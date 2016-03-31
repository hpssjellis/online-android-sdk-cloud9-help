a05-clone-github-android-studio-project-HELP




Some Android Studio repositories are very difficult to get working
Remember to load resources as well

Best Method. Clone the Android Studio github Repository, Then in main folder edit

build.gradle to include the lines (or an equivalent SDK version example 22, 23)

compileSdkVersion 20

buildToolsVersion 23.0.2


And add a local.properties file with only this line

sdk.dir=/usr/local/android-sdk-linux






echo ""
echo "Now in another terminal have a look at your new folders build.gradle file"
echo "Compare it to the build.gradle file in the folder helloGradle"
echo "Change the following lines to work on this system"
echo "The important lines are:"
echo "compileSdkVersion 20"
echo "buildToolsVersion 23.0.2"
echo ""
echo "The SDK version simply has to be an sdk platform you have already installed. See the above list"
echo ""
echo "The buildToolsVersion must be one that works for this system"
echo ""
echo "You may want to also check that the file local.properites looks correct for this workspace"
echo "hit enter when those lines are OK"
read
