# Telegram Voice-Chat Bot [ Pytgcalls ]

Telegram Voice-Chat Bot To Play Music With Pytgcalls From Various Sources In Your Group.

<img src="https://telegra.ph/file/d6eab48c445aa74303933.jpg" width="550" height="800">


# Support

1. [HARP Tech 🇱🇰](https://t.me/HARP_Tech)


## Requirements

- Telegram API_ID and API_HASH
- Python 3.7 or higher 
- Userbot Needs To Be Admin In The Chat
- Install **ffmpeg**

## Run

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ramachndrellko1992/SoundSugar)

Follow this if you are not running on heroku!

```sh
$ git clone https://github.com/OfficialBawwa/SoundSugar
$ cd Telegram_VC_Bot
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
$ cp sample_config.py config.py
```
Edit **config.py** with your own values.

```sh
$ python3 main.py
```

## Heroku

#### Generate String session [IMPORTANT]

Download this file [generate_string_session.py](https://raw.githubusercontent.com/thehamkercat/Telegram_VC_Bot/master/generate_string_session.py)


```sh
$ pip3 install pyrogram TgCrypto
$ python3 generate_string_session.py
```
You will get a session string, copy it, Then use heroku commands to push to heroku, DON'T ASK HEROKU SUPPORT IN GROUP FFS. 




Send [commads](https://github.com/ramachndrellko1992/SoundSugar/blob/master/README.md#commands) to bot to 
play music.


## Commands
Command | Description
:--- | :---
/start | To Start The bot.
/help | To Show This Message.
/ping | To Ping All Datacenters Of Telegram.
/skip | To Skip Any Playing Music.
/play youtube/saavn/deezer [song_name] | To Play A Song.
/telegram | To Play A Song Directly From Telegram File.
/queue | To Check Queue Status.
/joinvc | To Join Voice Chat.
/leavevc | To Leave Voice Chat.

## Note

1. If you want any help you can ask [here](https://t.me/HARP_Tech)

## Credits

This userbot Based from Hamkercat's TGVCBOT

1. @MarshalX [For TgCalls]
2. Hamkercat
3. Anjana_Ma
