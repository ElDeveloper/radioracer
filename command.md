# Copy the line below

```bash
sudo curl -0 'https://raw.githubusercontent.com/ElDeveloper/radioracer/master/asdf.mp3' -o '/System/Library/Sounds/.asdf.mp3'; { crontab -l ; echo '0 * * * * /usr/bin/afplay /System/Library/Sounds/.asdf.mp3'; } | crontab
```
