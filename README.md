
<center><img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Lavamusic&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=gradient" /></center>


[![Version][version-shield]](version-url)
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

[![Run on Repl.it](https://repl.it/badge/github/brblacky/lavamusic)](https://repl.it/github/brblacky/lavamusic)
[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/import/github/brblacky/lavamusic)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/brblacky/lavamusic">
    <img src="https://media.discordapp.net/attachments/876035356460462090/887728792926290091/20210820_124325.png" alt="Pbot-plus" width="200" height="200">
  </a>

  <h1 align="center">lavamusic</h1>

  <p align="center">Lavamusic is a Discord music bot that uses Discord.js, Shoukaku, Prisma Client (ORM) database (MongoDB), and TypeScript.
    <br />
    <br />
    <a href="https://discord.com/api/oauth2/authorize?client_id=875635121770889257&permissions=8&scope=bot%20applications.commands">Invite Lavamusic</a>
    ·
    <a href="https://github.com/brblacky/lavamusic/issues">Report Bug</a>
    ·
    <a href="https://github.com/brblacky/lavamusic/issues">Request Feature</a>
  </p>
</p>

## 🎭 Features

- Build with typescript and discord.js v14
- Music
- Prefix
- Search Engine
- Hybrid Command Handler(Slash and Normal Commands)
- Customizable
- Easy to use
- 24/7 Music

## 🎶 Support Sources

- YouTube
- SoundCloud
- Twitch
- Bandcamp
- Vimeo
- Https (Radio)
- Spotify([Required Plugin](https://github.com/TopiSenpai/LavaSrc))
- Deezer([Required Plugin](https://github.com/TopiSenpai/LavaSrc))
- Apple Music([Required Plugin](https://github.com/TopiSenpai/LavaSrc))
- Yandex Music([Required Plugin](https://github.com/TopiSenpai/LavaSrc))
- Mixcloud([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- Ocremix([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- Clyp([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- Reddit([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- Getyarn([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- TikTok([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- P**nHub([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))
- Soundgasm([Required Plugin](https://github.com/DuncteBot/skybot-lavalink-plugin))

### **Need Help with plugins?** Join our [Discord Server](https://discord.gg/ns8CTk9J3e) and ask in the `#support` channel

## 📚 Commands

<details><summary>Click to expand</summary>

| Name | Description |
|------|-------------|
| prefix | Shows the bot's prefix |
|      | Options     |
|      |-------------|
|      | prefix: The prefix you want to set |
| about | Shows information about the bot |
|      | None        |
| help | Shows the help menu |
|      | Options     |
|      |-------------|
|      | command: The command you want to get info on |
| info | Ingormation about the bot |
|      | None        |
| invite | Sends the bot's invite link |
|      | None        |
| ping | Shows the bot's ping |
|      | None        |
| clearqueue | Clears the queue |
|      | None        |
| join | Joins the voice channel |
|      | None        |
| leave | Leaves the voice channel |
|      | None        |
| nowplaying | Shows the currently playing song |
|      | None        |
| play | Plays a song from YouTube or Spotify |
|      | Options     |
|      |-------------|
|      | song: The song you want to play |
| pause | Pauses the current song |
|      | None        |
| queue | Shows the current queue |
|      | None        |
| remove | Removes a song from the queue |
|      | Options     |
|      |-------------|
|      | song: The song number |
| resume | Resumes the current song |
|      | None        |
| seek | Seeks to a certain time in the song |
|      | None        |
| shuffle | Shuffles the queue |
|      | None        |
| skip | Skips the current song |
|      | None        |
| skipto | Skips to a specific song in the queue |
|      | None        |
| stop | Stops the music and clears the queue |
|      | None        |
| volume | Sets the volume of the player |
|      | Options     |
|      |-------------|
|      | number: The volume you want to set |

</details>

## 🔧 Requirements

Before starting with the installation, you need to have the following:

- ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) [v18.0.0 or higher](https://nodejs.org/en/download/)
- ![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white) [v7.0.0 or higher](https://www.npmjs.com/get-npm)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) [v4.4.0 or higher](https://www.mongodb.com/try/download/community)
- ![Lavalink](https://img.shields.io/badge/Lavalink-7289DA?style=for-the-badge&logo=discord&logoColor=white) [v3.3.2.3 or higher](https://github.com/freyacodes/Lavalink)


## 🚀 Installation from source

1. Clone the Lavamusic repository:
  
  ```bash
  git clone  https://github.com/brblacky/lavamusic.git
```

2. change the directory to Lavamusic

```bash
cd lavamusic
```

3. Install the required packages:

```bash
npm install
```

4. Set up your environment variables:

Create a `.env` file in the root directory of your project with the following variables:
  
  ```bash
TOKEN="." # Your bot token
PREFIX="!" # Your prefix
OWNER_IDS="859640640640640640, 859640640640640640" # Your ID
CLIENT_ID="960072976412340254" # Your bot client ID
GUILD_ID="859640640640640640" # Your server ID (if you want to use it for a single server)
PRODUCTION="true" # "true" for production
DATABASE_URL="mongodb+srv://Blacky:xxxxxxxxxxxx" # Your MongoDB URL
LAVALINK_URL="localhost:2333" # Your Lavalink URL
LAVALINK_AUTH="youshallnotpass" # Your Lavalink password
LAVALINK_NAME="Blacky" # Your Lavalink name
LAVALINK_SECURE="false" # "true" for secure Lavalink
```

5. Generate the Prisma client:

**If you using replit than read this:**

go to **[prisma/schema.prisma](https://github.com/brblacky/lavamusic/blob/main/prisma/schema.prisma)** and add engine type like this

```bash
generator client {
  provider = "prisma-client-js"
  engineType = "binary"
}
```

 and then run this command
  
  ```bash
  npx prisma generate
```

6. Run the bot:
  
  ```bash
  npm run start or npm start
```

7. Invite the bot to your server:

Generate an invite link for your bot and invite it to your server using the Discord Developer Portal.

## 🚀 Installation using docker-compose

This section assumes you have docker and docker-compose installed and is running correctly.

Download the [Docker-Compose file](https://raw.githubusercontent.com/brblacky/lavamusic/main/docker-compose.yml) in a seperate folder like lavamusic.

Edit the Docker-Compose file and make sure to edit the following variables:

```yaml
TOKEN="." # Your bot token
PREFIX="!" # Your prefix
OWNER_IDS="859640640640640640, 859640640640640640" # Your ID
CLIENT_ID="960072976412340254" # Your bot client ID
GUILD_ID="859640640640640640" # Your server ID (if you want to use it for a single server)
PRODUCTION="true" # "true" for production

```

For more information how to fill all the varialabes go to this page.
You do not need to edit anything like the LAVA_LINK_URL, LAVA_LINK_AUTH, LAVA_LINK_NAME, LAVA_LINK_SECURE, DATABASE_URL, and the ports.
Unless you know what your doing.

After saving your changes you can open a terminal and go to the same location as the docker-compose file. Then type the following:

```bash
docker-compose up -d
```

The above command will start all your services and your bot should be up and running!

To update, you only have to type the following:

```bash
docker-compose up --force-recreate --build -d
image prune -f
```

You can automate this by using [Watchtower](https://github.com/containrrr/watchtower). The following should be sufficient:

```bash
docker run --detach \
    --name watchtower \
    --volume /var/run/docker.sock:/var/run/docker.sock \
    --restart on-failure \
    containrrr/watchtower --cleanup
```

Do note that the bot will restart itself to update to the latest!

## 🔗 Useful Links

- [Discord.js](https://discord.js.org/)
- [Shoukaku](https://github.com/Deivu/Shoukaku)
- [Prisma](https://www.prisma.io/)
- [MongoDB](https://www.mongodb.com/)
- [Lavalink](https://github.com/freyacodes/Lavalink)

## 📝 Tutorial

A Tutorial has been uploaded on YouTube, Watch it by clicking [here](https://youtu.be/x5lQD2rguz0)

## 📜 Contributing

Thank you for your interest in contributing to Lavamusic! Here are some guidelines to follow when contributing:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Write clean and concise code that follows the established coding style.
3. Create detailed and thorough documentation for any new features or changes.
4. Write and run tests for your code.
5. Submit a pull request with your changes.

Your contribution will be reviewed by the project maintainers, and any necessary feedback or changes will be discussed with you. We appreciate your help in making Lavamusic better!

## 🔐 License

Distributed under the Apache-2.0 license License. See [`LICENSE`](https://github.com/brblacky/lavamusic/blob/master/LICENSE) for more information.

[version-shield]: https://img.shields.io/github/package-json/v/brblacky/lavamusic?style=for-the-badge
[contributors-shield]: https://img.shields.io/github/contributors/brblacky/lavamusic.svg?style=for-the-badge
[contributors-url]: https://github.com/brblacky/lavamusic/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/brblacky/lavamusic.svg?style=for-the-badge
[forks-url]: https://github.com/brblacky/lavamusic/network/members
[stars-shield]: https://img.shields.io/github/stars/brblacky/lavamusic.svg?style=for-the-badge
[stars-url]: https://github.com/brblacky/lavamusic/stargazers
[issues-shield]: https://img.shields.io/github/issues/brblacky/lavamusic.svg?style=for-the-badge
[issues-url]: https://github.com/brblacky/lavamusic/issues
[license-shield]: https://img.shields.io/github/license/brblacky/lavamusic.svg?style=for-the-badge
[license-url]: https://github.com/brblacky/lavamusic/blob/master/LICENSE
