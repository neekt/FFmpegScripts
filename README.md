# FFmpegScripts
A collection of custom context menu items for the Nemo and Nautilus file managers, for making quick edits to video files and streams with FFmpeg.

Actions include options for file conversion, flipping/rotating, cropping, trimming, joining, looping/boomeranging, video speed, audio, effects/filters, and editing bitrate, frame rate, and resolution.

This is essentially an alpha release, and bugs are to be expected. All actions create new files, and should pose absolutely no danger to any of your existing files. However, the usual disclaimer about securely backing up all of your files applies.

**Requirements**

These scripts require FFmpeg and Zenity to run. If they're not already available in your distribution's software repository, you can install them with:

`sudo apt-get update`

`sudo apt-get install ffmpeg`

`sudo apt-get install zenity`

You'll also need Montage if you want the option to generate video thumbnails:

`sudo apt-get install montage`

They have been tested on Linux Mint and Ubuntu, but should work on any Debian-based distribution running Nemo and/or Nautilus.

**Installation**

The simplest way to install these scripts at the moment is to simply download the .zip file and unpack it in `/home/[user]/.local/share/nemo/scripts` (for Nemo) or `/home/[user]/.local/share/nautilus/scripts` (for Nautilus). Once the bugs are ironed out, I will provide instructions for cloning this repo and receiving updates.

**Use**

Simply right click on any video file in Nemo or Nautilus, and the actions can be found in Scripts > FFmpegScripts. Most of the actions should be fairly self-explanatory, but I will provide some documentation for them at some point soon.
