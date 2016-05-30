# AutomateAndroidBuild

Sample app to demonstrate automated build generation.

Signing config to be mentioned in build.gradle and keystore path to be specified
for generating signed apk.

Navigate to gradlew.bat in root directory in project
For signed apk 
gradlew.bat assembleRelease
For unsigned/debug apk
gradlew.bat assembleDebug

The build will be generated in the following folder.
\AutomateAndroidBuild\example\app\build\outputs\apk
