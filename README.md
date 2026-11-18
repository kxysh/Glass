# Glass

A modern music player for Windows that doesn't eat your resources.
Spotify, SoundCloud, YouTube Music and your own files all play from the same app.

## What it does

Plays Spotify (Premium), SoundCloud, YouTube Music and local files, with playlists, liked songs, and lyrics
There's an ambient mode, Discord RPC, and a performance mode for weaker PCs.

## Download

Grab `Glass.exe` from the [latest release](../../releases/latest) and run it.

It isn't signed yet (and probably won't be in the near future), so Windows will probably say it doesn't recognise it.
Click More info, then Run anyway.
The first launch after every update is slow while Windows scans it.

## Setup instructions

Spotify restricts apps in developer mode, so Glass uses a Client ID that you make yourself.

1. Make an app in the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
2. Set the redirect URI to `http://127.0.0.1:5543/callback` and tick Web API and Web Playback SDK.
3. Under User Management, add your Spotify account's name and email.
4. Paste the Client ID into Settings in Glass, then play a Spotify song and log in.

## Bugs

Settings has a Report a bug box. It sends your settings and recent logs along with it unless you switch off Include diagnostics.
Info on bugs is in the [Discord](https://discord.gg/HPQjrqSrfU).
