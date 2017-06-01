# parklezbot
Telegram bot made with PyTelegramBotAPI

**Requires Python 3 and [PyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) to run!**
# Features:
 - List handling.
 - .txt database system.
 - Lots of common functions to make life easier.
 - Tool to convert .wav to OPUS .ogg.
 - Easy drag and drop to enable/disable plugins.
 
# Plugins:
 - Enabled by default:
	- common_functions.py (no commands)
	- listener_module.py (listener mechanism)
	- reply_start.py (/start)
	
 - Disabled:
	- anime_module.py (/animes, /edit)
	- linux_shell module.py (/shell)
	- python_module.py (/python, a python interactive console)
	- reply_files ids.py (no commands, replies file's id's)
	- reply_rate.py (/rate)
	- reply_user id.py (/me)
	- sounds_module.py (/sons, /som, /delsom)

# SETUP:
 - Write your token and set yourself as admin at 'config.py'
 - Run 'bot_main.py'
 
 - Drag and drop a plugin from the '/disabled' folder to the '/plugins' folder to activate a function. 

# Future:
 - More and better functions for groups.
 - *Update to telegram 2.0 bot base.*
 
# Other
All extras included inside '/tools' are not supported anymore, they're just pieces of code I used somewhere in the project timeline.

You can delete any .txt or folder at any moment, since common_functions.py creates them when necessary! :)

# Screenshots:

![ScreenShot](http://i.imgur.com/P57Haar.png)
![ScreenShot](http://i.imgur.com/OM22K12.png)
![ScreenShot](http://i.imgur.com/FGEisXK.png)
![ScreenShot](http://i.imgur.com/VUoVvIn.png)
![ScreenShot](http://i.imgur.com/WxVnWzH.png)
