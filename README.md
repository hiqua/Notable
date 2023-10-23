## Notable

Notable is an app for Android notification reminders

The original version hasn't been updated in a while and can no longer be installed directly because of new security restrictions of Android 14. You can still install it using `adb install --bypass-low-target-sdk-block THE_APK.apk` though.

This fork:
* updates the SDK used so that it's possible to install it on Android 14.
* removes the scheduling feature as I don't use it and it seemed that the library it depends on caused build problems (I didn't dig further though).

Released under GPLv3.
