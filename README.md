Latest Version
--------------
##### _June 7, 2021_ - [v1.14.9](https://github.com/devtodev-analytics/android-sdk/releases/latest)

```
Attention! At the moment, SDK version 1.14.9 is only available on GitHub,
because the Bintray services we used before are terminated.
In the near future, we will find an alternative service.
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
