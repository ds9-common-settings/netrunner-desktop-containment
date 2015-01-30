# netrunner-desktop-containment
patched folderview containment


* remove "hamburger": plasma-package-org.kde.desktoptoolbox.desktop
 override upstream desktop toolbox.desktop file with version setting Hidden=true

* rename "Folder" to "Netrunner Desktop": override upstream folder metadata.desktop file with version setting different name
 (/usr/share/kservices5/plasma-applet-org.kde.plasma.folder.desktop)
