# androidAppWo
Android Web App constructed using HTML5,CSS3,AngularJS,JavaScript and packaged using PhoneGap and Cordova for android.

For more information - please check the link below -

You need Android Studio to deploy it in the Emulator or run it on your Android device

For more Information -

http://docs.phonegap.com/en/edge/guide_platforms_android_index.md.html#Android%20Platform%20Guide


Some useful commands below:

How to run this within Android Studio
1. Open Android Studio - Click on File - New - Project - Project From Version Control - GitHub
2. Enter the GitHub details - For Git Repository URL - https://github.com/manabshy/androidAppWo.git
3. Click on Clone
4. Configur the project - Please notice for a message  - "Android project detected"
5. Open the Terminal Window in Android Studio or a separate one
6. Run the below commands to build the app and launch it in emulator


cordova phonegap

$ cordova create hello com.example.hello HelloWorld
$ cd hello
$ cordova platform add android
$ cordova build
$ cordova emulate android   /* This pushes the app to the home screen - Emulator and launches it: */

In Android Studio

File - New - Import Project

select the folder - “android" inside platforms as below

/Users/manan/Sites/myproject/phonegap_projects/wo/platforms/android

Preview it in the emulator

*** how to modify ***

Modify the codes
Start the build as described above
Preview it in the emulator

