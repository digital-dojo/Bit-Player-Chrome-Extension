# Bit Player Chrome Extension

Chrome extension for playing video torrents.

###Features / Roadmap (help will be appreciated :) )
- [x] Play the main video file of a torrent.
- [ ] Find a way to recreate the nodejs bundle.ts.js file (currently i'm using a compiled file that i found online).
- [x] Open subtitles integration (using automatic hash only).
- [x] Open player using chrome's context menu on a magnet link - solved with another extension (couldn't find a better solution due to chrome's security restrictions.
- [ ] Create new icon for the plugin.
- [ ] Test the plugin with large video files - currently the video is stored in memory and i'm not sure it will work with large files.
  - [ ] Clear memory once the user closes the main window (looks like it stays with the bg.js)
- [ ] Player:
  - [ ] Create or integrate a better video player/controls.
  - [ ] Integrate a player that will support more video file types(??)
  - [x] Keyboard shortcuts (space: play/pause, left/right: 10 secs skip, up/down: 1 minute skip). 
  - [x] Mouse hiding on playing.
  - [ ] Add chromecast support.
- [ ] Subtitles:
  - [x] Change subtitles font size.
  - [x] Fix encoding issues.
  - [ ] Allow user to choose subtitles language.
  - [ ] Subtitles sync.
  - [ ] Integrate more subtitles vendors.
  - [ ] Subtitles manual search.
  - [x] Load subtitles from file.
- [ ] Storage:
  - [ ] Save user's settings to persistence storage.
    - [x] subtitles size.
    - [x] subtitles language and if on or off.
    - [ ] Save user's list of watched videos so that he can choose new ones.
- [ ] Add plugins support (Kodi style).
- [ ] Integrate with a website like myepisodes.com.
- [x] Allow user to save the downloaded video file to disk.
- [x] Allow user to play a video from the disk.

