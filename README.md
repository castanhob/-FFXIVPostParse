Mognet Plugin
=============
A simple plugin for ACT [(Advanced Combat Tracker)](http://advancedcombattracker.com/home.php), which allows your parses from Final Fantasy XIV to be sent to a Discord Guild chat, through the [Mognet Bot](https://discordapp.com/oauth2/authorize?client_id=322436422646628352&scope=bot&permissions=0).

With a fairly simple setup, the purpose of this plugin is to help the players of Final Fantasy XIV have a tool where one can post parses and share numbers between FC/Raid members. This also enables PS4 players to track their performance without having to ask party members to post their numbers manually everytime.

Requisites
----------
In order to make this plugin to work properly, you will need to have both below installed and configured:

* [Advanced Combat Tracker](https://advancedcombattracker.com/download.php)
* [Ravahn's FFXIV_ACT_Plugin](https://github.com/ravahn/FFXIV_ACT_Plugin)

Also, be sure to download the latest version of the plugin on the [releases](https://github.com/Aida-Enna/MognetPlugin/releases) page!

Setup
-----
Check the [wiki](https://github.com/Aida-Enna/MognetPlugin/wiki/Mognet-Setup-Guide).

Commands
--------
* !create-token : It sends you a private message with the token to allow ACT Mognet Plugin to post messages on the requested channel. Only works if the bot has write permission on the channel.
* !recreate-token : It recreates a token on the requested channel.
* !remove-token: It disables a previously generated token, making the bot unable to post logs through ACT Mognet Plugin on the requested channel.
* !mognet-help: It shows the list of available commands.

Contributing
------------

1. [Fork it](https://github.com/Aida-Enna/MognetPlugin/fork)
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

You can also contribute by posting bug reports or feature requests into the [issues](https://github.com/Aida-Enna/MognetPlugin/issues) section.
The server side code is private right now, but I'll make it public soon!
