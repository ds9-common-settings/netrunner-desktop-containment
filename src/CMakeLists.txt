add_definitions(-DTRANSLATION_DOMAIN=\"plasma_applet_org.kde.netrunnerdesktop\")
add_subdirectory(plugins)
plasma_install_package(package org.kde.netrunnerdesktop plasmoids containment)
