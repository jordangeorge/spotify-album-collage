# Spotify Album Collage

![Image collage](collages/collage.jpeg)

### Contents
- collage.ipynb
  - Jupyter Notebook that creates the college
  - Saves files locally
- collage-aws.ipynb
  - Jupyter Notebook that creates the college
  - Saves files in an AWS S3 bucket

### About
A program that creates an image collage from album covers from recently saved Spotify songs.

I came up with this idea when I wanted an album collage as my desktop wallpaper and figured others might want to do the same. Kind of similar to when I had songs on iTunes (before I jumped on the Spotify train in 2012) and it would create a screen saver of all the albums.

The first iteration took about under a day in real time because I wasn't familiar with the PIL library at all and, therefore, had to spend a lot of that time troubleshooting errors.

### Current Functionality
- User can generate a basic collage in the notebook

### Instructions on Using Jupyter Notebook
- Export the following environment variables:
  - SPOTIFY_CLIENT_ID
  - SPOTIFY_CLIENT_SECRET
  - SPOTIFY_REDIRECT_URI
  - SPOTIFY_USERNAME
- Run `jupyter notebook collage.ipynb` in command line
