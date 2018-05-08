Cordova Kiosk App Demo
======================

This example use **cordova-plugin-kiosk** - see https://github.com/hkalina/cordova-plugin-kiosk

To run this demo app after checkout:
------------------------------------

    cordova prepare
    ANDROID_HOME=/opt/android-sdk cordova run

To create new similar app:
--------------------------

    cordova create cordova-kiosk-demo jk.cordova.kioskdemo CordovaKioskDemo
    cd cordova-kiosk-demo
    cordova plugin add https://github.com/hkalina/cordova-plugin-kiosk.git
    ANDROID_HOME=/opt/android-sdk cordova run

To remove app from device use adb:
----------------------------------

    $ANDROID_HOME/platform-tools/adb uninstall jk.cordova.kioskdemo

**WARNING** Before installation ensure you have USB debug mode enabled. Without it you can have a problem to remove the app from device.

