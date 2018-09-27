# expo-firebase example

Detached ExpoKit app with Expo Firebase modules installed.

![Hey there](https://media.giphy.com/media/Wy6BauP5Ztlmu7zvs8/giphy.gif)

# Tutorial

 1. Create an Expo project
    * Download the Expo-CLI `npm i -g expo-cli`
    * Create a new project `expo init expo-firebase-example`
    * Select any template.
    * Enter the project `cd expo-firebase-example`
 2. Eject to **ExpoKit**
    * Run `expo eject`
    * Select the option: `ExpoKit: I'll create or log in with an Expo account to use React Native and the Expo SDK.`
    * Add a bundle ID. ex: `com.whoareyou.expofirebaseexample`
    * Add an Android Package. (usually the same as bundle ID) ex: `com.whoareyou.expofirebaseexample`
 3. Add **Expo-Firebase**
    * In the root directory of your project run: `yarn add expo-firebase-app` or `npm i expo-firebase-app`
    * Follow the setup guide for [`expo-firebase-app`](https://www.npmjs.com/package/expo-firebase-app)
 4. Use `expo-firebase`
    * In your `App.js` or anywhere in the js. Use **firebase** like `import firebase 'expo-firebase-app';`
 5. Add simple services
    * Use any other firebase services by following their setup instructions.
      * [`expo-firebase-app`](https://www.npmjs.com/package/expo-firebase-app)
      * [`expo-firebase-analytics`](https://www.npmjs.com/package/expo-firebase-analytics)
      * [`expo-firebase-database`](https://www.npmjs.com/package/expo-firebase-database)
      * [`expo-firebase-storage`](https://www.npmjs.com/package/expo-firebase-storage)
      * [`expo-firebase-firestore`](https://www.npmjs.com/package/expo-firebase-firestore)
      * [`expo-firebase-performance`](https://www.npmjs.com/package/expo-firebase-performance)
      * [`expo-firebase-auth`](https://www.npmjs.com/package/expo-firebase-auth)
      * [`expo-firebase-instance-id`](https://www.npmjs.com/package/expo-firebase-instance-id)
      * [`expo-firebase-remote-config`](https://www.npmjs.com/package/expo-firebase-remote-config)
      * [`expo-firebase-functions`](https://www.npmjs.com/package/expo-firebase-functions)
    * Remember to import the services before using them. ex: `import 'expo-firebase-database';`
 6. Advanced services can be used by following the setup in [`AppDelegate.m`](https://github.com/EvanBacon/expo-native-firebase/blob/master/ios/demofirebasemodulesapp/AppDelegate.m)

   