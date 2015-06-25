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
3. Connect to the app
	- Via Wi-Fi
		- Start the app on the device
		- Go to Settings > Wi-Fi on your device
		- Click the blue info button for the network you have selected
		- Find the IP Address, should be the first field listed under the DHCP tab
		- In MonkeyTalk select iOS Device under the Connect menu
		- Enter the IP address of the device in the MonkeyTalk IDE
	- Via Simulator
		- Start the app in the iOS Simulator
		- In MonkeyTalk select iOS Simulator under the Connect menu
4. Create a new test script
	- Go to File > New > Script
	- Record script (MonkeyTalk > Record or red circle)
	- Stop recording script (MonkeyTalk > Record or red circle)
	- Manually edit script if needed
	- Use Component Tree if needed (Component Tree tab in bottom panel)
5. Play script (green triangle)
6. Reports and screenshots are generated in folders inside the project