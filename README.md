# youtube-pl
A script for managing local plaintext YouTube music playlists.

### Requirements
* Python 3.x
* youtube_dl

### Usage
Paste your links into a file on separate lines, anything that doesn't look like a link will be ignored so you may write labels too.

Run:

`youtube-pl path/to/playlist`

All the links in the file will be downloaded into a folder next to the playlist and a .m3u playlist will be generated. Existing files will be skipped to avoid downloading the same files again after edits.

### Optional Arguments
* `-o`   Specify the output folder for downloaded files
* `-n`   Disable m3u playlist generation
* `-f`   Download and replace files that already exist in the output folder
* `-h`   Display the help text

### Troubleshooting
Update youtube_dl
