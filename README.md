# KEXPspotifier
IFFTT Applet code for converting KEXP's playlist stream into a Spotify playlist as a show archive

# Wait, what? What does this thing do?
1. KEXP publishes their playlist as track metadata to twitter [@kexplaylist](https://twitter.com/kexpplaylist)
2. If the published tweet is in a window of the [showtime](http://kexp.org/schedule) one is interested in, the IFTTT applet searches Spotify for that song, and if found, adds it to specified playlist.

## How to use
If you want streamed songs to be added to your personal playlist on Spotify, I've published a couple of my favorite shows as applets that you can turn on after you connect your IFTTT to Spotify:

[Wo'pop IFTTT applet](https://ifttt.com/applets/LXQRLwH2-kexp-wo-pop-spotify-playlist)

[El Sonido IFTTT applet](https://ifttt.com/applets/C3RWd6bz-kexp-el-sonido-spotify-playlist)

If you are just looking to follow one of these shows archives, you can simply follow the archives I have since Oct 2017, which have been build using these applets:

[Spotify KEXP-Wo'pop-Archive](https://open.spotify.com/user/kpsin/playlist/4UlSdhKvSnDSNpGgq1pI3d)

[Spotify KEXP-El Sonido-Archive](https://open.spotify.com/user/kpsin/playlist/7o0Q7iQyStrII8QooRbE2F)

## How do you get an applet for another KEXP show?
Unfortunately, I don't see a direct way of parameterizing these applet variables on IFTTT. There are 2 options:
1. Create your own IFTTT Applet! Take the included `applet-filter.js` and customize it for your desired show. You can even have it listen to completely independent twitter handle.
2. Create an issue in this repo requesting another show applet and I'll get to it at some point!


