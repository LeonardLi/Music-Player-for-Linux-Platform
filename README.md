# Raspberry Pi_Music Player
## Discription
I used the raspberry pi as a music player. It could download music from the internet and play automatically.
I found some URL links that ended with “.mp3” and stored the music name and URL into a database. When I started to play music, it connected to database to fetch the URL used for mgp123 to decode and download music. I imported control keys of mpg123 which enabled terminal control. Press 'h' for listing keys and press “q” for shifting songs. I set two music playing mode: play music in order and play randomly. When choosing playing all music in order, press “q” could change to next song. When playing random, press “q” might shift to any songs in list. 
The command is:
```shell
mpg123 -C url
```
