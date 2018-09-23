# cordova-vue

A simple Cordova iOS project with a Vue CLI 3 generated App.

Includes `vuex`, `vue-router`, `sass`, and linting with `eslint` and the `prettier` standard.

## Setup

First modify `config.xml` and `package.json` to change App name and details

Then install dependencies and prepare project:

```
yarn install
cordova prepare
```

## Generating icons and splashscreen for iOS

Install `cordova-icon` and `cordova-splash` globally:

```
yarn install -g cordova-icon cordova-splash
```

```
cordova-icon --icon=res/icon.png
cordova-splash --splash=res/splash.png
```

## Building app

```
yarn run build
```

## Running in iOS Simulator

Open `platforms/ios/<app-name>.xcworkspace` in Xcode and hit run
