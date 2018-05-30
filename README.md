# Groestlcoin Telegram Police Bot

This bot (when supplied with a valid Telegram Bot Token) will remove media messages on a per-chat-per-user basis if the parameters have been met (commands are included below).

## Building

Open the project in Visual Studio 2015 or greater, enter in your token to the parameter `BotClient`, then build (For debugging, windows or Linux) and/or publish (for click-once for windows) the project.

This repository can also be run on Linux - Simply copy the build files to the Linux machine, and install Mono:

`sudo apt-get mono-complete`

Browse to the directory you copied the build files to, and enter:

`sudo mono GifPolice.exe`


##commands
/status - Gets the options set for the bot.
/setgifs - Set the gifs per minute
/setminutes - Sets the minute threshhold
/setrestrictdays - Sets the number of days a user is restricted for if strike limit has been hit
/setstrikes - Sets the number of strikes allowed before media ban
/strikes - See how many strikes you have