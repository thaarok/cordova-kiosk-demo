Howto create Cordova Kiosk app
==============================

This example use **cordova-plugin-kiosk** - see https://github.com/honza889/cordova-kiosk-demo

To create new similar app:

    cordova create cordova-kiosk-demo jk.cordova.kioskdemo CordovaKioskDemo
    cd cordova-kiosk-demo
    cordova plugin add https://github.com/honza889/cordova-plugin-kiosk.git
    ANDROID_HOME=~/MAF/android-sdk-linux/ cordova run

To remove app from device use adb:
----------------------------------

    $ANDROID_HOME/platform-tools/adb uninstall jk.cordova.kioskdemo

**WARNING** Before installation ensure you have USB debug mode enabled. Without it you will have problem to remove app from device.

