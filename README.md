# maestro-mobile-demo

Trying out maestro - https://github.com/mobile-dev-inc/maestro

https://maestro.mobile.dev/


## Dependencies 
- run `brew tap mobile-dev-inc/tap`
- run `brew install maestro`

Real devices or simulator (it will auto-run on whichever is available & connected)

### Android 
- Android Studio
- Java 

### iOS
- Xcode
- run `brew tap facebook/fb`
- run `brew install facebook/fb/idb-companion`
- run `idb_companion --udid {id of the iOS device}`, use `xctrave list devices` to show available uuids
https://support.apple.com/en-au/guide/deployment/depece748c41/web

- iPhone SE (2nd generation) (14.0.1) (90BD2531-C13E-471A-9185-C978CF0036D3)
- iPhone 14 Pro Max Simulator (16.0) (CD5F595C-92F8-4007-B079-F305B40AC007)


## Future
Utilise https://github.com/danielpaulus/go-ios for better iOS device control (not simulator)


## Issues
### Android
`Exception in thread "pool-2-thread-1" dadb.AdbStreamClosed: ADB stream is closed for localId: f6c11363`

### iOS
Cannot connect to simulator frequently & consistently