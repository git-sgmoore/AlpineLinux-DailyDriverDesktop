# AlpineLinux-DailyDriverDesktop
My minimalist desktop running Alpine Linux 

https://www.alpinelinux.org/


```root
setup-alpine
us
us
localhost
eth0
UTC
none
none
1
none
busybox
sda
sys
y
reboot


setup-dns
8.8.8.8:1.1.1.1
rc-service networking restart
adduser sgm
setup-apkrepos
apk -U upgrade
setup-xorg-base

apk add accounts-qml-module accountsservice acct adwaita-gtk2-theme adwaita-icon-theme alpine-base alpine-baselayout alpine-conf alpine-keys alsa-lib aom-libs apk-tools argon2-libs ark aspell-libs at-spi2-atk at-spi2-core atk atkmm attica attr autoconf automake avahi-libs bash binutils blkid boost-locale brotli-libs bubblewrap busybox busybox-initscripts busybox-suid bzip2-dev ca-certificates ca-certificates-bundle cairo cairo-gobject cairomm cdparanoia-libs cfdisk clang-libs cryptsetup-libs cups-libs dbus dbus-glib dbus-libs dbus-openrc dbus-x11 dconf dconf-editor desktop-file-utils device-mapper-event-libs device-mapper-libs dialog discount-libs dmraid docbook-xml docbook-xsl e2fsprogs e2fsprogs-libs elogind elogind-openrc enchant2 encodings eudev eudev-libs eudev-openrc exiv2 exo exo-libs expat faenza-icon-theme faenza-icon-theme-bash faenza-icon-theme-firefox faenza-icon-theme-gparted faenza-icon-theme-thunar faenza-icon-theme-xfce4-appfinder faenza-icon-theme-xfce4-panel falkon ffmpeg-libs file findmnt findutils firefox flac font-alias font-cursor-misc font-misc-misc fontconfig freetype fribidi fts garcon gcr-base gdbm gdk-pixbuf gettext gettext-asprintf gettext-dev gettext-libs ghostscript glib glib-dev glib-networking glibmm glslang gmp gnome-themes-extra gnupg gnutls gparted gpgme graphite2 grep gsettings-desktop-schemas gst-plugins-base gstreamer gtk+2.0 gtk+3.0 gtk-doc gtk-update-icon-cache gtkmm3 gvfs harfbuzz harfbuzz-icu hexchat hexdump hicolor-icon-theme hunspell hwids-net hwids-pci hwids-udev hwids-usb hyphen iceauth icu-libs ifupdown-ng intltool iso-codes jack jbig2dec json-c kaccounts-integration kactivities-libs kactivities-stats karchive kauth kbookmarks kcodecs kcompletion kconfig kconfigwidgets kcoreaddons kcrash kdbusaddons kdeclarative kdegraphics-mobipocket kdoctools keepassxc kfilemetadata kfind kglobalaccel kguiaddons ki18n kiconthemes kio kitemviews kjobwidgets kjs kmod kmod-libs kmod-openrc knotifications kompare kpackage kparts kpty kservice ktexteditor ktextwidgets kwallet kwidgetsaddons kwindowsystem kxmlgui lame lcms2 lddtree leafpad less libaccounts-glib libaccounts-qt libacl libarchive libass libassuan libasyncns libatasmart libattr libblkid libblockdev libbluray libbsd libbytesize libbz2 libc-utils libcanberra libcap libcap-ng libcdio libcdio-paranoia libcom_err libcrypto1.1 libcurl libdav1d libdjvulibre libdrm libdvdcss libdvdnav libdvdread libeconf libelf libelogind libepoxy libevdev libevent libexif libfdisk libffi libffi-dev libfontenc libgcc libgcrypt libgomp libgpg-error libgtop libgudev libhunspell libical libice libidn2 libinput-libs libintl libjpeg-turbo libkexiv2 libkomparediff2 libksba libldap libltdl libmagic libmount libnotify libogg libpciaccess libpcre16 libpcre2-16 libpcre32 libpcrecpp libplacebo libpng libproxy libpsl libpulse libqrencode librsvg libsamplerate libsasl libseccomp libsecret libsigc++ libsm libsmartcols libsndfile libsodium libsoup libspectre libsrt libssh libssl1.1 libstdc++ libtasn1 libtheora libtls-standalone libtool libunistring libusb libuuid libva libvdpau libvorbis libvpx libwebp libwnck3 libwoff2common libwoff2enc libwpe libwpebackend-fdo libx11 libxau libxcb libxcomposite libxcursor libxdamage libxdmcp libxext libxfce4ui libxfce4util libxfixes libxfont2 libxft libxi libxinerama libxkbcommon libxkbcommon-x11 libxkbfile libxklavier libxml2 libxml2-utils libxmu libxpresent libxrandr libxrender libxres libxscrnsaver libxshmfence libxslt libxt libxtst libxv libxxf86vm libzip lightdm lightdm-gtk-greeter lightdm-openrc linux-headers linux-pam linux-virt llvm10-libs lrzip lsblk lsof lua5.1 lua5.1-libs lua5.2-libs lua5.3-libs lz4-libs lzo m4 make mcookie mesa mesa-dri-classic mesa-dri-gallium mesa-dri-intel mesa-egl mesa-gbm mesa-gl mesa-glapi mesa-xatracker mkfontscale mkinitfs mozjs78 mpfr4 mpv mtdev mtools musl musl-utils ncurses-libs ncurses-terminfo-base ndctl-libs nettle network-manager-applet networkmanager-elogind networkmanager-qt networkmanager-openvpn networkmanager-l2tp nghttp2-libs npth nspr nss ntfs-3g-libs ntfs-3g-progs nuspell okular okular-common openjpeg openrc openssl opus orc osmo p11-kit p7zip pango pangomm parted partx pciutils pciutils-libs pcre pcre-dev pcre2 perl perl-capture-tiny perl-devel-symdump perl-encode-locale perl-file-listing perl-html-parser perl-html-tagset perl-http-cookies perl-http-daemon perl-http-date perl-http-message perl-http-negotiate perl-io-html perl-libwww perl-lwp-mediatypes perl-net-http perl-pod-coverage perl-pod-parser perl-test-pod perl-try-tiny perl-uri perl-www-robotrules perl-xml-parser phonon pinentry pixman pkgconf polkit-elogind polkit-elogind-openrc polkit-qt-1 poppler poppler-glib poppler-qt5 purpose py3-appdirs py3-ordered-set py3-packaging py3-parsing py3-pygments py3-setuptools py3-six python3 qt5-qtbase qt5-qtbase-sqlite qt5-qtbase-x11 qt5-qtdeclarative qt5-qtmultimedia qt5-qtspeech qt5-qtsvg qt5-qttools qt5-qtwayland qt5-qtwebchannel qt5-qtwebengine qt5-qtx11extras quazip re2 readline scanelf sdl2 sed setpriv sfdisk shaderc shadow shared-mime-info signond slim slock snappy solid-libs sonnet sound-theme-freedesktop soxr speexdsp spirv-tools sqlite-libs ssl_client startup-notification sweeper syntax-highlighting syslinux taglib tdb-libs threadweaver thunar thunar-volman tiff ttf-cantarell ttf-dejavu tumbler uchardet udev-init-scripts udev-init-scripts-openrc udisks2 udisks2-libs unrar unzip upower usbutils util-linux util-linux-dev util-linux-openrc util-macros v4l-utils-libs vidstab virtualbox-guest-additions virtualbox-guest-additions-openrc volume_key vte3 vulkan-loader wayland-libs-client wayland-libs-cursor wayland-libs-egl wayland-libs-server webkit2gtk x264-libs x265-libs xauth xcb-util xcb-util-image xcb-util-keysyms xcb-util-renderutil xcb-util-wm xdg-dbus-proxy xf86-input-libinput xf86-input-synaptics xf86-video-sis xf86-video-vmware xfce-polkit xfce4 xfce4-appfinder xfce4-clipman-plugin xfce4-dev-tools xfce4-notifyd xfce4-panel xfce4-power-manager xfce4-session xfce4-settings xfce4-taskmanager xfce4-terminal xfce4-whiskermenu-plugin xfconf xfdesktop xfwm4 xinit xkbcomp xkeyboard-config xmodmap xorg-server xrdb xvidcore xz-libs yaml ykpers yubico-c zip zlib zlib-dev zstd zstd-libs
reboot

rc-update add dbus
rc-update add lightdm
rc-service dbus start
rc-service lightdm start

#su -
#TO INSTALL AWESOME
#vi /home/sgm/.xinitrc
##add line 'awesome'
#mkdir /home/sgm/.config
#cp -r /etc/xdg/awesome /home/sgm/.config
#reboot

#TO INSTALL DWM
#cd /home/sgm
#vi .xinitrc
## add line 'exec dwm'
#:wq
#vi .profile
## add line 'startx'
#:wq
#reboot
```

ʕ •́؈•̀)

I welcome feedback to help make this install more efficient and secure.
