![logo](https://cdn.discordapp.com/attachments/789489821986062366/801144433650696252/ff883accb2fb91323c3e3f722eef3136f5b4765d_hq.png)

# 🤖 AwesomeBot (Discord Music Bot)
> AwesomeBot is an open-source Discord Music Bot built with node.js & uses Command Handler from [repl.it](https://repl.it)

## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Optional)** Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v12.0.0 or newer

## ⚙️ Configuration

Edit the values of `config.json`:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "STAY_TIME": 30
}
```

## 📝 Features & Commands

> Note: The default prefix is '>'

* 🎶 Play music from YouTube via url

`/play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎 Play music from YouTube via search query

`/play under the bridge red hot chili peppers`

* 🎶 Play music from Soundcloud via url

`/play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎 Search and select music to play

`/search Pearl Jam`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

* 📃 Play youtube playlists via url

`/playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Play youtube playlists via search query

`/playlist linkin park meteora`
* Now Playing (>np)
* Queue system (>queue, >q)
* Loop / Repeat (>loop)
* Shuffle (>shuffle)
* Volume control (>volume, >v)
* Lyrics (>lyrics, >ly)
* Pause (>pause)
* Resume (>resume, >r)
* Skip (>skip, >s)
* Skip to song # in queue (/skipto, /st)
* Remove song # from queue (/remove, /rm)
* Toggle pruning of bot messages (/pruning)
* Help (/help, /h)
* Command Handler from [discordjs.guide](https://discordjs.guide/)

# Credits

Just me, RocketSpot :/
