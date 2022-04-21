# ytm-dl

This is a very simple script that allows downloading music from Youtube Music and automatically tagging the song its respective metadata (song title, artist name, and album). This script  works by fetching the song's metadata using [ytmusicapi](https://github.com/sigma67/ytmusicapi), downloading the actual song using [yt-dlp](https://github.com/yt-dlp/yt-dlp), and finally tagging the MP3 file using [eyeD3](https://github.com/nicfit/eyeD3/tree/master)

## Dependencies
- python3
- ytmusicapi
- yt-dlp
- eyeD3

## How-to-Install
No formal way to install it is provided. Simply copy it to your `/usr/bin`.

## How-to-Use
It only requires one parameter, the URL to he song:
```
./ytm-dl https://music.youtube.com/watch?v=gDQ9kyRs32A
```

