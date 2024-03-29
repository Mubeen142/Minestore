# Minestore

[<img alt="spigot" src="https://lielamar.com/cdn/plugins/github_spigot.png" size=1.5>](https://www.spigotmc.org/resources/minestore-proof-of-concept-a-flexible-open-source-webstore.86795/)
<br>[<img alt="discord" src="https://lielamar.com/cdn/plugins/github_discord.png" size=1.5>](https://discord.gg/NzgBrqR)
<br>

## Information
Minestore is an online store solution for Minecraft servers.
It serves more as a “proof of concept”, to show that server owners can securely sell perks on their server, avoiding most “refund” issues.

More information can be found [HERE](https://docs.google.com/document/d/1Gqy6RHqojxX5QjQuuB6GWjKTvyUgBUTPidzOyTKpOa4)

* This plugin was developed from scratch and is not related to Buycraft by any means.
It is in no way a complete plugin and is advised not to be used until a full version is released!

This source-code is a structure, a point to start off, a framework for other developers to continue building their store upon it.


## Features
* MySQL Integration
* Purchase history with full information
* Paypal Integration
* Secure Client-Side
* Socket communication between Minecraft and Web Server
* Authentication System
* Item Giving & Command Executing Systems


## What's next?
* <strong>FIX THE PAY NOW BUTTON FFS</strong>
* Block Sockets from IPs not listed in config
* Update the 'Delivered' column on the database when giving a player their package 
* Add Bungeecord Support (including handling per-server commands)
* Adding an option to have an auto-authenticate for players who don't want to secure their purchases
* Check the unit limit to make sure players don't buy something they already have/too many times
* Adding an option to turn debug messages on and off to avoid console spam
* Make the plugin fully customizable textwise
* Switching to SSL Socket Communication
* Making the packages non-static by implementing a database call before loading the /category/ pages.
* Add Sponge Support(?)
* Add MongoDB Support(?)
* Make cleaner code with notes

## Using Liel's Minestore
You are allowed to use this code under the GPL 3 License.
You can contact me through my email @ liel@lielamar.com, or through Spigot/Discord for further explanation.
When using this code you are allowed to change anything about it, however, some things may not work properly if you change them.
This framework is trying to be the best version of itself. It still has some bugs to fix and features to add, but overall, it serves it's initial purpose.

* It was tested with Paper/Spigot version 1.8.8 (v1_8_R3) but SHOULD work on every version.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GPL 3](https://choosealicense.com/licenses/agpl-3.0/)
