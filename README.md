[![Travis](https://img.shields.io/travis/rakshans1/docker-android.svg)](https://travis-ci.org/rakshans1/docker-android)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/android.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/android/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/android/latest.svg)]()


![rakshans1/android](/icon.png?raw=true)
# android 8 (1.8.0_111)
### based on [Java 8 (1.8.0_111)](https://github.com/rakshans1/docker-java)
----
- Ant 1.9.6
- Maven 3.3.9
- Java 1.8.0_111
- Gradle 2.10 (Groovy 2.4.5)
- Android SDK 24.4.1
    + APIs: android-10,android-15,android-16,android-17,android-18,android-19,android-20,android-21,android-22,android-23,android-24,android-25
    + Build-Tools: 25.0.2

----
## Tagging scheme
- `v${TOOLS_VERSION}-${BUILD_TOOLS_VERSION}-${HIGHEST_ANDROID_SDK_VERSION}`
- e.g. `v25.2.5-27.0.0-26`
----
### Pull from Docker Hub
```
docker pull rakshans1/android:latest
```

### Build from GitHub
```
docker build -t rakshans1/android github.com/rakshans1/docker-android
```

### Run image
```
docker run -it rakshans1/android bash
```

### Use as base image
```Dockerfile
FROM rakshans1/android:latest
```