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

### License

MIT &copy; Armno P.

