# React Native Firestore<a href="https://rnfirebase.io"><img align="left" src="http://i.imgur.com/01XQL0x.png"></a>

---

Follow this tutorial to make basic react native app with [`react-native-firebase`](https://github.com/invertase/react-native-firebase) pre-integrated  to get you started quickly.

---


### Getting Started
We're doing to practice with Firestore, how can we use and how can we intergrate in our application. So at first, you can download my repository or follow `rnfirebase.ios` to create the base project, they're intergrating firebase into react-native very well. Let's enjoy! ^ ^!

#### 1) Clone & Install Dependencies

- 1.1) `git clone https://github.com/l0ptruong/react-native-firebase-firestore.git`
- 1.2) `cd react-native-firebase-starter` - cd into your newly created project directory.
- 1.3) Install NPM packages with your package manager of choice - i.e run `yarn` or `npm install`
- 1.4) **[iOS]** `cd ios` and run `pod install` - if you don't have CocoaPods you can follow [these instructions](https://guides.cocoapods.org/using/getting-started.html#getting-started) to install it.
- 1.5) **[Android]** No additional steps for android here.

#### 2) Rename Project

**You will need to be running Node verison 7.6 or greater for the rename functionality to work**

- 2.0) **[iOS]** `cd ..` to return to the root directory of the project
- 2.1) `npm run rename` - you'll be prompted to enter a project name and company name
- 2.2) Note down the package name value - you'll need this when setting up your Firebase project

#### 3) Add `Google Services` files (plist & JSON)

- 3.1) **[iOS]** Follow the `add firebase to your app` instructions [here](https://firebase.google.com/docs/ios/setup#add_firebase_to_your_app) to generate your `GoogleService-Info.plist` file if you haven't done so already - use the package name generated previously as your `iOS bundle ID`.
- 3.2) **[iOS]** Place this file in the `ios/` directory of your project.
- 3.3) **[Android]** Follow the `manually add firebase` to your app instructions [here](https://firebase.google.com/docs/android/setup#manually_add_firebase) to generate your `google-services.json` file if you haven't done so already - use the package name generated previously as your `Android package name`.
- 3.4) Place this file in the `android/app/` directory of your project.
  
#### 4) Start your app

- 4.1) Start the react native packager, run `yarn run start` or `npm start` from the root of your project.
- 4.2) **[iOS]** Build and run the iOS app, run `npm run ios` or `yarn run ios` from the root of your project. The first build will take some time. This will automatically start up a simulator also for you on a successful build if one wasn't already started.
- 4.3) **[Android]** If you haven't already got an android device attached/emulator running then you'll need to get one running (make sure the emulator is with Google Play / APIs). When ready run `npm run android` or `yarn run android` from the root of your project.

If all has gone well you'll see an initial screen like the one below.
  
## Screenshots

![preview](https://i.imgur.com/4lG4HuS.png)


## Contributors

This project exists thanks to all the people who contribute. [[Contribute]](CONTRIBUTING.md).
<a href="graphs/contributors"><img src="https://opencollective.com/react-native-firebase/contributors.svg?width=890" /></a>


### License

- See [LICENSE](/LICENSE)


### Developer
- [Johnny]
