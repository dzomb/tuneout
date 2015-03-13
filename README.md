# tuneout
An apple script that writes iTunes song and artist information to a text file for use with the "text-from-file" feature of OBS streaming software.  TuneOut and OBS, used together, will display iTunes now-playing information during a stream.

1. Open iTunes
2. Play a song.
3. Run the TuneOut applescript.
4. Create or Select a text file to use.
5. Create a text source in OBS and select Text-From-File
6. Browse to the file you created from iTunes in step 4. 
7. Format the text as you like!

WARNING - Don't select the wrong file in step 4.  This script clears the file contents and rewrites them. 

To change "refresh rate" you can change the delay in the script. 

Helpful tip:  goto File > Export and select the Application file format. This way you don't need to run it from Apple Script every time. (Just a convenience feature anyone might want to use.)

It'll ask you to select a text file, but the first time you run it, just type in a name that doesn't already exist, and just use that same file every time. You can then add that text file to OBS and, when iTunes (or any other Music player - just change where it says "iTunes" to the name of the player, like "Spotify") is playing music the file will have the text in it. Also make sure iTunes is running. 

Thanks to @NateSandstorm for pointing this out on the OBS Forums. 
