The Most Powerfull Userbot ☣️
Codacy Badge

Python 3.6

GitHub repo size

Contact Me

†hê Hêllẞø†
This is a userbot made for telegram. I made this userbot with help of all other userbots available in telegram. All credits goes to its Respective Owners....

This is the one and only official HellBot Userbot made by @Kraken_The_BadASS Also join support channel and group :- https://t.me/HellBot_Official Enjoy Your Bot!!💝 HellBot logo

The owner would not be responsible for any kind of bans due to the bot...
FORK AT YOUR OWN RISK
Credits
• JaaduBot
One and only. Others with some misfuntioning brain stay out from this SUPER POWERFULL BOT😏
Official Support
 

Video Tutorial
 

⚡ Set-Up ⚡
✨ The Easy Way ✨
Deploy

⚔️ The Normal Way ⚔️
Simply clone the repository and run the main file:

git clone https://github.com/HellBoy-OP/HellBot
cd HellBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
An example local_config.py file could be:

Not All of the variables are mandatory

The Userbot should work by setting only the first two variables

from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
UniBorg Configuration
The UniBorg Config is situated in userbot/uniborgConfig.py.

Heroku Configuration Simply just leave the Config as it is.

Local Configuration Fortunately there are no Mandatory vars for the UniBorg Support Config.

Mandatory Vars
Only two of the environment variables are mandatory.
This is because of telethon.errors.rpc_error_list.ApiIdPublishedFloodError
APP_ID: You can get this value from https://my.telegram.org
API_HASH: You can get this value from https://my.telegram.org
The userbot will not work without setting the mandatory vars.
