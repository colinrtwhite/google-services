# Google Services Gradle Plugin

This plugin converts the google-services.json file for Firebase into a set of resources that the Firebase libraries can use. It also references the strict-version-matcher plugin, and will execute those checks as well. 

## Usage

Add [JitPack](https://jitpack.io) to your list of repositories:

```groovy
repositories {
    maven { url 'https://jitpack.io' }
}
```

And add the library to your list of dependencies:

```groovy
buildscript {
    dependencies {
        classpath 'com.github.colinrtwhite:google-services-plugin:4.3.0'
    }
}
```
