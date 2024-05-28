## Music Streaming Service in Flask

### HTML Files
- **index.html**: Homepage of the music streaming service, featuring music categories, popular songs, and a search bar.
- **browse.html**: Page for browsing music by category, displaying playlists and albums.
- **artist.html**: Page for an individual artist, showing their profile, albums, and popular songs.
- **album.html**: Page for an album, showcasing its cover, tracklist, and reviews.
- **search.html**: Results page for music search, listing songs, albums, and artists.

### Routes

**Homepage:**
- `/`: Redirects to the index page.

**Browsing:**
- `/browse`: Displays the browse page for selecting music categories.
- `/browse/<category>`: Shows playlists and albums within a specific music category.

**Specific Pages:**
- `/artist/<artist_id>`: Displays the artist page with their profile, albums, and songs.
- `/album/<album_id>`: Presents the album page with its cover, tracklist, and reviews.
- `/search`: Redirects to the search results page.

**Search:**
- `/search/query`: Displays the search results page for a given query, containing songs, albums, and artists.

**Actions:**
- `/play/<song_id>`: Plays the selected song.
- `/add_to_playlist/<song_id>`: Adds the song to the user's current playlist.
- `/create_playlist`: Creates a new playlist for the user.