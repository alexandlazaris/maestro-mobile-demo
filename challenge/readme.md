# cross platform challenge

## General
* framework used: [Maestro](https://github.com/mobile-dev-inc/maestro)
* screen recordings included for both platforms
* run both platforms using simulators

## Android
* https://github.com/testproject-io/android-demo-app/blob/master/APK/testproject-demo-app.apk
* android run cmd: `maestro test android-{fileName}.yaml`
* requires android emulator to be running prior to test
* once the test is executed, it will auto-attach the first available android device

## iOS
* https://github.com/testproject-io/ios-demo-app
* ios run cmd: `maestro test ios-{fileName}.yaml`
* using ios simulator uuid 90BD2531-C13E-471A-9185-C978CF0036D3 (ios v14)
* requires `idb_companion --udid 90BD2531-C13E-471A-9185-C978CF0036D3` to be run in a separate process before running test


## Dependencies
* Android Studio, Android emulator, adb (for debugging)
* XCode (manages all other dependencies also)
