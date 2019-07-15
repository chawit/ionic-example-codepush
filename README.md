# ionic-example-codepush
This repository is an example ionic application, which use CodePush service.

## Requirement
-CodePush Account.(See in https://appcenter.ms/) <br>
-Setting your app (See in https://docs.microsoft.com/en-us/appcenter/sdk/getting-started/cordova)

## Tutorial
1. Add CodePush Plugin <br>
```
cordova plugin add cordova-plugin-code-push@latest
```
2. Edit config.xml(add key from CodePush Server)
```
<platform name="android">
    <preference name="CodePushDEV" value="Your KEY(android)" />
</platform>
<platform name="ios">
    <preference name="CodePushDEV" value="our KEY(ios)" />
</platform>
```
