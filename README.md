# Discord GPT Bot

A discord bot that sends OpenAI generated messages to a channel whenever a specific user uses the /generate-prompt command


## Table Of Contents

- [Support The Project](#support)
- [Installation](#installation)

- [Usage Example](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

Use the package manager [npm](https://npmjs.org) to install the dependencies. Then copy the example .env file and fill in with appropriate values.

```bash
 git clone https://github.com/mastashake08/discord-gpt-bot.git
 npm install
 cp .env.example .env
 #set values for OpenAI and DISCORD APIs in .env
 DISCORD_TOKEN=
 DISCORD_CHANNEL_ID=
 DISCORD_CLIENT_ID=
 DISCORD_GUILD_ID=
 OPENAI_API_KEY=



```

## Usage

```bash
node index.js
```
### Docker

```bash
# On linux/amd64 architechture
docker run --platform linux/amd64 --env-file=<PATH TO .ENV> -d --name=<NAME> mastashake08/discord-gpt-bot

docker run  --env-file=<PATH TO .ENV> -d --name=<NAME> mastashake08/discord-gpt-bot:latest
```
