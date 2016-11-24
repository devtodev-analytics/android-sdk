Latest Version 
--------------
##### _Oct 27st, 2016_ - v1.9

```
dependencies {
    compile 'com.devtodev:sdk:1.9'
}
```

Getting Started
---------------
Check out our [official documentation](https://www.devtodev.com/help/35/android/) to learn how to install the library on your IDE. You will also learn how to make use of all the features we currently support!

Changelog
---------
See [releases](https://github.com/devtodev-analytics/android-sdk/releases/).

#### Version 1.9
* Migration to FCM protocol for push processing. Previous GCM will no longer be supported.
* Added interactivity to push-notifications: buttons, sharing, URLs, deeplinks, sound control.
* Distribution of SDK in AAR package, in addition to the JAR to simplify the integration.
* Ability to send "quiet push-notifications"

#### Version 1.8.1
* Added possibility to generate several progression events within one session

#### Version 1.8
* Added new "Progression event". First of all, the event is used for the games with short (within one game session) locations, game levels. The event allows you to gather data on passing the locations and get statistics on parameters which vary during the the location passing.
* Android N support

#### Version 1.7.2
* Referral tracking was improved

#### Version 1.7.1
* Improvements of user profile feature.

#### Version 1.7.0
* User profile feature is added. Here you can store properties about a specific user.
- New methods for managing preset and custom properties of user profile are added.
- Old methods: age, gender and cheater, are removed. These properties are moved to user profile.
* Initial referrer data tracking method is added
* Stability improvement

#### Version 1.6.11
* Improved stability

#### Version 1.6.10
* Improved compatibility with older sdk versions

#### Version 1.6.9
* Added possibility to call events before  SDK initialization
* Custom push icons setters was added

#### Version 1.6.8
* Fix mac-address issue

#### Version 1.6.7
* Added ability to customize images in android push-notifications

#### Version 1.6.6
* Encoding parameters was changed

#### Version 1.6.5
* Some minor improvements

#### Version 1.6.4
* Push events fixed

#### Version 1.6.3
* Added the gathering of user's time zone data to provide the ability to send push notifications considering user's time
* Added the ability to control the color of LED indicator while push-notification goes in
* Other negligeable improvements.

#### Version 1.6.2
* Push migration to GCM

#### Version 1.6.1
* Improvement of the user identification in cross-platform projects

#### Version 1.6
* SDK preparation for usage in cross-platform projects: added methods for user initialization (UserID, ReplaceUserId, SetCurrentLevel).
* Other negligeable improvements.

#### Version 1.5.4 
* Fixed bug with reset user level.
* Fixed bug with events, called immediately after init.

#### Version 1.5.3
* Blocking of certain events from SDK.
* Improvement of new user calculation method.
* Change of session length calculation method.

#### Version 1.5.1
* The start/finish constants of the tutorial are added to the tutorial steps event.
* Filtering of resending for once committed tutorial steps is made.
* Constants with the names of popular social networks are added to connecting and posting to social networks events.
* Collecting data about "rooted" devices.
* Method for getting devtodev SDK integrated version.
* Method for immediate dispatching of events.
* Method for getting the app installation source (id of the application store).

#### Version 1.5
* Unified SDK! No more need to use multiple small files, it's enough to integrate one library.
* In-game purchases for several in-game currencies.
* An ability to track currency/resources circulation and balances upon moving to the next level.
