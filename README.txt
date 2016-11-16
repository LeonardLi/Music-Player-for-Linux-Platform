<snippet>
  <content><![CDATA[
# ${1:Raspberry Pi_Music Player}

## Discription
I used the raspberry pi as a music player. It could download music from the internet and play automatically.
I found some URL links that ended with “.mp3” and stored the music name and URL into a database. When I started to play music, it connected to database to fetch the URL used for mgp123 to decode and download music. I imported control keys of mpg123 which enabled terminal control. 
The command is:
```shell
mpg123 -C url
```
]]></content>
  <tabTrigger>readme</tabTrigger>
</snippet>
