### Calibre cron job

## Configuration

```sh
cp config.template config
```

Update your user data in config file

## Adding to crontab
```sh
crontab -e
```

and add line

```sh
0   8,20   *   *   *   $HOME/calibre_cron/calibre.job 2>&1
```

---
_More info on:_ [crontab](http://ss64.com/osx/crontab.html)