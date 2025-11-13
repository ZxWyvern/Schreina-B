##  Discord Bot: Advanced Music Bot
Schreina (B) is a Discord bot built purely for fun and as a means for me to explore and develop skills in Discord development.



(Yes, the "B" in the bot's name stands for Bot.)



LANGUAGE: This bot primarily uses Bahasa Indonesia (Indonesian Language) for its responses and interactions.
This is an **Advanced Music Bot** built to provide a rich music experience with features like **audio filters, custom playlists, and full queue control.**

**IMPORTANT:** The bot is designed for high-quality audio playback and comprehensive music management.

---

##  Command Type

This bot primarily uses **Slash Commands** for all major functions.

All commands must be prefixed with: **`/`**


---

##  Commands List

Here is the complete list of commands available for the bot:

###  Music Commands

| Command | Description |
| :--- | :--- |
| `/play <query>` | Plays music from YouTube/SoundCloud/Spotify or adds it to the queue. |
| `/skip` | Skips the currently playing track. |
| `/pause` | Pauses playback. |
| `/resume` | Resumes playback. |
| `/stop` | Stops playback and disconnects the bot. |
| `/leave` | Forces the bot to leave the voice channel. |
| `/join` | Invites the bot to your current voice channel. |
| `/queue [page]` | Views the list of songs in the queue. |
| `/nowplaying` | Displays details of the currently playing song. |
| `/clearqueue` | Clears all songs from the queue. |
| `/shuffle` | Shuffles the order of songs in the queue. |
| `/remove <index>` | Removes a song from the queue by its index number. |
| `/skipto <index>` | Skips the queue up to the song at the specified index. |
| `/previous` | Plays the previously played track. |
| `/loop [mode]` | Toggles repeat mode (`song`/`queue`/`off`). |
| `/volume [level]` | Sets the playback volume (0-200). |
| `/seek <time_str>` | Seeks to a specific timestamp (e.g., `1:30` or `90s`). |
| `/autoplay` | Toggles the *autoplay* feature. |
| `/lyrics [song]` | Gets the lyrics for the current or specified song. |
| `/musicpanel` | Creates an interactive music control panel with buttons. |

###  Filter Commands

| Command | Description |
| :--- | :--- |
| `/bassboost` | Toggles the bassboost filter. |
| `/8d` | Toggles the 8D audio filter. |
| `/nightcore` | Toggles the nightcore filter. |
| `/bass` | Toggles the general bass filter. |
| `/chipmunk` | Toggles the chipmunk effect. |
| `/karaoke` | Toggles the karaoke filter. |
| `/pop` | Toggles the pop filter. |
| `/radio` | Toggles the radio filter. |
| `/slowmo` | Toggles the slow motion filter. |
| `/soft` | Toggles the soft filter. |
| `/speed` | Toggles the speed filter. |
| `/treblebass` | Toggles the treblebass filter. |
| `/clearfilter` | Clears all active audio filters. |

###  Playlist Commands

| Command | Description |
| :--- | :--- |
| `/pl-create <name>` | Creates a new server playlist. |
| `/pl-delete <name>` | Deletes a playlist (requires ownership/admin). |
| `/pl-list` | Lists all server playlists. |
| `/pl-info <name>` | Displays information and songs in a playlist. |
| `/pl-play <name>` | Adds all songs from a playlist to the queue. |
| `/pl-shuffle <name>` | Shuffles and plays all songs from a playlist. |
| `/pl-save <name>` | Saves the currently playing song to a playlist. |
| `/pl-saveq <name>` | Saves the entire current queue to a playlist. |
| `/pl-remove <name> <index>` | Removes a song from a playlist by index. |
| `/pl-dupes <name>` | Removes duplicate songs from a playlist. |

###  Settings Commands (Admin Only)

| Command | Description |
| :--- | :--- |
| `/setprefix <prefix>` | Sets a custom legacy prefix (max 5 chars). |
| `/adddj <role>` | Sets a role that can use DJ commands. |
| `/removedj` | Removes the set DJ role. |
| `/toggledj` | Toggles DJ mode (restricts music commands to DJs/Admins). |
| `/247` | Toggles 24/7 mode (prevents the bot from auto-disconnecting). |

###  Info Commands

| Command | Description |
| :--- | :--- |
| `/help [category]` | Displays this help menu (`music`, `filters`, `playlist`, `settings`, `info`). |
| `/ping` | Checks the bot's latency (ping). |
| `/uptime` | Displays the bot's current uptime. |
| `/about` | Displays general information about the bot. |
| `/invite` | Get the bot's invite link. |
| `/support` | Displays the support server information. |

***
**Thank you for using the Advanced Music Bot!**
