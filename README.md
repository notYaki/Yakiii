<img width="64" height="64" align="left" style="float: left; margin: 10px 10px 0 0;" alt="Icon" src="https://imgur.com/dRSYp1f.png">

# Sniper

> An easy to run simple bot that lets you snipe messages in your Discord server.

## Setup

Node.js 16.6.0 or newer is required.

1. Run:

```bash
$ git clone https://github.com/notYaki/Yakiii.git
$ cd .Yakiii
```

2. Add token:

add .env file and tpye TOKEN=your token here without the

3. Run:

```bash
$ npm i
$ npm run register [guild id]
$ npm run bot
```

Note:
Without specifying [guild id], snipe command will available on all of your app's guilds. It will fan out slowly across all guilds, and will be guaranteed to be updated in an hour (due to Discord's cache).

With [guild id] it will be available only within the guild specified. It will update instantly.

!enjoy
