# ual-radio
Extensión de la radio por Internet de la UAL sobre servidores Icecast

```
vlc http://150.214.150.112:8000/stream --sout '#transcode{vcodec=none,acodec=vorb,ab=128,channels=2,samplerate=44100}:std{access=shout,mux=ogg,dst=source:1qaz@150.214.150.68:4551/multimedia.ogg}'
```
