# netrunner-desktop-containment
patched folderview containment


* remove "hamburger": 
 override desktop toolbox.desktop file with version setting Hidden=true
 (/usr/share/kservices5/plasma-package-org.kde.desktoptoolbox.desktop)


* rename "Folder" to "Netrunner Desktop":
 override folder.desktop file with version setting different name
 (/usr/share/kservices5/plasma-applet-org.kde.plasma.folder.desktop)
