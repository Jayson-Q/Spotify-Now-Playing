# ESPHome-SpotifyNowPlaying

## Idea
Make a Music Jukebox which integrates with Home Assistant using ESPHome and off-the-shelf components. This is intended as a Christmas present for my wife who stated she had never received a mixtape when she was younger.


## Parts used

- LilyGO TTGO T-Display ESP32

## Coding

### ESPHome
The display is made with "pages" within the display component, I built a page to display the song, artist and album name. Additional pages were creating as 
It then displays these pages in a sequence with which change on either a button press or on an interval delay before showing the next page.

### Home Assistant
Sensors are made to export the information using the Template option to conform to the latest best practice. My Home Assistant is setup with seperate files for each aspect to give granularity, and the file structure reflects this, however can be easily adapted.

## Construction
The TFT display on the Lillygo board is very clear and bright with easy visability. Some fonts like Arial can be problematic due to typesetting issues.

## Pictures / Video

![SpotifyNowPlaying](https://user-images.githubusercontent.com/68851601/201924545-12c760c9-283e-4254-9228-4fdef07ab300.png)


