## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Optional)** Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v12.0.0 or newer

## 🚀 Getting Started

```
git clone https://github.com/Endternvl/pdjsourcecode
cd pdjsourcecode
npm install
```

After installation finishes you can use `node index.js` to start the bot.

## ⚙️ Configuration! this is important

Copy or Rename `config.json.example` to `config.json` and fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "pd!",
  "PRUNING": false
}
```

## 📝 Features & Commands

> Note: The default prefix is 'pd!'

* 🎶 Play music from YouTube via url

`pd!play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎 Play music from YouTube via search query

`pd!play under the bridge red hot chili peppers`

* 🎶 Play music from Soundcloud via url

`pd!play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎 Search and select music to play

`pd!search Pearl Jam`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

* 📃 Play youtube playlists via url

`pd!playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Play youtube playlists via search query

`pd!playlist linkin park meteora`
* Now Playing (/np)
* Queue system (/queue, /q)
* Loop / Repeat (/loop)
* Shuffle (/shuffle)
* Volume control (/volume, /v)
* Lyrics (/lyrics, /ly)
* Pause (/pause)
* Resume (/resume, /r)
* Skip (/skip, /s)
* Skip to song # in queue (/skipto, /st)
* Remove song # from queue (/remove, /rm)
* Toggle pruning of bot messages (/pruning)
* Help (/help, /h)
* Command Handler from [discordjs.guide](https://discordjs.guide/)
* Media Controls via Reactions

## 📝 Credits

[Prodigous](https://dsc.gg/prodigous), Our Community + editor!