# OoT input display
Ocarina of Time themed input display skin for NintendoSpy, based on the HUD you see in the game. Available both for Nintendo 64 and Gamecube controller.

![input](https://github.com/xwmtp/oot-input-display/blob/master/docs/gc-input-2.gif)

The gif shows the Gamecube version of the input display, but they are identical apart from L and Z buttons.

## Download
Please visit the [Releases](https://github.com/xwmtp/oot-input-display/releases) page to download the latest skin.

Unzip the downloaded folder containing the skin.xml and images and put it in the ```skins``` folder in the directory where ```NintendoSpy.exe``` is located.

## Color settings
Capture the window in OBS by adding a ```Window Capture``` source.

I recommend using the input display against a dark background in OBS, since the buttons slowly fade to black on the sides. You can add a ```Color key``` filter to the source to get rid of the black background. Make sure to play a bit with the settings. In particular, I recommend a **smoothness** of 45 and keeping the **similarity** at 1.

![settings](https://github.com/xwmtp/oot-input-display/blob/master/docs/obs-settings.png)

The skin shows button inputs by lighting the corresponding buttons up. If you would like the whole display to look a bit brighter/fainter, add a ```Color correction``` filter to the source to adjust the brightness or contrast, or see the next section.

## Brighter display
The downloaded skin will also have a brighter version of the background image. To use this one instead, open the ```skin.xml``` file in a text editor and put ```<background name="Basic" image="gc-skin-brighter.png"/>``` (GC skin example). This will make the contrast between buttons being pressed and unpressed smaller though.

## Requests
If people are interested in more skin variatons (red b button for the gamecube version of the game style or maybe items on the c-buttons), let me know by making an issue.

## Support
Skin made by me ([xwillmarktheplace](https://twitch.tv/xwillmarktheplace)). If you like the skin and would like to support me, please take a look at my channel:)
