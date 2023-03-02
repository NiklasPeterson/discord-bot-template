# discord-bot-template
A simple template to easily get you started with creating your own bot for Discord!
---

## Features and technologies used

- [Slash commands](https://discord.com/developers/docs/interactions/application-commands)
- [Interactive buttons](https://discord.com/developers/docs/interactions/message-components#buttons)
- [Discord.JS v14](https://discord.js.org/#/)
- Supports both local and gobal commands

---
## Deploy using Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/zMVF-L?referralCode=2v8Zry)

---

## Project structure

```
├── commands
│   ├── beep-local.js
│   ├── ping-global.js
│   ├── server-global.js
│   ├── user-global.js
├── events
│   ├── interactionCreate.js
│   ├── ready.js
├── .env.sample
|–– .gitignore
|–– .eslintrc.json
|–– config.json.sample
├── deploy-commands-global.js
├── deploy-commands.js
├── index.js
├── package.json
├── README.md
```
