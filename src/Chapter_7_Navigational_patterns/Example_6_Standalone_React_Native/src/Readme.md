This is the standalone React Native app

Please read the following guidelines:

[Getting started with React Native](https://facebook.github.io/react-native/docs/getting-started.html)

Before you proceed with launch install `react-native-cli`.

```
npm install -g react-native-cli
```

To launch particular simulator use

```react-native run-ios```

or

```react-native run-android```

# FAQ

##### I'm getting "Unable to resolve module " errors
Run `react-native start --reset-cache`

##### I'm getting ":CFBundleIdentifier, Does Not Exist" error
See [":CFBundleIdentifier", Does Not Exist #7308](https://github.com/facebook/react-native/issues/7308)

Removing `node_modules` and running `react-native upgrade` may fix this.
