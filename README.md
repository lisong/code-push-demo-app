# base on

fork from https://github.com/Microsoft/react-native-code-push examples

# iOS eg.

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

# codepush 热更新

```shell
$ code-push login http://api.code-push.com:8080 #登录code-push-server
$ code-push app add CodePushReactNativeDemo-ios  #iOS版
$ code-push app add CodePushReactNativeDemo-android #android版
$ cd /path/to/code-push-demo-app
$ npm install
$ code-push release-react CodePushReactNativeDemo-ios ios -d Production #发布到code-push-server ios
$ code-push release-react CodePushReactNativeDemo-android android -d Production #发布code-push-server android
```
