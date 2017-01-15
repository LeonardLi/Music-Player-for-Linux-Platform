# Music Player based on Linux Platform
###Introduction
Build the Raspberry Pi as a music player. It could download music from the internet and play automatically.  
###Usage
- Install mpg123:
```
$ sudo apt-get install python-setuptools mpg123 -y
```
- Import **sqlite3** module to provide a lightweight disk-based database. 

- Import control keys of mpg123 which enables terminal control
```
$ mpg123 -C url
```

![GitHub][github]
[github]:http://coderxiaoyu.com/alarmclock/img/music2.png  

###Design
- Find some URL links that end with “.mp3” and store the name, URL pair into a database. 

- When start music player, it connect to database to fetch the URL used for mgp123 to decode and download music.
 
- Import control keys of mpg123 which enabled terminal control. Press 'h' for listing keys and press “q” for shifting songs.

-  Two music playing mode: play music in order and play randomly. When choosing playing all music in order, press “q” could change to next song. When playing random, press “q” might shift to any songs in list. 

