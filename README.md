# Quick Access Spotify Data

**Live Demo:** [music.lucas.tools](https://music.lucas.tools)

## Description

A lightweight web app that uses the Spotify Web API (PKCE OAuth) to fetch and display your:

* Current user profile
* Top artists (short, medium, long term)
* Top tracks (short, medium, long term)
* Currently playing track
* Recently played tracks

No server needed, just a simple HTML page with JavaScript. The app uses the Spotify Web API to fetch data and display it in a user-friendly way.

## Setup & Development

1. **Clone or download** this repo.
2. **Configure** your Spotify app:

   * Go to the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
   * Create an app (or use an existing one).
   * Add your Redirect URI (e.g., `https://music.lucas.tools/index.html`).
3. **Update** `index.html`:

   ```js
   const clientId = 'YOUR_SPOTIFY_CLIENT_ID';
   ```
4. **Serve** the files over HTTP (e.g., `npx serve .`).
5. **Visit** `https://music.lucas.tools` and log in.

## Support & Coffee ☕️

If you enjoy this tool, consider buying me a coffee:

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/lucasobe)
