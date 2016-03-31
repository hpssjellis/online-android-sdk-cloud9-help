a05-clone-github-android-studio-project-HELP




Some Android Studio repositories are very difficult to get working
Remember to load resources as well

Best Method. Clone the Android Studio github Repository, Then in main folder edit

build.gradle to include the lines (or an equivalent SDK version example 22, 23)

compileSdkVersion 20

buildToolsVersion 23.0.2


And add a local.properties file with only this line

sdk.dir=/usr/local/android-sdk-linux



