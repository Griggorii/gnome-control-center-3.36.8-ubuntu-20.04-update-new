# gnome-control-center-3.36.8-ubuntu-20.04-source-deb
ubuntu 20.04 , gnome-control-center-3.36.8 , fix resize

https://youtu.be/45iNZPhmIas install meson , ninja

Support https://www.youtube.com/channel/UC6WtVfU5gi2CQ4ionzbz1CQ and donate dollar card visa VISA 4817 7601 8112 4706 thanks

Deb package ubuntu 20.04 generation https://github.com/Griggorii/gnome-control-center-3.36.8-ubuntu-20.04-update-new/releases/tag/ubuntu-20.04

$ sudo apt --reinstall install autopoint comerr-dev debhelper dh-autoreconf dh-migrations dh-strip-nondeterminism dh-translations docbook docbook-to-man docbook-xml docbook-xsl dwz gir1.2-cheese-3.0 gir1.2-clutter-gst-3.0 gir1.2-colord-1.0 gir1.2-colordgtk-1.0 gir1.2-gkbd-3.0 gir1.2-grilo-0.3 gir1.2-gsound-1.0 gir1.2-harfbuzz-0.0 gir1.2-modemmanager-1.0 gnome-pkg-tools gnome-settings-daemon-dev gobject-introspection gsettings-desktop-schemas-dev gtk-doc-tools icu-devtools intltool krb5-multidev libaccountsservice-dev libarchive-zip-perl libatk-bridge2.0-dev libatk1.0-dev libatspi2.0-dev libblkid-dev libbrotli-dev libcairo2-dev libcanberra-dev libcanberra-gtk-common-dev libcanberra-gtk3-dev libcheese-dev libcheese-gtk-dev libclutter-1.0-dev libclutter-gst-3.0-dev libclutter-gtk-1.0-dev libcogl-dev libcogl-pango-dev libcogl-path-dev libcolord-dev libcolord-gtk-dev libcups2-dev libcupsimage2-dev libdatrie-dev libdebhelper-perl libdrm-dev libegl-dev libegl1-mesa-dev libepoxy-dev libevdev-dev libexpat1-dev libffi-dev libfile-stripnondeterminism-perl libfile-which-perl libfontconfig1-dev libfreetype-dev libfreetype6-dev libfribidi-dev libgdk-pixbuf2.0-dev libgirepository1.0-dev libgl-dev libgl1-mesa-dev libgles-dev libgles2-mesa-dev libglib2.0-dev libglvnd-dev libglx-dev libgnome-bluetooth-dev libgnome-desktop-3-dev libgnomekbd-dev libgoa-1.0-dev libgoa-backend-1.0-dev libgraphite2-dev libgrilo-0.3-dev libgsound-dev libgssrpc4 libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libgstreamer1.0-dev libgtk-3-dev libgtop2-dev libgudev-1.0-dev libharfbuzz-dev libibus-1.0-dev libice-dev libicu-dev libinput-dev libjbig-dev libjpeg-dev libjpeg-turbo8-dev libjpeg8-dev libjson-glib-dev libkadm5clnt-mit11 libkadm5srv-mit11 libkdb5-9 libkrb5-dev libmm-glib-dev libmount-dev libmtdev-dev libnm-dev libnma-dev libnotify-dev libopengl-dev liborc-0.4-dev liborc-0.4-dev-bin libosp5 libpango1.0-dev libpcre2-32-0 libpcre2-dev libpcre2-posix2 libpcre3-dev libpcrecpp0v5 libpng-dev libpolkit-gobject-1-dev libpsl-dev libpthread-stubs0-dev libpulse-dev libpwquality-dev librest-dev libseccomp-dev libsecret-1-dev libselinux1-dev libsepol1-dev libsm-dev libsmbclient-dev libsnapd-glib-dev libsoup2.4-dev libsqlite3-dev libsub-override-perl libsystemd-dev libthai-dev libtiff-dev libtiffxx5 libtool libudisks2-dev libupower-glib-dev libwacom-dev libwayland-dev libwhoopsie-preferences-dev libx11-dev libx11-xcb-dev libxau-dev libxcb-render0-dev libxcb-shm0-dev libxcb1-dev libxcomposite-dev libxcursor-dev libxdamage-dev libxdmcp-dev libxext-dev libxfixes-dev libxft-dev libxi-dev libxinerama-dev libxkbcommon-dev libxklavier-dev libxml2-dev libxrandr-dev libxrender-dev libxtst-dev modemmanager-dev opensp pango1.0-tools po-debconf python3-dbusmock python3-lxml python3-markdown python3-packaging python3-pygments python3-pyparsing python3-scour scour sgml-data uuid-dev x11proto-core-dev x11proto-dev x11proto-input-dev x11proto-randr-dev x11proto-record-dev x11proto-xext-dev x11proto-xinerama-dev xml-core xorg-sgml-doctools xsltproc xtrans-dev

$ tar xvpf gnome-control-center-3.36.8.tar.xz /tmp

$ cd /tmp/gnome-control-center-3.36.8/obj-x86_64-linux-gnu

$ sudo mkdir /root

$ ninja install

$ cd /tmp/gnome-control-center-3.36.8

$ quilt refresh && quilt refresh

Deb package generate

$ dpkg-buildpackage -rfakeroot -b -d

$ sudo apt purge autopoint comerr-dev debhelper dh-autoreconf dh-migrations dh-strip-nondeterminism dh-translations docbook docbook-to-man docbook-xml docbook-xsl dwz gir1.2-cheese-3.0 gir1.2-clutter-gst-3.0 gir1.2-colord-1.0 gir1.2-colordgtk-1.0 gir1.2-gkbd-3.0 gir1.2-grilo-0.3 gir1.2-gsound-1.0 gir1.2-harfbuzz-0.0 gir1.2-modemmanager-1.0 gnome-pkg-tools gnome-settings-daemon-dev gobject-introspection gsettings-desktop-schemas-dev gtk-doc-tools icu-devtools intltool krb5-multidev libaccountsservice-dev libarchive-zip-perl libatk-bridge2.0-dev libatk1.0-dev libatspi2.0-dev libblkid-dev libbrotli-dev libcairo2-dev libcanberra-dev libcanberra-gtk-common-dev libcanberra-gtk3-dev libcheese-dev libcheese-gtk-dev libclutter-1.0-dev libclutter-gst-3.0-dev libclutter-gtk-1.0-dev libcogl-dev libcogl-pango-dev libcogl-path-dev libcolord-dev libcolord-gtk-dev libcups2-dev libcupsimage2-dev libdatrie-dev libdebhelper-perl libdrm-dev libegl-dev libegl1-mesa-dev libepoxy-dev libevdev-dev libexpat1-dev libffi-dev libfile-stripnondeterminism-perl libfile-which-perl libfontconfig1-dev libfreetype-dev libfreetype6-dev libfribidi-dev libgdk-pixbuf2.0-dev libgirepository1.0-dev libgl-dev libgl1-mesa-dev libgles-dev libgles2-mesa-dev libglib2.0-dev libglvnd-dev libglx-dev libgnome-bluetooth-dev libgnome-desktop-3-dev libgnomekbd-dev libgoa-1.0-dev libgoa-backend-1.0-dev libgraphite2-dev libgrilo-0.3-dev libgsound-dev libgssrpc4 libgstreamer-plugins-base1.0-dev libgstreamer-plugins-good1.0-dev libgstreamer1.0-dev libgtk-3-dev libgtop2-dev libgudev-1.0-dev libharfbuzz-dev libibus-1.0-dev libice-dev libicu-dev libinput-dev libjbig-dev libjpeg-dev libjpeg-turbo8-dev libjpeg8-dev libjson-glib-dev libkadm5clnt-mit11 libkadm5srv-mit11 libkdb5-9 libkrb5-dev libmm-glib-dev libmount-dev libmtdev-dev libnm-dev libnma-dev libnotify-dev libopengl-dev liborc-0.4-dev liborc-0.4-dev-bin libosp5 libpango1.0-dev libpcre2-32-0 libpcre2-dev libpcre2-posix2 libpcre3-dev libpcrecpp0v5 libpng-dev libpolkit-gobject-1-dev libpsl-dev libpthread-stubs0-dev libpulse-dev libpwquality-dev librest-dev libseccomp-dev libsecret-1-dev libselinux1-dev libsepol1-dev libsm-dev libsmbclient-dev libsnapd-glib-dev libsoup2.4-dev libsqlite3-dev libsub-override-perl libsystemd-dev libthai-dev libtiff-dev libtiffxx5 libtool libudisks2-dev libupower-glib-dev libwacom-dev libwayland-dev libwhoopsie-preferences-dev libx11-dev libx11-xcb-dev libxau-dev libxcb-render0-dev libxcb-shm0-dev libxcb1-dev libxcomposite-dev libxcursor-dev libxdamage-dev libxdmcp-dev libxext-dev libxfixes-dev libxft-dev libxi-dev libxinerama-dev libxkbcommon-dev libxklavier-dev libxml2-dev libxrandr-dev libxrender-dev libxtst-dev modemmanager-dev opensp pango1.0-tools po-debconf python3-dbusmock python3-lxml python3-markdown python3-packaging python3-pygments python3-pyparsing python3-scour scour sgml-data uuid-dev x11proto-core-dev x11proto-dev x11proto-input-dev x11proto-randr-dev x11proto-record-dev x11proto-xext-dev x11proto-xinerama-dev xml-core xorg-sgml-doctools xsltproc xtrans-dev




