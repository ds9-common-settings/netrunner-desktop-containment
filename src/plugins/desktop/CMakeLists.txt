set(netrunnerdesktopplugin_SRCS
    netrunnerdesktopplugin.cpp
    infonotification.cpp
    systemsettings.cpp
)

install(FILES qmldir DESTINATION ${QML_INSTALL_DIR}/org/kde/private/netrunnerdesktop/desktop)

add_library(netrunnerdesktopplugin SHARED ${netrunnerdesktopplugin_SRCS})

target_link_libraries(netrunnerdesktopplugin
                      Qt5::Core
                      Qt5::Qml
                      Qt5::Quick
                      Qt5::Widgets
                      KF5::Notifications)

install(TARGETS netrunnerdesktopplugin DESTINATION ${QML_INSTALL_DIR}/org/kde/private/netrunnerdesktop/desktop)
