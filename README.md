# Telegram Voice-Chat Bot [ Pytgcalls ]

Telegram Voice-Chat Bot To Play Music With Pytgcalls From Various Sources In Your Group.

<img src="https://hamker.me/wl9twld.png" width="530" height="300">


## Support

Only For Heroku:
[Join Group for Any Help](https://t.me/SWXChatt)

For other OS Check the:
[Main Repository](https://github.com/thehamkercat/Telegram_VC_Bot)



## Requirements

- Telegram API_ID and API_HASH
- Userbot Needs To Be Admin In The Chat
- [Heroku Client](https://devcenter.heroku.com/articles/heroku-cli#download-and-install): Installed On Your System


## Heroku

#### Generate String session [IMPORTANT]

Go to this bot [@PyrogramStringBot](https://t.me/PyrogramStringBot) and enter your API ID AND API HASH, then Mobile no. and you will get your String Session.


Fork and Star this repository and copy `sample_config.py` and rename it to `config.py`.

## Deploying

#### Note - Change appname to any other name

    heroku login

    heroku create appname
 
    heroku buildpacks:add https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git -a appname

    heroku buildpacks:add https://github.com/heroku/heroku-buildpack-python.git -a appname

    git init

    heroku git:remote -a appname

    git add .

    git commit -am "Your commit message"

    git push heroku master

    heroku ps:scale worker=1


## Video Tutorial
[![video tutorial](https://raw.githubusercontent.com/Lucifer7535/Telegram_VC_Bot/master/thumbnail.jpg)](https://www.youtube.com/watch?v=qW9DZWslRkc)

## Commands
Send [commands](https://github.com/Lucifer7535/Telegram_VC_Bot/blob/master/README.md#commands) to bot to 
play music.

Command | Description
:--- | :---
/help | Show Help Message.
/skip | Skip Any Playing Music.
/play youtube/saavn/deezer [SONG_NAME] | To Play A Song.
/telegram | Play A Song Directly From Telegram File.
/queue | Check Queue Status.
/joinvc | Join Voice Chat.
/rejoinvc | Rejoin Voice Chat.
/leavevc | Leave Voice Chat.
/volume [1-200] | Adjust Volume.
/pause | Pause Music.
/resume | Resume Music.
/update | Update & Restart.

## Note

1. If you want any help you can ask [here](https://t.me/yt_DarkHackerX_chat)

## Credits

1. @MarshalX [For TgCalls]
2. Everyone who contributed to the project.
