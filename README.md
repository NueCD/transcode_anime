# transcode_anime
Script that tries to find japanese audio and english subtitles in video files.
Picks the first available japanese audio track and the last english subtitles track.
Picking the first audio track should avoid if commentary track is present.

Made to be used with readymedia-transcode. https://bitbucket.org/stativ/readymedia-transcode/src/transcode/

## Twitch support added
If you try play a video in a directiry named "twitch" it will try to open the Twitch stream using streamlink.
Requires that streamlink is installed.
Example dir: videos/twitch/esl_sc2.mp4 < will play the esl_sc2 channel on Twitch.
