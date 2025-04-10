# flutter_useragent

[![Pub](https://img.shields.io/pub/v/user_agent_client.svg)](https://pub.dartlang.org/packages/flutter_useragent)
[![Awesome Flutter](https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square)]()
[![Awesome Flutter](https://img.shields.io/badge/Platform-Android_iOS-blue.svg?longCache=true&style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](/LICENSE)

Retrieve Android/iOS device user agents in Flutter.

### Example user-agents:

| System  | User-Agent                                                                     | WebView User-Agent                                                                                                                                                 |
| ------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| iOS     | CFNetwork/897.15 Darwin/17.5.0 (iPhone/6s iOS/11.3)                            | Mozilla/5.0 (iPhone; CPU iPhone OS 11_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Mobile/15E217                                                      |
| Android | Dalvik/2.1.0 (Linux; U; Android 5.1.1; Android SDK built for x86 Build/LMY48X) | Mozilla/5.0 (Linux; Android 5.1.1; Android SDK built for x86 Build/LMY48X) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/39.0.0.0 Mobile Safari/537.36 |

### Additionally:

Every version returns some additional constants that might be useful for custom user-agent building.

iOS version returns:

- isEmulator
- systemName
- systemVersion
- applicationName
- applicationVersion
- buildNumber
- darwinVersion
- cfnetworkVersion
- deviceName
- packageUserAgent

Android version returns:

- systemName
- systemVersion
- packageName
- shortPackageName
- applicationName
- applicationVersion
- applicationBuildNumber
- packageUserAgent
