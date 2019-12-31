EggTimer - Final Code 
============================================================================

Solution code for Advanced Android with Kotlin Codelab 

Content: http://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-notifications-fcm

Introduction
------------

EggTimer is a timer app for cooking eggs.
You can start and stop the timer, choose different cooking intervals.. 

In this codelab, working from this starter app, you:

* Add notitications to the eggtimer app.
* Use channels and importance for the app notifications. 
* Customize and style the notifications.

Pre-requisites
--------------

You should be familiar with:

* Services, AlarmManager, Broadcast Receivers.

Getting Started
---------------

1. Download
2. Swtich to start branch
3. Run the app.

Lab path
--------

### 4. Adding Firebase to your Android project

1. Create a Firebase project
1. Register your app with Firebase
1. Add the Firebase configuration file to your project
1. Configure your Android project to enable Firebase products

### 5. Starting with Firebase Cloud Messaging

#### 5.1. Sending FCM notifications to a single device

1. [AndroidManifest.xml](http://github.com/dscoppelletti/android-kotlin-notifications-fcm/blob/attend/app/src/main/AndroidManifest.xml)
    * Step 3.0 - Uncomment to start the service
1. [EggTimerFragment.kt](http://github.com/dscoppelletti/android-kotlin-notifications-fcm/blob/attend/app/src/main/java/com/example/android/eggtimernotifications/ui/EggTimerFragment.kt)
    * Step 3.1 - Create a new channel for FCM
1. [MyFirebaseMessagingService.kt](http://github.com/dscoppelletti/android-kotlin-notifications-fcm/blob/attend/app/src/main/java/com/example/android/eggtimernotifications/MyFirebaseMessagingService.kt)
    * Step 3.2 - Log registration token

#### 5.1. Sending FCM Notifications to a Topic

1. [EggTimerFragment.kt](http://github.com/dscoppelletti/android-kotlin-notifications-fcm/blob/attend/app/src/main/java/com/example/android/eggtimernotifications/ui/EggTimerFragment.kt)
    * Step 3.3 -  Subscribe to breakfast topic
    * Step 3.4 - Call subscribe topics on start

### 6. Sending data with FCM

#### 6.1. Data messages

1. [MyFirebaseMessagingService.kt](http://github.com/dscoppelletti/android-kotlin-notifications-fcm/blob/attend/app/src/main/java/com/example/android/eggtimernotifications/MyFirebaseMessagingService.kt)
    * Step 3.5 - Check messages for data

#### 6.2. Handling messages in the foreground and background

1. [MyFirebaseMessagingService.kt](http://github.com/dscoppelletti/android-kotlin-notifications-fcm/blob/attend/app/src/main/java/com/example/android/eggtimernotifications/MyFirebaseMessagingService.kt)
    * Step 3.6 - check messages for notification and call sendNotification

References
----------

* [Publish-Subscribe pattern](http://en.wikipedia.org/wiki/Publish-subscribe_pattern)
