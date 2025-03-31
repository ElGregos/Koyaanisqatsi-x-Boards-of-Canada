![](/images/Koyaanisqatsi-x-BoardsOfCanada.png)

*Koyaanisqatsi × Boards of Canada* is a Boards of Canada music mix crafted as an alternative soundtrack to the 1982 movie *Koyaanisqatsi*. Although Philip Glass original soundtrack is one of his very best works and critical to the importance of that movie, this project is the fulfillment of an imperative urge for Koyaanisqatsi and Boards of Canada to meet.

While Boards of Canada allow their music to play on YouTube, showing the whole *Koyaanisqatsi* movie there is impossible for obvious copyright reasons. Hence this GitHub repository allowing you to build your own video file, provided you add the Koyaanisqatsi and Boards of Canada files. 

You can also simply enjoy the mix on [YouTube](https://youtu.be/ncp7bPfbITw) which includes a video made to check everything stays in sync if you choose to play the mix along a muted Koyaanisqatsi video, give a glimpse of this movie and music relationship and encourage people to use this repository to appreciate *Koyaanisqatsi × Boards of Canada* as intended, but also offer both an experience of its own and a 1h26 undecipherable trailer of this movie that everyone should watch. The mix (audio only) is on [SoundCloud](https://soundcloud.com/gregosel/koyaanisqatsi-x-boards-of-canada) too.

# How to build your video

Besides this tutorial, repository mainly contains the **Koyaanisqatsi-x-BoardsOfCanada.rpp** Reaper file which describes how video and audio files are organized into the final mix. It comes in two versions, synchronized either to the regular or the Criterion edition of the movie. In short, that's the whole mix recipe, it only needs ingredients:
- **Boards of Canada** music files. Unless you own CDs, Bandcamp is the no-brainer solution to get them. In any case, FLAC format is recommended for its optimal quality. [Files tree](#files-tree) section below lists all tracks used, with links to each of them and their albums on Bandcamp.
- The **Koyaanisqatsi** movie as a file. Alas there's no Bandcamp for movies so legally getting the Koyaanisqatsi file may be trickier. Ripping a Blu-ray or DVD is still the way to go, which is a well known process I won't explain here beyond recommanding MakeMKV and HandBrake. Any edition used must be at 23.976 frames per second, different framerates will more or less break the music synchronization. Fortunately, video framerates can be altered too, but that goes beyond this tutorial too.

You'll also need tools:
- [**Reaper**](https://www.reaper.fm/), the audio editor used to make this mix. It's free to use for 60 days, after that each launch will remind you to buy the full $60 version.
- Optional but recommended: a tool to allow multiplexing, i.e. adding the generated mix audio file to Koyaanisqatsi video without re-encoding it and, even better, keeping the original Philip Glass music as second audio track. [**Avidemux**](https://avidemux.sourceforge.net/) is free and made for this but it may be achieved in many ways, like FFMPEG.

## Files tree
Here are the files tree as defined in the RPP file. You can either organize your files the same way, or let Reaper ask for their location. You may also search & replace paths in the RPP file as it is a plain text file, but that may be tricky and won't be detailed here.

╓─ **[Boards of Canada](https://boardsofcanada.bandcamp.com/)**<br/>
║ ╟─ **[Geogaddi](https://boardsofcanada.bandcamp.com/album/geogaddi)**<br/>
║ ║ ╟─ 02- [Music Is Math](https://boardsofcanada.bandcamp.com/track/music-is-math).flac<br/>
║ ║ ╟─ 06- [Sunshine Recorder](https://boardsofcanada.bandcamp.com/track/sunshine-recorder).flac<br/>
║ ║ ╙─ 14- [Alpha and Omega](https://boardsofcanada.bandcamp.com/track/alpha-and-omega).flac<br/>
║ ║<br/>
║ ╟─ **[Music Has the Right to Children](https://boardsofcanada.bandcamp.com/album/music-has-the-right-to-children)**<br/>
║ ║ ╟─ 02- [An Eagle in Your Mind](https://boardsofcanada.bandcamp.com/track/an-eagle-in-your-mind).flac<br/>
║ ║ ╟─ 09- [Bocuma](https://boardsofcanada.bandcamp.com/track/bocuma).flac<br/>
║ ║ ╟─ 10- [Roygbiv](https://boardsofcanada.bandcamp.com/track/roygbiv).flac<br/>
║ ║ ╙─ 18- [Happy Cycling](https://boardsofcanada.bandcamp.com/track/happy-cycling).flac<br/>
║ ║<br/>
║ ╟─ **[The Campfire Headphase](https://boardsofcanada.bandcamp.com/album/the-campfire-headphase)**<br/>
║ ║ ╟─ 04- [Peacock Tail](https://boardsofcanada.bandcamp.com/track/peacock-tail).flac<br/>
║ ║ ╙─ 09- [Oscar See Through Red Eye](https://boardsofcanada.bandcamp.com/track/oscar-see-through-red-eye).flac<br/>
║ ║<br/>
║ ╟─ **[Tomorrow's Harvest](https://boardsofcanada.bandcamp.com/album/tomorrows-harvest)**<br/>
║ ║ ╟─ 02- [Reach For The Dead](https://boardsofcanada.bandcamp.com/track/reach-for-the-dead).flac<br/>
║ ║ ╟─ 06- [Cold Earth](https://boardsofcanada.bandcamp.com/track/cold-earth).flac<br/>
║ ║ ╟─ 08- [Sick Times](https://boardsofcanada.bandcamp.com/track/sick-times).flac<br/>
║ ║ ╟─ 10- [Palace Posy](https://boardsofcanada.bandcamp.com/track/palace-posy).flac<br/>
║ ║ ╟─ 14- [Sundown](https://boardsofcanada.bandcamp.com/track/sundown).flac<br/>
║ ║ ╟─ 15- [New Seeds](https://boardsofcanada.bandcamp.com/track/new-seeds).flac<br/>
║ ║ ╙─ 16- [Come To Dust](https://boardsofcanada.bandcamp.com/track/come-to-dust).flac<br/>
║ ║<br/>
║ ╟─ **[Trans Canada Highway](https://boardsofcanada.bandcamp.com/album/trans-canada-highway)**<br/>
║ ║ ╟─ 02- [Left Side Drive](https://boardsofcanada.bandcamp.com/track/left-side-drive).flac<br/>
║ ║ ╙─ 04- [Skyliner](https://boardsofcanada.bandcamp.com/track/skyliner).flac<br/>
║ ║<br/>
║ ╙─ 01- [Seven Forty Seven](https://warprecords.bandcamp.com/track/seven-forty-seven).flac<br/>
║<br/>
╟─ Koyaanisqatsi-x-BoardsOfCanada(criterion).rpp<br/>
╟─ Koyaanisqatsi-x-BoardsOfCanada(regular).rpp<br/>
╟─ Koyaanisqatsi(criterion).mkv<br/>
╙─ Koyaanisqatsi(regular).mp4<br/>

## Reaper setup
- Open video monitor in View/Video (ctrl+shift+V).
- [**Reaper**](https://www.reaper.fm/) generates waveform images for media used, stored by default in their associated media folders as .reapeaks files. To use a dedicated folder instead, open Options/Preferences (ctrl+P), in General/Paths check "Store all peak caches (.reapeaks) in alternate path" and browse for a folder underneath. You can safely delete .reapeaks files anyway, they'll just be recreated when needed.

### Quick help
- mousewheel: vertical scrolling (over tracklist on left) or horizontal zoom in/out (over clips).
- ctrl+mousewheel: vertical zoom in/out.
- alt+mousewheel: horizontal scrolling.
- Space: play/stop.
- Enter: play/pause.
- Home/End: Move cursor to start/end of mix.
- shift+Up/Down key: zoom in/out waveforms vertically.

# Let's build that mix

It goes like this:
- [Load the RPP file](#load-the-rpp-file) and set sources location.
- [Check video & music synchronization](#check-audio--video-synchronization), then [fix unsynced video](#fix-unsynced-video) and [bring video clip to start](#bring-video-clip-to-start) if needed.
- [Add extra sounds](#add-extra-sounds) to the mix if you'd like, like MGM lion roar.
- [Export the mix](#export-the-mix).
- [Mux the audio to original video file](#mux-the-audio-to-original-video-file).

## Load the RPP file

Now launch Reaper and open the .rpp file fitting your Koyaanisqatsi edition. If your files tree differs from [the one above](#files-tree), this window will pop asking for each missing file:

![](/images/capture01.png)

So click "Browse for file...", select missing file, and repeat until load is complete. Video format does not matter as long as Reaper can read it, i.e. you can load a .mp4 even if it's asking for a .mkv. A "Building Peaks..." window will open, displaying files being scanned to build their waveforms. Then Reaper main screen should look like this:

![](/images/allFilesLoaded.png)

## Check audio & video synchronization

Those vertical colored bars are markers. #0 (red) marks the start of video on [YouTube](https://youtu.be/ncp7bPfbITw), allowing viewers to approximately know when to launch the mix there, while their Koyaanisqatsi movie plays locally. Yellow markers will help checking synchronization. Make sure video monitor is opened (ctrl+shift+V) and click on each marker head listed below: cursor goes there and if you're lucky, the monitor shows the **exact** corresponding image. Moreover, the frame just before those shown should be completely different.

| Marker | Name |  Frame |
| --- | --- | --- |
| 1 | Butte | ![](/images/01-butte.jpg) |
| 2 | Ruins | ![](/images/02-ruins.jpg) |
| 3 | Factory | ![](/images/03-factory.jpg) |
| 4 | Thruster | ![](/images/04-thruster.jpg) |

If that's the case, great, now you can either [add extra sounds](#add-extra-sounds) or directly [export the mix](#export-the-mix). Otherwise, let's fix this in next part.

## Fix unsynced video

By default Reaper jogs audio when we drag the cursor triangle head, which is too slow, we need fastest access to video image instead. So open Options/Preferences (ctrl+P), select Editing Behavior/Mouse modifiers on left, choose Edit cursor handle on top dropdown, double-click on Default action and choose "No action".

![](/images/reaperSettingMouseNoAction.png)

Then check #4 "Thruster" marker. The picture you're looking for is the 1st frame where that falling and rotating thruster is zoomed in. Drag cursor around the marker to roughly find it. Then drag the video item from the cursor position to marker position, and click that marker head to bring cursor there. Now use mousewheel to zoom in/out and precisely drag the clip to bring that zoomed-in thruster 1st image under that marker.

![](/images/reaperFindThruster.gif)

If you can't move your video left enough, this means it has a longer intro than intended and you need to move everything to the right to give space. Check "Options/Ripple edit all tracks" so that markers will follow items, then ctrl+A to select everything and move the whole as much to the right as needed by dragging any item. Then uncheck "Options/Ripple edit all tracks" to no longer move markers with clips. Now you can look for that thruster image again as described above.

Once done, check other images at markers listed above and if everything's ok, jump to [next section](#bring-video-clip-to-start). If not, make sure the very first image showing the thruster is precisely under #4 marker. If, despite this, other markers still don't show their intended pictures, this means your video is either a different framerate than 23.976 fps, or its edit is different; in both cases the video won't fit and you need to either adapt its framerate to 23.976 (Internet or an AI chat will help), or find another video to enjoy *Koyaanisqatsi × Boards of Canada* the expected way.

## Bring video clip to start
Make sure there's no empty gap before the video, or the mix export will have a delay. Select all clips with ctrl+A, check "Options/Ripple edit all tracks" so that markers will follow (just in case), and drag the video clip as much to the left as possible. All clips and markers will move at once.

## Add extra sounds
For now the mix only contains Boards of Canada music, but you may want to add some outside sounds, like the lion roar that begins and ends all MGM movies. To do so, duplicate the video track and maybe rename it, place cursor where you want to cut that new track, split item, delete the rest of the video (DEL key) and bring track volume back to 0 dB with a double-click on its potentiometer.

![](/images/addLionRoar.gif)

## Export the mix

There are 3 ways to at last enjoy the movie with its new soundtrack:
- Just watch it in Reaper in full screen (click on monitor, then alt+Enter or Options/Full screen). Sometimes simplicity is good enough. You can still export later. Don't forget to save your Reaper project though.
- [Export the whole video and audio](#export-the-whole-video-and-audio). Straight enough, but this will re-encode video so you'll lose quality, and you'll lose Philip Glass soundtrack too. You're a bit on your own there as I didn't manage to get satisfying results, but in case you're more at ease than I am or eager to experiment, check that section.
- [Export the audio only](#export-the-audio-only), and mux it to the original video (mux, as multiplexing). This is the best: you keep original video and Philip Glass soundtrack untouched, and you just add this mix as secondary track. Or set that mix as main audio track and Glass as 2nd. Better and faster than exporting the whole video.

### Export the whole video and audio

Click "Files/Render... (ctrl+alt+R)" to open this window:

![](/images/reaperRenderVideo01.png)

These settings allowed to get a mp4 video, but with keyframes distinctly showing every second. On the other hand, the "Video (ffmpeg/libav encoder)" format generated a mkv video file VLC could barely read. Oh well. Maybe you'll get luckier, otherwise next section is the best option.

### Export the audio only

Click "Files/Render... (ctrl+alt+R)" to open this window:

![](/images/reaperRenderAudio01.png)

These are the settings I used but if you're familiar with audio codecs you may have better choices. Check Directory and File name and when you're all set, click "Render 1 file".

Now you may save this project and close Reaper.

## Mux the audio to original video file
First make a security copy of the video you used in your mix, we never know. Then open [**Avidemux**](https://avidemux.sourceforge.net/). Drop that video file into it. Now click "Audio/Select track" which opens this window:

![](/images/avidemux01.png)

If you want to set the mix to track 1, open the dropdown menu, select ".... Add audio track" and browse for your exported mix file, then check "Track 2" to enable it with Philip Glass music. You'll then be able to switch audio track in VLC f.e. with "Audio/Audio track", or "B" key. If you'd rather have Glass music on track 1 and the mix on 2, keep Track 1 untouched, check Track 2 and browse for your file.
Now click "OK" to close that window. On the left, in "Output Format" dropdown menu, choose your format; it should be the same than the given video. Then open File/Save (ctrl+S), select location & name, save, progress bar shows and after a few seconds your new video is built. Well done! Now you can watch *Koyaanisqatsi × Boards of Canada*.

# Links
- *Koyaanisqatsi × Boards of Canada* on [YouTube](https://youtu.be/ncp7bPfbITw) and [SoundCloud](https://soundcloud.com/gregosel/koyaanisqatsi-x-boards-of-canada).
- *Koyaanisqatsi* on [Wikipedia](https://en.wikipedia.org/wiki/Koyaanisqatsi) and [IMDb](https://www.imdb.com/title/tt0085809/).
- Boards of Canada on [Wikipedia](https://en.wikipedia.org/wiki/Boards_of_Canada), [Spotify](https://open.spotify.com/intl-fr/artist/2VAvhf61GgLYmC6C8anyX1), [Deezer](https://www.deezer.com/fr/artist/1098), [Bandcamp](https://boardsofcanada.bandcamp.com/), [Discogs](https://www.discogs.com/artist/307-Boards-Of-Canada), [AllMusic](https://www.allmusic.com/artist/boards-of-canada-mn0000758999), [Warp](https://warp.net/artists/boards-of-canada), [SoundCloud](https://soundcloud.com/boardsofcanada) and fan wiki [bocpages](https://bocpages.org/wiki/About).

## Tools
- [Reaper](https://www.reaper.fm/) is the audio tool used to make this mix. You can freely use it for 60 days, beyond that each launch will remind you its full price is $60.
- [Avidemux](https://avidemux.sourceforge.net/) to mux audio to video file.
