# maestro-mobile-demo

Trying out maestro

- https://github.com/mobile-dev-inc/maestro
- https://maestro.mobile.dev/
- https://alexander.ghost.io/maestro-alternative-simpler-mobile-automation/



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

## Run
`maestro test <flow-yaml-here>`

Prefix with `time` to measure command execution

## Future
Utilise https://github.com/danielpaulus/go-ios for better iOS device control (not simulator)

## Issues
### Android
`Exception in thread "pool-2-thread-1" dadb.AdbStreamClosed: ADB stream is closed for localId: f6c11363`

### iOS
- Cannot connect to simulator frequently & consistently
- UI elements are not not always found, even though they're visible on screen