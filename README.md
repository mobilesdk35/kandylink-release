# kandylink-release

To add MobileSDK dependency add your root gradle maven dependency with given url.

```
allprojects {
    repositories {
    ....
        maven {
            url "https://raw.githubusercontent.com/mobilesdk35/kandylink-release/master/releases/"
        }   
    }
}
```

and add dependcy of MobileSDK to app gradle.

```
implementation 'com.genband.spidr.android:MobileSDK:4.6.1.3'
```
