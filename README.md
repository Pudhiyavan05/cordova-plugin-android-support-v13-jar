# Android Support Library v13

revision 23.2.1, `1443358 bytes`

## Contents

This package contains the latest `android-support-v13.jar` file from Android SDK.

- https://developer.android.com/topic/libraries/support-library/features.html#v13
- https://developer.android.com/reference/android/support/v13/app/package-summary.html

## Install

```
cordova plugin add cordova-plugin-android-support-v13-jar
```

## How to upgrade

Upgrade Android SDK support library

- start Android SDK Manager with running command `android`
- check item `Extras` / `Android Support Library`
- upgrade if available
- write down the latest revision number

If the revision number is greater than the jar file of this plugin, it is upgradeable.

Check file size and overwrite the jar file to the plugin library

```
ls -l /usr/local/var/lib/android-sdk/extras/android/support/v13/android-support-v13.jar
copy /usr/local/var/lib/android-sdk/extras/android/support/v13/android-support-v13.jar .
```

Modify the version number in `plugin.xml` and save.
