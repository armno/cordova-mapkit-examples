# Cordova apps with Mapkit plugin

Using [MapKit plugin](https://github.com/imhotep/MapKit/) with Cordova apps. Currently working only on iOS platform.

## iOS

```sh
$ cordova create com.example.mapkittest "MapKitTest"
$ cordova plugin add com.phonegap.plugins.mapkit
$ cordova platform add ios
$ cordova build ios
```

you can also search for the plugin (in case plugin's id changed for any reason)

```sh
$ cordova plugin search mapkit
```

### screenshot

![cordova-ios-mapkit](https://raw.github.com/armno/cordova-mapkit-examples/master/screenshots/ios-iphone4.png)

## Issues
- only working on ios when install via cordova cli. got build errors on android
- map's size doesn't fit in 4-inches iphones
- extra steps needed when install via cordova cli.

### License

MIT &copy; Armno P.

