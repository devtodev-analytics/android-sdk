Latest Version
--------------
##### _June 24, 2021_ - [v1.14.10](https://github.com/devtodev-analytics/android-sdk/releases/latest)

```
If you use Gradle, please add mavenCentral() into gradle.build of your application
and then add the line “implementation com.devtodev:android:1.14.10” into dependencies.
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
