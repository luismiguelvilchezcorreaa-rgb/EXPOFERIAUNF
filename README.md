# SING IT IN ENGLISH! — UNF Karaoke Player

A one-file HTML karaoke player for the UNF Language Center Expo Fair, **Friday, October 23, 2026, 4:00–7:00 p.m.**

## How to run

1. Open `index.html` with Chrome or Edge, or publish it using GitHub Pages.
2. Select one of the 10 songs in the left panel.
3. Choose **Original** or **Karaoke** mode.
4. Use the matching file selector to load an audio/video file from your laptop. Repeat for the other version if needed. The app **does not bundle or upload commercial songs**.
5. Click **Play**, choose **Project / Fullscreen**, and connect laptop video to the projector and its audio output to the JBL speaker (or use an appropriate wired audio connection).
6. Paste lyrics you have permission to display in **Lyrics & Timing**, optionally with `[mm:ss.xx]` timestamps, and click **Save lyrics**. Lyrics are stored in this browser's local storage when available, while media files must be reselected after a refresh. Karaoke MP4s with embedded lyric visuals display their own video automatically.
7. Configure the visitor timer (30–120 s), start it for each performer, and use **Celebrate!** for the congratulations screen.

## GitHub Pages

Create a GitHub repository, upload `index.html` to its root, then go to **Settings → Pages → Deploy from a branch → main / (root)**. Wait for the URL GitHub provides. No backend or paid hosting is required.

## Keyboard shortcuts

- Space: Play/Pause (except while editing)
- Left/Right arrows: previous/next lyrics line (except while editing)
- F: fullscreen projection view
- Escape: leave projection or celebration view

## Important details

- This website is a local-file player. It does not require internet once opened locally, and doesn't upload song files to GitHub. The file chooser does not permanently save media in the browser, so keep your original files on the event laptop.
- Compatible media formats depend on your browser. MP3 for audio and MP4 (H.264 video / AAC audio) are usually safe choices.
- The browser cannot change the microphone volume of a separate JBL microphone. Set that on the speaker and test for feedback.
- The countdown is independent of track playback. Auto-play on timer start is optional. Browser audio/video outputs will depend on the system's chosen playback device.
- Only use audio/video files and lyrics you are authorized to reproduce or publicly perform/display. The app doesn't include copyrighted files or lyrics.
- For venues with uncertain internet, test by opening `index.html` directly from your laptop, load all audio/video files, and avoid reloading the browser during the fair.
