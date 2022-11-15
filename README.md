# ESPHome-SpotifyNowPlaying

## Idea
Make a Music Jukebox which integrates with Home Assistant using ESPHome and off-the0shelf components. This is intended as a Christmas present for my partner who stated she had never received a mixtape when she was younger.


## Parts used

- LilyGO TTGO T-Display ESP32

## Coding

### ESPHome
The display is made with "pages" within the display component, I built a page to display the song, artist and album name. Additional pages were creating as 
It then displays these pages in a sequence with a ten second delay before showing the next page.
I made it so that the sequence displays the time then a sensor then back to the time again in a loop, so that the time is always ten seconds at max before being displayed again.

The display can be used to change the page display with either a button press or a interval carousel. Code is commented for interval carousel.

### Home Assistant
Sensors are made to export the information using the Template option to conform to the latest best practice. My Home Assistant is setup with seperate files for each aspect to give granularity, and the file structure reflects this, however can be easily adapted.

## Construction
The TFT display on the Lillygo board is very clear and bright with easy visability. Some fonts like Arial can be problematice due to typesetting issues.

## Pictures / Video




