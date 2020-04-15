This is the soundtrack music for the original Quake campaign. You can use these files to hear the soundtrack while playing through the Quake campaign using a modern "Quake engine" (a program that plays Quake).

These tracks should work as-is for the following Quake engines: DarkPlaces, QuakeSpasm, Fitzquake Mark V, DirectQ, qbism Super 8, reQuiem, and QuakeForge. They may also work for any other Quake engine that is designed to use the now-standard format for music track placement and naming.

Put the "music" folder and its contents inside your "id1" folder.

If you're using the QuakeForge engine, you also need to put the tracklist.cfg file inside your "id1" folder.

You should now hear the soundtrack while playing the original Quake campaign using one of the above Quake engines. If not, make sure your music volume isn't set to zero!

That's all there is to it. More info below though, if you're curious or having problems.

==========

The tracklist.cfg file is used only by QuakeForge, but it doesn't hurt anything to have that file in place even while using some other Quake engine.

It also shouldn't hurt to have both the .ogg and .mp3 files in place, regardless of which music format(s) your Quake engine can play.

The .ogg files can be read by DarkPlaces, QuakeSpasm, DirectQ (if you have the necessary DirectShow filter installed), qbism Super8, and QuakeForge.

The .mp3 files can be read by QuakeSpasm, FitzQuake Mark V, DirectQ, qbism Super8, and reQuiem.

If you're playing on Linux, you may need to install additional external libraries for playing music files of these formats, such as libogg or libvorbis for OGG support, and libmad or libmpg123 for MP3. You can check the documentation for your Quake engine of choice to be sure.

If you are using an engine that can read both .ogg and .mp3, and you experience playback issues when it attempts to play one of those formats, possibly you have some sort of missing or misconfigured codec on your computer. You could try removing the soundtrack files with the "problematic" format to force your Quake engine to try using the files in the other format.

If you have these soundtrack files installed but you are hearing something different while playing, make sure you don't have a physical CD in your CD drive. Also make sure you don't have any other soundtrack files installed somewhere under your Quake folder (maybe inside a .pak or .pk3 file).

These tracks were ripped from CD to a lossless format, properly handling any CD pre-emphasis. The .ogg tracks were generated from the lossless rips using ffmpeg with the libvorbis codec set with qscale:a 8. The .mp3 tracks were generated from the lossless rips using ffmpeg with the libmp3lame codec set with qscale:a 0.

==========

For more about Quake soundtrack support see this guide:
http://steamcommunity.com/sharedfiles/filedetails/?id=119489135

also mirrored at:
http://neogeographica.com/site/pages/guides/soundtrack_solutions.html

