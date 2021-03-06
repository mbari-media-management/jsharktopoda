![MBARI logo](src/site/resources/images/logo-mbari-3b.png)

# jsharktopoda


[![Build Status](https://travis-ci.org/mbari-media-management/jsharktopoda.svg?branch=master)](https://travis-ci.org/mbari-media-management/jsharktopoda)

![Sharktopoda](src/site/resources/images/icon_256x256.png)


JavaFX-based video player for macOS, Linux, and Windows. Provides remote UDP interface for integration with other apps. See [REQUIREMENTS.md](https://github.com/mbari-media-management/Sharktopoda/blob/main/docs/REQUIREMENTS.md) for the UDP remote interface specification.

A java implementation of a remote control is available in the [vcr4j-sharktopoda](https://github.com/mbari-media-management/vcr4j/tree/master/vcr4j-sharktopoda) module of [vcr4j](https://github.com/mbari-media-management/vcr4j)

## Build

Builds are tested using Java 11 for compilation and Java 14 for packaging. 

```bash
export JPACKAGE_HOME=/path/to/jdk14
gradlew jpackage --info
```

The generated applications are:

- Applicaiton image including packaged JDK: `build/image`
- Application packaged for OS: `build/jpackage`

## Screenshot

![Screenshot](src/site/resources/images/jsharktopoda.png)

## Download

You can download JSharktopoda, as a Java jar, from [bintray](https://bintray.com/hohonuuli/generic/download_file?file_path=jsharktopoda-0.1.3-app.jar)

## Java 11 building

<https://medium.com/@adam_carroll/java-packager-with-jdk11-31b3d620f4a8>
