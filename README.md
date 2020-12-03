# online-video-wrangler

# Install software 

Install Homebrew 
[brew.sh](https://brew.sh)

Install FFMPEG
```	
brew install ffmpeg
```

Install ImageMagick
```	
brew install imagemagick
```

Install Python
```	
brew install python3
```

Install youtube-dl
```
pip3 install youtube-dl
```

# Edit videos.csv with the videos to download

- Column 1: filename
- Column 2: url
- Column 3: trim start (optional per video to override the script variable)
- Column 4: trim end (optional per video to override the script variable)

# Edit process-videos.sh configuration

Edit the variables at the top of the script
- Clip start, end, size
- Still large and small sizes

# Run the script

Open the terminal to this directory and run

```
bash process-videos.sh
```