#ruby 1.9.3 or 2.1 installation required to open idb
#use following command if not installed:
rvm install 2.1 --enable-shared

#Below two commands enough to set up idb for Kali 2.0

apt-get install cmake libqt4-dev git-core libimobiledevice-utils libplist-utils usbmuxd libxml2-dev libsqlite3-dev -y

gem install idb
