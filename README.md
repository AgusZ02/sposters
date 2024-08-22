# <a href="https://agusz02.github.io/SpostersWeb/">Sposter</a> 
Generates posters from any album/song/artist available on Spotify. It grabs the cover art, scannable code and and combines them into a single image wich you can download in a single click. Current output size is 640x800 pixels, since that is the biggest resolution that Spotify's API provides for album covers.

<p align="center">
    <img src="https://github.com/AgusZ02/Sposter/assets/76200509/9e349f73-0ae2-4ae6-9b7c-d92c9daa9ebe" alt="Badge"/>  
</p>

# Features
- Get album/track covers and artist's profile pictures from Spotify's database
- Generate Spotify scannable codes
- Pick custom colour for the scannable code's background
- Select between black and white for scannable code's stripes
- Automatic colour picking for code's background
  
# Technologies used
- Spotify API documentation: https://developer.spotify.com/documentation/web-api
- Tailwind documentation: https://tailwindcss.com/docs/installation
- Cover's colour palette extraction tool: https://www.npmjs.com/package/color.js
