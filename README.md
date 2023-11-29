# App Tracker

### App Tracker is a Discord bot for monitoring iOS AppStore applications. DM’s you when an application you’re monitoring has received an update!

Invite to your server: https://discord.com/oauth2/authorize?client_id=1175934288332607668&scope=bot&permissions=8

***

#### TABLE OF CONTENTS (COMMANDS)
* Watch-List
* Search
* Add
* Update
* Remove
* Help
* More
* Source


#### WATCH-LIST
Each user has their own “watch-list”, a track list where the user’s applications will be managed through. This list contains all the user’s application and can only be managed by the corresponding user. The user can add, remove and update this list. A maximum of 3 applications is allowed per user. Contact me via iOSGods if you make mods and want to be whitelisted to add more!

Running the command will send a message with all the applications in the watch-list listed, along with their bundle identifier, version, name and status (up-to-date or outdated). Passing the parameter "o" will yield a list with only the outdated applications.

Usage: `.watchlist OR .wl o`

![](https://i.imgur.com/JTdwnIb.png)


#### SEARCH
Users can search the AppStore for applications. A message with information about the first matching application will be sent. This information will contain the applications name, publisher, version, update date, price, rating, icon and bundle identifier. The search result can then be added directly to the users watch-list.

Usage: `.search <appname>`

![](https://i.imgur.com/DdL7MFP.png)

### ADD
Users can add applications to their watch-list using the applications bundle identifier. Multiple applications can be added at once by separating the bundle identifiers with a whitespace.

Usage: `.add <bundle identifier>`

![](https://i.imgur.com/vwB5LXE.png)

#### UPDATE
Users can update the version of the application in their watch-list to the latest version available, making the application up-to-date in the watch-list.

Usage: `.update <bundle identifier>`

![](https://i.imgur.com/q9F026M.png)


#### REMOVE
Users can remove applications from their watch-list using the applications bundle identifier.

Usage: `.remove <bundle identifier>`

![](https://i.imgur.com/OBObW1D.png)


#### HELP
A list of all the commands available to the command issuer will be sent with a brief description of each command.

Usage: `.help`


#### MORE
A message containing more information about the specified command will be sent. This information contains aliases, a description and the usage syntax for the command.

Usage: `.more <command>`


#### SOURCE
A message with information about this bot and its author will be sent.

Usage: `.source`


#### UPDATE NOTIFICATION

![](https://i.imgur.com/PzhnKVU.png)
