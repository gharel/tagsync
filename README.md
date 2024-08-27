# iTunes MP3 tag sync
Command line utility to sync itunes metadata with tags in files  
Import files by 1 000 on iTunes to avoid bugs  
Sync files on Phone by 1 000 Tracks to avoid bugs  
Fork of https://github.com/sergei-dyshel/itunes-tag-sync

## Requirements
Need Python 3.12

## Install
```poetry install```

## Run
Keep iTunes in English, select Track in view mode, look tagsync.py line 190 to find option for CLI.

```poetry run python tagsync.py --dry --sel --update```
