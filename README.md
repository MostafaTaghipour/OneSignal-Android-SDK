<p align="center">
  <img src="https://media.onesignal.com/cms/Website%20Layout/logo-red.svg"/>
</p>

### OneSignal Android Push Notification Plugin
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.onesignal/OneSignal/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.onesignal/OneSignal) [![Build Status](https://app.travis-ci.com/OneSignal/OneSignal-Android-SDK.svg?branch=main)](https://app.travis-ci.com/OneSignal/OneSignal-Android-SDK)

---

[OneSignal](https://onesignal.com/) is a free email, sms, push notification, and in-app message service for mobile apps. This plugin makes it easy to integrate your native Android or Amazon app with OneSignal.

<p align="center"><img src="https://app.onesignal.com/images/android_notification_image.gif" width="400" alt="Android Notification"></p>

### Installation
To install this library, do the following


#### Step 1 - Download or CLone Library

First thing you’ll need download or clone current repository.

<img src="screenshots/1.jpg" width="400" >



#### Step 2 - Import Library as Module

Then you should import onesignal as module in Android Studio.

<img src="screenshots/2.jpg" width="500" >

<img src="screenshots/3.jpg" width="600" >



#### Step 3 - Add one signal as dependency

Add the dependency to your app/build.gradle file:

```
implementation project(path: ':onesignal')
```

See OneSignal's [Android Native SDK Setup Guide](https://documentation.onesignal.com/docs/android-sdk-setup) for next steps and more documentation.

### API
See OneSignal's [Android Native SDK API](https://documentation.onesignal.com/docs/android-native-sdk) page for a list of all available methods.

### Change Log
See this repository's [release tags](https://github.com/OneSignal/OneSignal-Android-SDK/releases) for a complete change log of every released version.

### Support
Please visit this repository's [Github issue tracker](https://github.com/OneSignal/OneSignal-Android-SDK/issues) for feature requests and bug reports related specifically to the SDK.
For account issues and support please contact OneSignal support from the [OneSignal.com](https://onesignal.com) dashboard.

### Demo Project
To make things easier, we have published demo projects in the `/Examples` folder of this repository.

### Supports:
* Tested from Android 4.1.0 (API level 16) to Android 12 (31)