# discord-music-bot

Forked version of ```https://github.com/mindaugaskasp/discord-music-bot.git```, focused on bugfixes and reducing unnecessary code surface *(e.g., extraneous Docker configuration to debug while the core code itself doesn't work properly at all)*.

## How to Use

1. Install Node.

2. Install ffmpeg and make sure paths are configured so that this tool can find it.

2. Set up configuration data in `configs/app.json`.

3. Run `npm install` to install Node project dependencies.

4. Start the server with either ```node index```, ```npm run prod``` or `npm run debug`.

5. Invite the bot to your Discord server by visiting the following link while logged into the Discord account that owns that server, replacing ```<ClientID>``` with the bot's Client ID: 
```
https://discordapp.com/oauth2/authorize?client_id=<ClientID>&permissions=0&scope=bot
```

6. Type ```.help``` in your Discord server to see a full list of commands.