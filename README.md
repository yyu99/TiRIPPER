# TiRIPPER - a Tidal Album/Playlist Downloader

Copyright 2017 Yongliang Yu krustysworld@gmail.com

Released under [MIT License](http://en.wikipedia.org/wiki/MIT_License)

This script allows the user to produce 1:1 album/playlists rips from the Tidal music database. Requires Tidal subscription access.



# Requires -
* metaflac 
* gsed
* ffmpeg
* jq

# Features -

* Builds FLAC metadata from track listings
* Builds folder in format %artist% - %album% (%year%) [%format%]
* Lossless checker for guaranteed 16-bit 1411 kbps (some albums are only available in 320 or 192 kbps on Tidal) - allows option to skip
* Compatibility with MQA "Master" Quality albums
* Exceptional cover art replication at phenomenal resolutions (1280x1280)
* "Various Artists" check for multiple album contributors 
* Adds gain metadata across album tracks
* File checker at end of rip for verifying rip completion
* Allows indexed start ripping for broken downloads
* Checks for duplicates in folder
