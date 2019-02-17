# discord-music-bot

Forked version of ```https://github.com/mindaugaskasp/discord-music-bot.git```, focused on bugfixes.

## How to Use

1. Install Node.
2. Install ffmpeg and make sure paths are configured so that this tool can find it.
2. Set up configuration data in `configs/app.json`.
3. Run `npm install` to install project dependencies.
4. Run `npm run prod` or `npm run debug` .
5. Invite bot to your discord server via `https://discordapp.com/oauth2/authorize?client_id=<ClientID>&permissions=0&scope=bot`, replacing ```<ClientID>``` with the bot's Client ID.
6. Use command `<prefix>help` in your discord guild text channel to view available commands