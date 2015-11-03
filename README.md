# maven-password-decrypter-example

This project contains a basic example which shows how to use the [maven-password-decrypter][1] to access encrypted Maven credentials within a Gradle build.

The `build.gradle` file should be fairly self explanatory.

To test the project out run `./gradlew uploadArchives`, the example credentials provided and the Artifactory urls are all fictitious so the upload actually upload anything anywhere. 

[1]: https://github.com/eddgrant/maven-password-decrypter.git