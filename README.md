# Udacity IOS Developer Nanodegree Graduation Project : Rooms

This app allows users to create a beautiful chat to send text/photo messages to any participant who is registered in this app.
The data messages and communications between users is based on Firebase.
The app have many view controller scenes.
• Welcome View Controller: Allows the user register a new account, or sign in via his Facebook or Google account.
Via tab bar controller you can choose between two view controllers : 1- Settings View Controller.
2- Chats View Controller.
• Settings View Controller: Allows the users to make any changes to his resisted informations
• Chats View Controller: Displays a list of chats between the current user and other users.
• AddUser View Controller: Displays the list of all registered accounts, and allows the user to select one of them.
• Chat View Controller: Allows the users to send / receive messages to another registered account.
The scenes are described in detail below.
![Screen Shot 2019-12-08 at 11 38 34 PM](https://user-images.githubusercontent.com/46827335/70396752-6981be00-1a14-11ea-80d2-09d42f59531b.png)

Settings
The user can change his Display name from SettingsViewController.
![Screen Shot 2019-12-08 at 11 38 47 PM](https://user-images.githubusercontent.com/46827335/70396755-6d154500-1a14-11ea-8882-95a1f79c5455.png)

Chats View Controller:
It displays the chats between user and his participants using customer TableView cells.
The user can see the profile picture, display name of his participant and also the messages between each others.
IF the user select any message cell it navigates him to Chat View Controller.
Also the user can add a new participant chat user by pressing the add user button in right navigation item, which navigates him to AddUsers to Chat View Controller.
![Screen Shot 2019-12-08 at 11 38 52 PM](https://user-images.githubusercontent.com/46827335/70396757-70a8cc00-1a14-11ea-85c5-099476d4a774.png)

AddUsers Chat View Controller:
It displays all registered users, when the user select any cell, which contains user profile picture, display name and email, it navigates him to Room View Controller.
![Screen Shot 2019-12-08 at 11 39 03 PM](https://user-images.githubusercontent.com/46827335/70396761-73a3bc80-1a14-11ea-87ee-fb54c68ff8a3.png)


Chat View Controller
The user can send/receive messages to participant user by typing the message text into bottom textField and hit Send button.
The message customer cell displays the message which contains :
- Display name of message’s sender.
- The message Body.
- The profile picture of message’s sender.
![Screen Shot 2019-12-08 at 11 41 56 PM](https://user-images.githubusercontent.com/46827335/70396762-769ead00-1a14-11ea-87d1-313e8293ff62.png)

