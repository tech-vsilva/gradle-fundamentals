# How to run

```
gradle wrapper
```


It will generate the `./gradlew` file:

    .
    ├── build
    │   ├── libs
    │   │   └── 1.3-introduction-to-gradle-wrapper.jar
    │   └── tmp
    │       └── jar
    │           └── MANIFEST.MF
    ├── build.gradle
    ├── gradle
    │   └── wrapper
    │       ├── gradle-wrapper.jar
    │       └── gradle-wrapper.properties
    ├── gradlew
    ├── gradlew.bat
    └── README.md


Now you can run `./gradlew`. Next time you run it, it will download the gradle version that we specified.

    ./gradlew build
    Downloading https://services.gradle.org/distributions/gradle-4.2-bin.zip
    ...................................................................
    Unzipping /home/vasi/.gradle/wrapper/dists/gradle-4.2-bin/cl9xe1l8k8ophj72k8rv6xbu7/gradle-4.2-bin.zip to /home/vasi/.gradle/wrapper/dists/gradle-4.2-bin/cl9xe1l8k8ophj72k8rv6xbu7
    Set executable permissions for: /home/vasi/.gradle/wrapper/dists/gradle-4.2-bin/cl9xe1l8k8ophj72k8rv6xbu7/gradle-4.2/bin/gradle
    Starting a Gradle Daemon (subsequent builds will be faster)

    BUILD SUCCESSFUL in 35s
    1 actionable task: 1 executed

As you can see, gradle were downloaded and installed at your home directory: `~/.gradle/wrapper/`
