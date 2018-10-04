# Version 1.0

# Ban Lister

Ban Lister gathers bans from trusted secure servers and compiles a free to use public repository.

This plugin is connected to BanLister's ever-growing repository, allowing you full control over your user's fate when they don't meet your standards.

### Installation

Download the ZIP file and extract ```Rust-BanLister.cs``` addon to the addons folder.

### Configuration

Open ```BanLister.json``` from the Oxide Config directory and modify the following fields as follows.
```
"Ban Threshold": 15, -- If the user has equal to or more recorded bans then this value, then the user will be kicked from the server.
"Kick player from server if bans exceed the threshold": true -- if false, instead of kicking users for MaxBans a message will be sent to staff. If true a message won't be sent and the user will be kicked.
```

### Security

Our developers are committed to ensuring a full working and secure plugin. This plugin connects securely to our database both inserting and retrieving data when necessary. If you have further safety concerns or general questions your more then welcome to come and chat to a developer https://discord.gg/F7FH2nn

###### Developed by [SLUT](https://steamcommunity.com/profiles/76561198084594722/)
