#Setting up MonkeyTalk for iOS and Android

### Installing MonkeyTalk agents on application 
 
1. Open Terminal
2. Navigate to cordova project directory 
3. Install MonkeyTalk plugin from github using the cordova command-line interface

```
$ cordova plugin add https://github.com/sarahgoldman/cordova-monkeytalk-ios-plugin.git
```

***(Non-developers start here)***
### Testing with MonkeyTalk IDE

1. Download MonkeyTalk IDE: [downloads page](https://www.cloudmonkeymobile.com/download/monkeytalk-community)
2. Create a new Project
3. While the app is running in a simulator or device, connect to the app
4. File > New > Script
	- record script (MonkeyTalk > Record or red circle)
	- stop recording script (MonkeyTalk > Record or red circle)
	- manually edit script if needed
	- use Component Tree if needed (Component Tree tab in bottom panel)
5. Play script (green triangle)
6. Reports and screenshots are generated in folders inside the project