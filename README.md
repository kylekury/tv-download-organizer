# tv-download-organizer

## Requirements
- Python3
- Handbrake
- TV downloads are in the same root folder
- Destination(s) for your shows
-- Example: A media folder backed by Plex/XBMC
-- Example: A media folder automatically imported by iTunes

## Steps

- [For each file in root folder ending in mkv, mp4, m4v, avi, flv, mov, wmv]
- Pulls out TV show name, season and episode number
- Create folder work
- Re-organizes the files into work/[TV Show Name]/[Season]/[TV Show Name].S[Season Number].E[Episode Number].[extension]
- Copy work/* into destination folder(s)
- For iTunes, we must convert to mp4 w/ handbrake first
