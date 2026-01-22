## SIG Public Resources

### Scripts
FFmpeg script to generate thumbnails for the backgrounds 280x158:
```bash
ffmpeg -i bg.png -vf "scale=280:158" -frames:v 1 -update 1 bg_thumb.png
```

Run commands for Teams for Linux to allow custom backgrounds:
```bash
/opt/teams-for-linux/teams-for-linux %U --isCustomBackgroundEnabled=true --customBGServiceBaseUrl=https://raw.githubusercontent.com/RisPNG/SIG-Resources/main
```
