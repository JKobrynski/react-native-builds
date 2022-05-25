# React Native builds example

The goal of this project is to exemplify multiple environment setup in React Native for both iOS and Android.

### Environments

This project contains two environments: **dev** and **live**. (*.env files are not gitignored on purpose*). The application's name is dependent on the environment that is used, so is the *.env* file.

### Running different builds

Check out the **scripts** section in [package.json](https://github.com/JKobrynski/react-native-builds/blob/main/package.json) for available build/run commands on Android. 
To change the environment for the iOS app, select the desired variant on the top bar in XCode and press the button next to it to run the build.

### Setup

To see how this is done on the Android side, check out this [build.gradle](https://github.com/JKobrynski/react-native-builds/blob/main/android/app/build.gradle) file and [these folders](https://github.com/JKobrynski/react-native-builds/tree/main/android/app/src)
(for each environment).

You can open the iOS project in XCode and check out how different environments are set up.