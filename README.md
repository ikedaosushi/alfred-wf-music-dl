# alfred-wf-music-dl
A Alfred workflow that download Spotify, Youtube, SoundCloud, Bandcamp Musics

# Install
[music-dl.alfredworkflow](https://raw.githubusercontent.com/ikedaosushi/alfred-wf-music-dl/master/music-dl.alfredworkflow)

# Required
This Workflow only helps to call below commands. You have to install each commands by yourself.

- [ytdl-org/youtube-dl: Command-line program to download videos from YouTube.com and other video sites](https://github.com/ytdl-org/youtube-dl)
- [Miserlou/SoundScrape: SoundCloud (and Bandcamp and Mixcloud) downloader in Python.](https://github.com/Miserlou/SoundScrape)
- [ritiek/spotify-downloader: Download Spotify playlists with albumart and meta-tags](https://github.com/ritiek/spotify-downloader)

# Note
Each commands.

```sh
# SoundCloud
soundscrape $URL
# Bandcamp
soundscrape -b $URL
# Spotify
spotdl --song $URL -f .
# Youtube
youtube-dl -x --audio-format mp3 $URL
```