# Getting Started

Here's a video tutorial:

https://www.youtube.com/watch?v=p-rZapbQips

# Save files

Songs are saved as JSON documents that contain the transform and metadata about all placed items, within the `items` field. Each placed Item has an ID that maps to an instrument definition.

The `instrumentDefinitions` field contains the information about each item, which has an ID and a path to the sound file it plays, as well as the color of the paddle.

There's a `name` and `author` field as well.

The idea is to make a save format that's easily shareable via the Web. I might make a website post-launch for sharing songs.

# Custom instruments

To make a custom instrument:

1. Create or find an MP3 or WAV file. There is no length limit. But you might not want to import a podcast episode, since the audio will be loaded into memory on each strike.
2. Rename the file to what the name of the instrument should be, i.e., `Piano.mp3`.
3. Place the sound file in your custom sounds directory, which is `C:\Users\coold\AppData\LocalLow\Valve\SteamVR\saves`.

To make a custom intrument with multiple notes:

1. Create or find a number of MP3/WAV files for each note you want.
2. Rename them with the following convention: `{instrumentName}%{note}`. So, for example `Piano%C3.mp3`.
3. Add them to the custom notes folder, which is in `C:\Users\coold\AppData\LocalLow\Valve\SteamVR\saves`.
