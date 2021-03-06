# testbed_native_ios

This app illustrates how to integrate the react-react-native-branch@2.0.0-beta.1-branch SDK into a React Native component within an existing native iOS app.

The app was produced following the methodology outlined in these tutorials:

- https://facebook.github.io/react-native/docs/integration-with-existing-apps.html
- https://www.raywenderlich.com/136047/react-native-existing-app

In particular, it uses the `React`, `react-native-branch` and `Branch-SDK` pods from node_modules.

## Building

To build and run, install NPM dependencies using `npm install` or `yarn` and then run `pod install`, e.g.

```bash
yarn
pod install
```

Note that since all pods are taken from node_modules, the `--repo-update` argument to `pod install` is unnecessary.
