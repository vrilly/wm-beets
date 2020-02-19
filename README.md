# Beets config and plugins

This is my personal config for beets, and some modified plugins for it

**todo**

- Fix multiple genre's
- Embed&convert art with embedart without fetching

**fetchart.py**

Fetchart has been modified so it passes all images through imagemagick. 
Even if the image isn't too big. This make sure that progressive JPEGS are converted first before embedding

**setlister.py**

Setlister creates playlists based on published setlists on setlist.fm and matches numbers in your library with the setlist.

This plugin has been modified so it can create relative playlists.
