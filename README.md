### Calibre RSS job
This script will send your calibre RSS source to kindle every 8h.


## Configuration
```sh
cp config.template config
```
Update your user data in config file


## Add script to launchd
```sh
ln -s [CALIBRE_RSS]/local.calibre.rss.plist ~/Library/LaunchAgents/local.calibre.rss.plist
launchctl load ~/Library/LaunchAgents/local.calibre.rss.plist
```
