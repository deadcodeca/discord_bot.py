# DiscordBot
A simple discord bot that helps you get started within discord.py<br>

## Requirements
- Python 3.6+ - https://www.python.org/downloads/
- git - https://git-scm.com/download/

## Optional tools
- PM2 - NodeJS Module (Keeps the bot alive)
  - Requires NodeJS - https://nodejs.org/en/download/

## How to setup
```
[Optional]
If you use Windows, I would recommend using chocolatey (https://chocolatey.org/install) to install
ffmpeg, python and git, as it's both easier and promising to work.

Chocolatey command usage:
choco install <package>

Replace <package> with what you want to install, also remember to use Command Prompt as Admin.
```

1. Make a bot [here](https://discordapp.com/developers/applications/me) and grab the token
![Image_Example1](https://i.alexflipnote.xyz/0c8788.png)

2. Rename the file **config.json.example** and fill in the required spots, such as token, prefix and game

3. To install what you need, do **pip install -r requirements.txt**<br>
(If that doesn't work, do **python -m pip install -r requirements.txt**)<br>
`Note to 3: Use pip install with Administrator/Sudo`

4. Start the bot by typing in CMD/Terminal **python index.py**

5. You're done, enjoy your bot!

# FAQ
Q: I don't see my bot on my server!!<br>
A: Invite it by using this URL: https://discordapp.com/oauth2/authorize?client_id=CLIENT_ID&scope=bot<br>
Remember to replace **CLIENT_ID** with your bot client ID

Q: There aren't that many commands here...<br>
A: Yes, I will only provide a few commands to get you started, maybe adding more later.
