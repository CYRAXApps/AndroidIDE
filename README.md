## AndroidIDE

[![AndroidIDE](https://img.shields.io/badge/Download-Letest_Release-blue?style=for-the-badge)](https://github.com/CYRAXApps/AndroidIDE/releases/tag/AndroidIDE)

### Terminal Setup
1:- nano $PREFIX/etc/apt/sources.list


2:- deb [trusted=yes] https://packages.androidide.com/apt/termux-main/ stable main


3:- cd && pkg upg && idesetup -c


4:- cd && pkg upgrade && pkg install wget && wget https://github.com/MrIkso/AndroidIDE-NDK/raw/main/ndk-install.sh --no-verbose --show-progress -N && chmod +x ndk-install.sh && bash ndk-install.sh


5:- nano /data/data/com.itsaky.androidide/files/home/.androidide/init/init.gradle


If you have any problems setup it up, you can watch my tutorial video.
https://github.com/CYRAXApps
