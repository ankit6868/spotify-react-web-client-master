# Spotify React Web Client

Spotify Web Client using [Spotify Web API](https://developer.spotify.com/documentation/web-api/) and [Spotify Playback SDK](https://developer.spotify.com/documentation/web-playback-sdk/).

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## Features

- Play full audio tracks.
- Control playback (pause, volume, shuffle, etc).
- Add or edit your playlists.
- See your recently played tracks and your top artists.
- Follow and unfollow playlists and artists.
- Add or remove tracks from your library.
- Change the device in which you are currently playing.
- Search tracks, albums, artists and playlists.

## Try it out

https://spotify-react-web-client.herokuapp.com

**Warning:** Spotify Playback requires users to authenticate with a valid Spotify Premium subscription.

## How to Run locally

First you need a [Spotify Client ID](https://developer.spotify.com/dashboard/applications).

```bash
$ git clone https://github.com/francoborrelli/spotify-react-web-client.git
$ cd spotify-react-web-client
$ npm i
```

You will have to define a '.env' file and set the following variables:

```
REACT_APP_CLIENT_ID="YOUR_CLIENT_ID"
REACT_APP_REDIRECT_ID=http://localhost:3000/
```

Now run:

```bash
$ npm start
```

and visit http://localhost:3000.

## Use Docker!

```
docker-compose up -d
```

## Screenshots

![browse](file:///C:/Users/ANKIT/Pictures/Screenshots/Screenshot%20(1420).png 'Playlist')
![playlist](file:///C:/Users/ANKIT/Pictures/Screenshots/Screenshot%20(1421).png 'Artist')
![artist](file:///C:/Users/ANKIT/Pictures/Screenshots/Screenshot%20(1422).png'Artist')
![devices](file:///C:/Users/ANKIT/Pictures/Screenshots/Screenshot%20(1423).png')

More in images folder.