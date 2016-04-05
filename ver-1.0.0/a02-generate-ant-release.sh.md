#a02-generate-ant-release.sh.md



##Making a release version

The problem is that your keystore signing of your app should be kept private but that is very difficult to do on a cloud 9 free account

On the free account you really only have 2 options.
1. Have your App on a github site, fully sign your release version on Cloud 9 and then delete the cloud 9 workspace. Do not just delete the App folder since revision control can reverse the deletion


1. Make a local version of the cloud 9 workspace. Then sign your app on your own computer which should be a bit safer. For more info about making a local version of the workspace see [local-workspace](https://github.com/hpssjellis/online-android-sdk-cloud9-help/blob/master/version-1.0.0-android-sdk-help/other/local-workspace.md)



