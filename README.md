# ytmenu
A simple script to play music from youtube with mpd and dmenu. It can search for songs, auto-generated mixes and live streams, then play them through mpd. It also keeps a history of the songs you played.

### Requirements
 - python 3.x
 - [pafy](https://pypi.org/project/pafy/)
 - [appdirs](https://pypi.org/project/appdirs/)
 - [mpd](https://www.musicpd.org/)
 - [dmenu](https://tools.suckless.org/dmenu/)

### Usage
 1. Clone the repo
 2. Get a YouTube Data API key [here](https://developers.google.com/youtube/v3/getting-started#before-you-start) (follow until step 3)
 3. Paste your API key into the `ytmenu` script (`API_KEY = '{YOUR_API_KEY_HERE}'`)
 5. Make the script executable `chmod +x ./ytmenu`
 6. (Optional) Add the script top your path
 7. (Optional) Setup a keyboard shortcut with sxhkd or your window manager

### Known issues
 - Sometimes livestreams can't be played from history, even if they're still streaming. Perhaps they change their IDs?
