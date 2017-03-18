# Marv is an incredibly easy to use music bot for [Discord](http://discordapp.com)

Some stuff about the support server here

## Commands

**Note:** Most command parts can be shortened to one letter. For example, `-play` monstercat can be shortened to `-p` monstercat

#### Adding to the queue

* `-play [link/search term]` Adds the song or playlist to the queue. If the input is a search term, it will automatically choose the first result
* `-play choose [search term]` Prompts you to choose which search results you want to queue if you input a search
* `-play shuffle [playlist]` Automatically shuffles the playlist before adding it to the queue if you input a playlist
* `-play random` Adds a random song to the queue
* `-play` If the command call message has audio attachments, it will add them to the queue

**Note:** Every command above can have the word next added before the input. This will queue the song in the position after the current track. For example, `-play choose next [link/search term]`

#### Viewing the queue

* `-queue` Shows the queue

#### Controlling the queue

* `-next/skip` Skips to the next song
* `-back` Skips to the previous song
* `-remove [song index/title]` Removes the track at the specified index/title
* `-jump [song index/title]` Jumps to the track at the specified index/title
* `-clear` Clears the queue
* `-shuffle` Randomizes all the songs after the current one
* `-move [song index/title], [index]` Moves the specified song to the specified index

#### Controlling the bot

* `-join` Makes the bot join your voice channel
* `-leave` Makes the bot leave your voice channel
* `-stop` Makes the bot stop

#### Controlling the song

* `-pause` Pauses the song
* `-resume` Resumes the song

#### Looping

* `-loop` Cycles between the three loop settings
* `-loop track` Loops the current track
* `-loop queue` Loops the entire queue
