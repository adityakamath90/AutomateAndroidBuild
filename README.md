# AutomateAndroidBuild

Sample app to demonstrate automated build generation.

Signing config to be mentioned in build.gradle and keystore path to be specified
for generating signed apk.

To generate build Navigate to gradlew.bat in root directory in command line.

For signed apk <br />
gradlew.bat assembleRelease <br />
For unsigned/debug apk <br />
gradlew.bat assembleDebug <br />

The build will be generated in the following folder.<br />
\AutomateAndroidBuild\example\app\build\outputs\apk
