# Converting an existing React app to an Android app using the Ionic Capacitor.



Here's a react web application : https://iemeka.github.io/zuri-score/
Here's the Android Application Package file (after Converting the react app) : https://github.com/iemeka/zuri-score-mobile/blob/master/apk/debug/app-debug.apk

Requirements :
- Existing react app
- Ionic
- Android Studio
- xcode for IOS

Steps:
in the root directory :
1. create a capacitor.config.json file (link : https://github.com/iemeka/zuri-score-mobile/blob/master/capacitor.config.json)
2. create a ionic.config.json  (link : https://github.com/iemeka/zuri-score-mobile/blob/master/ionic.config.json)
3. build the react project. "npm run build"
4. install Iconic , Capacitor core , Capacitor CLI
For Android:
5. Create an android app with the existing react app. - "ionic capacitor add android"
6. Open the android project in the Android Studio.
   To see the app running:
    - create a Virtual Device or
    - Use a physical Device (your phone). Enable "USB debugging"
7. Build an Android Application Package file. The apk file can be used to install the app on any Android device. 
For iOS: Similar process with the use Xcode to run the app.