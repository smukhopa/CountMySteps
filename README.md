Fitness Tracking
============

Fitness tracking application using the Sensors API, History API and Recording API on the Android Fit platform.


Pre-requisites
--------------

- Android API Level > 9
- Android Build Tools v23
- Android Support Repository
- Register a Google Project with an Android client per getting started instructions
  http://developers.google.com/fit/android/get-started

Support
-------

The most common problem using these samples is a SIGN_IN_FAILED exception. Users can experience
this after selecting a Google Account to connect to the FIT API. If you see the following in
logcat output then make sure to register your Android app underneath a Google Project as outlined
in the instructions for using this sample at: http://developers.google.com/fit/android/get-started

`10-26 14:40:37.082 1858-2370/? E/MDM: [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}`

Use the following channels for support:

- Google+ Community: https://plus.google.com/communities/103314459667402704958
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-fitness/issues