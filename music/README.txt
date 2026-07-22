Background music
================

Current track: call-it-fate.mp3
(The Strokes - Call It Fate, Call It Karma)

The page plays it on a loop at 70% volume, starting automatically the
first time Susan interacts with the page (clicks/taps anything). This is
because browsers block audio from autoplaying until the visitor interacts.

There is a 🔊 button in the top-right corner to mute / unmute.

To swap the song
----------------
- Replace call-it-fate.mp3 with another file of the same name, OR
- Put a new file here and update the <source> tag in index.html
  (search for "music/call-it-fate.mp3") to match the new filename.
- .mp3 is the safest format for all browsers.
- To change the volume, edit index.html and search for "bgm.volume"
  (0.7 = 70%). To stop looping, remove the word "loop" from the
  <audio id="bgm" ...> tag.
