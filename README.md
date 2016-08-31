# base on

fork from https://github.com/Microsoft/react-native-code-push examples

# ios eg.

```shell
$ cd /path/to/code-push-demo-app
$ npm install
$ open ios/CodePushDemoApp.xcodeproj
```

# android eg.

```shell
$ cd /path/to/code-push-demo-app
$ npm install
$ cd android
$ ./gradlew assembleRelease
$ cd app/build/outputs/apk #install app-release.apk into your phone
```

# codepush热更新

```
$ cd /path/to/code-push-demo-app
$ code-push release-react ios_CodePushDemo ios -d Production
```