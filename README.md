# React Native Web Boilerplate 🥘 with navigation 🗺

@RandGor version inspired by updating [inspmoore/rnw_boilerplate_nav](https://github.com/inspmoore/rnw_boilerplate_nav) repo.

## Installing 🔩

Clone the repo and run

```
npm i --force
```

to install all the dependencies.

## Scripts ️️️⚙️

### `yarn start-web` or `npm run start-web`

Runs your app in the browser under the http://localhost:3000.

### `yarn start` or `npm run start`

Starts metro bundler for your react native project.

### `yarn start-ios` or `npm run start-ios`

Runs metro bundler and opens the app in the iOS simulator.

### `yarn build` or `npm run build`

Builds your web app for production.

### `yarn test` or `npm run test`

Runs the test environment for the native part.

### `yarn test-web` or `npm run test-web`

Runs the test environment for the web part.

### `yarn eject` or `npm run eject`

Eject your web project to your custom setup.

## Usage 🛠

Folder and file structure is also a result of combination of create-react-app and react-native boilerplates.

```
rnw_boilerplate
├── android
├── ios
├── node_modules
├── public
├── src
│    ├── NativeWebRouteWrapper
│    │    ├── index.js
│    │    ├── pop.native.js
│    │    └── pop.web.js
│    ├── App.js
│    ├── App.native.js
│    ├── DasModalScreen.js
│    ├── HomeScreen.js
│    ├── index.js - web index file
│    ├── registerServiceWorker.js
│    ├── SecondScreen.js
│    ├── TopNav.js
│    ├── UserScreen.js
│    └── UserScreen.native.js
├── app.json
├── index.js - native index file
├── package.json
└── README.md
```

`HomeScreen.js` file is an example of a component shared between the platforms. Thanks to React Native Web lib, it is possible to use React Native primitives in the Web environment. Please check out [RNW guide](https://github.com/necolas/react-native-web) for more details.

Also notice that there are separate `App.js` files for Web and Native. This gives a lot of advantages, including adding platform specific libraries to your app.

There are also separete `UserScreen.js` files for Web and Native. It is because new Navigation library requires new appreaches and does not support the old one (as Web).

## Renaming the app ✏️

This boilerplate comes with ios and android bundles already named. If you want to (and you should) change the name, use the [react-native-rename](https://github.com/junedomingo/react-native-rename) lib.

## Demo React Native true multiplatform 🌐

If you did everything correctly, you will get the following result:

## Android 📱
![Android](https://i.imgur.com/Ln6rBzl.png)

## Web 💻
![Web](https://i.imgur.com/fRRp1P9.png)

## Contribution ❤️

You are welcome to ask everything or contribute.