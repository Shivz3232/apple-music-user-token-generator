# Script to generate an Apple Music User Token

Hosted version: https://shivz3232.github.io/apple-music-user-token-generator/

The `Music-User-Token` header is required to call Apple Music's user specific APIs. [Docs](https://developer.apple.com/documentation/applemusicapi/generating-developer-tokens)

I could find tonnes of examples to generate the developer token, which is used in the `Authorization` header but none for the music user token!!!

Script to generate the `DEVELOPER TOKEN`: [github repo](https://github.com/pelauimagineering/apple-music-token-generator)

IOS is not required! pure html solution!

Unfortunately the MusicKit library requires an URL to complete the OAuth flow, hence just opening html file in a browser will not work.

You may use a server of your choice to serve the html, I have used python/node

## Steps
0. If you are not able use [this](https://shivz3232.github.io/apple-music-user-token-generator/) hosted version, then follow the steps below
1. `git clone \<repository url\>`
2. `cd apple-music-user-token-generator`
3. If you are using python: `python -m http-server` & visit localhost:3000
4. If you are using node: `npx http-server --cors` & visit localhost:8080
5. Input your developer token
6. Click load
7. Make sure the apple musickit loaded turns True
8. Click authorize
