Latest Version 
--------------
##### _Nov_ 19th, 2018_ - [v1.13.7](https://github.com/devtodev-analytics/android-sdk/releases/latest)

```
dependencies {
    implementation 'com.devtodev:android:1.13.7'
}
```

Getting Started
---------------
Full description of the integration process of devtodev SDK and all the accessible features can be found on the page with [official devtodev documentation](https://www.devtodev.com/help/39).

ProGuard
---------------
Add following lines at the bottom of proguard.config
```
-keep class com.devtodev.** { *; }
-dontwarn com.devtodev.**
```

Changelog
---------
See [releases](https://github.com/devtodev-analytics/android-sdk/releases/).
