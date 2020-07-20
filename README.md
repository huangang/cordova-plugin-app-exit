# ExitApp PhoneGap/Cordova Plugin
changed support cordova 7.0+ & publish npm list

### Supported Platforms

- Android
- iOS
- Browser*

\* _Only for development purpose._

### Version Requirements

This plugin is meant to work with Cordova 3.5.0+.

### Installation

#### Automatic Installation using PhoneGap/Cordova CLI (iOS and Android)
1. Make sure you update your projects to Cordova iOS version 3.5.0+ before installing this plugin.

        cordova platform update ios
        cordova platform update android

2. Install this plugin using PhoneGap/Cordova cli:

        cordova plugin add https://github.com/huangang/cordova-plugin-app-exit.git
        cordova plugin add cordova-plugin-app-exit

### Usage

    navigator.app.exitApp();
