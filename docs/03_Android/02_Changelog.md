### Version 1.4.7
Released: 2017-01-19

* [BUGFIX] Improved VisualSupport.
* [BUGFIX] Increased buffers to help app with log bursts.

### Version 1.4.6
Released: 2017-01-12

* [NEW] Support for VisualSupport.

### Version 1.4.5
Released: 2016-12-27

* [IMPROVEMENT] Minor performance improvement on inspect element component.

### Version 1.4.4
Released: 2016-12-15

* [IMPROVEMENT] Auto Update is supported for Android 7 and targetSdkVersion > 23 .

### Version 1.4.3
Released: 2016-11-29

* [BUGFIX] Fix sessions that was detected as on background from the first seconds.

### Version 1.4.2
Released: 2016-11-28

* [BUGFIX] Fix a bug related to TextureView screenshot while the app in the background.

### Version 1.4.0
Released: 2016-11-21

* [NEW] We added an API for stopping sessions, so you can stop and restart session according to your own specific logic [See java doc](https://app.testfairy.com/reference/android/).
* [BUGFIX] We fixed a minor memory-leak.

### Version 1.3.11
Released: 2016-11-06

* [BUGFIX] Fix double start session issue

### Version 1.3.10
Released: 2016-10-26

* [IMPROVEMENT] - Auto Update behaviour improved for apps that has services.

### Version 1.3.9
Released: 2016-09-29

* [IMPROVEMENT] When there is no connection and tester tries to send a feedback, an error messgae is shown.
* [IMPROVEMENT] Multiple clicks on the send feedback button will send it only once.
* [BUGFIX] NullPointerException exceptions fixed

### Version 1.3.8
Released: 2016-09-20

* [BUGFIX] Drawing on feedback screenshot will work on devices with disabled animation.

### Version 1.3.7
Released: 2016-09-19

* [NEW] A new session can be created when app is back in foreground.

### Version 1.3.5
Released: 2016-08-30

* [BUGFIX] Feedback module can now be initialized without an existing activity.

### Version 1.3.4
Released: 2016-08-08

* [NEW] Adaptive screenshot interval - When heavy work detected on the UI thread, screenshot interval is increased automatically.


### Version 1.3.3
Released: 2016-08-07

* [BUGFIX] Fix auto update and feedback for React Native.
* [BUGFIX] Fix auto update and feedback for Unity.
* [BUGFIX] Fix auto update and feedback for Adobe Air.
* [BUGFIX] Fix auto update and feedback for Xamarin.
* [BUGFIX] Fix auto update and feedback for PhoneGap/Cordova.
* [BUGFIX] Fix auto update and feedback for Titanium.


### Version 1.3.2
Released: 2016-07-20

* [BUGFIX] Attach screenshot checkbox behaviour

### Version 1.3.1
Released: 2016-07-17

* [NEW] New UI for feedback module.
* [NEW] Added an option to add screenshot to feedbacks and have screenshots sent to JIRA automatically.
* [NEW] Added an option to draw on screenshot.
* [NEW] Feedback now contains screen name (actvity name).
* [NEW] Screen Name (activity name) is now sent to JIRA automatically via API.
* [IMPROVE] Improved Logcat reader performance. 

### Version 1.2.10 
Released: 2016-06-21

* [NEW] Added confirmation dialog before auto update.
* [BUGFIX] Support for >2GB apk auto-update downloads.
* [BUGFIX] Cancel download during auto update.

### Version 1.2.9 
Released: 2016-06-09

* [NEW] Added log() method, to send logs to TestFairy without passing logcat.
* [BUGFIX] Word-wrapping when filing in a feedback.
* [BUGFIX] Changing orientation during 'Would you like to provide feedback' dialog disabled it.
* [BUGFIX] Fixed hints in feedback form under certain Android themes.

### Version 1.2.8 
Released: 2016-06-01

* [BUGFIX] Feedback dialog fixed.

### Version 1.2.7
Released: 2016-05-31

* [NEW] `ACCESS_WIFI_STATE` is no longer mandatory, [More information](http://docs.testfairy.com/Android/Integrating_Android_SDK.html#permissions).
* [NEW] Detect sessions recorded from an Android service.
* [NEW] `TestFairy.setScreenName(String screenName)` function added, for more information [SDK reference](http://app.testfairy.com/reference/android/com/testfairy/TestFairy.html#setScreenName(java.lang.String)).
* [NEW] `TestFairy.addEvent(String event)` added to the SDK, `TestFairy.addCheckpoint()` is deprecated.
* [BUGFIX] Session videos are now supported on Android N.

### Version 1.2.5
Released: 2016-05-24

* [BUGFIX] All Proguard warnings are fixed.

### Version 1.2.4
Released: 2016-05-01

* [NEW] Customize feedback form with optional/mandatory email field.
* [NEW] Request callback from feedback form upon success, failure or cancellation.
* [NEW] Optionally configure a URL to open instead of built-in feedback form. [More information](http://docs.testfairy.com/Android/Customizing_feedback_dialog.html).

### Version 1.2.3
Released: 2016-04-24

* [BUGFIX] Fixed memory leak on switching activities.

### Version 1.2.2
Released: 2016-04-21

* [NEW] Auto-update builds if newer is available.
* [NEW] Auto-update detects non-upgradable builds (ie, downloaded from Play Store).
* [NEW] User can decide not to upgrade, and keep sending metrics on old build.
* [BUGFIX] Fixed warnings when using Proguard.

### Version 1.1.0
Released: 2016-04-07

* INITIAL NON-BETA RELEASE.
