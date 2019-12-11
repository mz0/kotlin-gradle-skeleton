# Kotlin + Gradle skeleton

A starting point for Kotlin projects. Build and run: `./gradlew -q run`.

### On deprecated features warning

Kotlin 1.2/1.3 Gradle plugins always trigger the following message
```
Deprecated Gradle features were used in this build, making it incompatible with Gradle 6.0.
```
for their use of deprecated `DefaultSourceDirectorySet`. You may hide that with `-q` option, e.g. `./gradlew -q clean`
