# React-native Example

Using both the `randomCirclePoint` and `randomCircumferencePoint`
functions to create a Smiley above Twitter's HQ:

<img alt="React-Native Example" width=300px src="https://github.com/rmrs/random-location/raw/master/examples/react-native/example.png">

Currently the example is only for **Android**. Nevertheless, if you need an **iOS** version of it just open an issue and I'll make one for you.

## Make example work

To make the example work you'll have to:

1. Get a Google Maps API Key from:  https://developers.google.com/maps/documentation/android-api/signup
2. Substitude "`<GOOGLE_MAPS_API_KEY>`" in [AndroidManifest.xml](./random_location/android/app/src/main/AndroidManifest.xml) with it.

Then simply:

```bash
$ cd random_location
$ npm install
$ react-native run-android
$ npm start
```
