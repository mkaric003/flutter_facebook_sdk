# Facebook Sdk For Flutter

![GitHub code size](https://img.shields.io/github/languages/code-size/saadfarhan124/sadfarhan124-facebook_flutter_plugin)
![GitHub followers](https://img.shields.io/github/followers/saadfarhan124?style=social)
![GitHub contributors](https://img.shields.io/github/contributors/saadfarhan124/sadfarhan124-facebook_flutter_plugin)
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/saadfarhan124/)
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/saadfarhan124/)

`facebook_sdk_flutter` allows you to fetch `deep links`, `deferred deep links` and `log facebook app events`.

This was created using the latest facebook SDK to include support for iOS 14. The plugin currently only supports app events and deeps links for iOS. 

## Prerequisites

First of all, if you don't have one already, you must first create an app at Facebook developers: https://developers.facebook.com/

Get your app id (referred to as [APP_ID] below)

* If your code does not have CFBundleURLTypes, add the following just before the final </dict> element:
```
 <key>CFBundleURLTypes</key>
    <array>
      <dict>
      <key>CFBundleURLSchemes</key>
      <array>
        <string>fb[APP_ID]</string>
      </array>
      </dict>
    </array>
    <key>FacebookAppID</key>
    <string>[APP_ID]</string>
    <key>FacebookDisplayName</key>
    <string>[DISPLAY_NAME]</string>
    <key>FacebookAutoLogAppEventsEnabled</key>
    <true/>
    <key>FacebookAdvertiserIDCollectionEnabled</key>
    <true/>
```
