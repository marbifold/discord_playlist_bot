# Simple Playlist Bot

Discord bot which listens for a particular channel where users share links to songs on Spotify. From those URLs, it adds the songs to a collaborative playlist.

Refer to [this article](https://medium.com/marble-manifold/build-a-discord-bot-for-adding-tracks-to-a-collaborative-spotify-playlist-from-a-channel-5c4e8b149cac) for more detailed instructions.

## Environment Variables
* `DISCORD_TOKEN`
* `SPOTIPY_CLIENT_ID`
* `SPOTIPY_CLIENT_SECRET`
* `SPOTIPY_REDIRECT_URI`
* `SPOTIFY_PLAYLIST_NAME`
* `SPOTIFY_PLAYLIST_ID`

## Setup
0. Make sure you have the proper values ready for all environment variables
1. Clone the repo to your local machine
2. Within the repo, initialize your virtual environment using `requirements.txt`
3. Run authentication with the Spotify API by running `python src/spotify_helper.py`
4. In your preferred hosting service, set the environment variables as secrets
5. Deploy the application via the Dockerfile
