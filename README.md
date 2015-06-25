#Setting up MonkeyTalk for iOS

### Installing MonkeyTalk agents on application 
 
1. Open Terminal
2. Navigate to cordova project directory 
3. Install MonkeyTalk plugin from github using the cordova command-line interface

```
$ cordova plugin add https://github.com/sarahgoldman/cordova-monkeytalk-ios-plugin.git
```

***(Non-developers start here)***
### Testing with MonkeyTalk IDE

1. Download and install MonkeyTalk IDE: [downloads page](https://www.cloudmonkeymobile.com/download/monkeytalk-community)
	- Unzip the downloaded file
	- Mac users: Move the MonkeyTalkIDE folder to your Applications folder, then double click on the MonkeyTalk app file inside
	- Windows users: Move the MonkeyTalkIDE folder into your Program Files folder, then and double click on MonkeyTalk.exe to run
	- Choose a location for your MonkeyTalk workspace (outside of Applications/Program Files)
2. Create a new Project
3. While the app is running in a simulator or device, connect to the app using the Connect menu
4. File > New > Script
	- Record script (MonkeyTalk > Record or red circle)
	- Stop recording script (MonkeyTalk > Record or red circle)
	- Manually edit script if needed
	- Use Component Tree if needed (Component Tree tab in bottom panel)
5. Play script (green triangle)
6. Reports and screenshots are generated in folders inside the project