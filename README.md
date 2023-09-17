# PopupLyrics-Plus
### Modded Spiceify [PopupLyrics](https://github.com/spicetify/spicetify-cli/tree/master/CustomApps/lyrics-plus) to enable translations and more! 拥有翻译和更多功能的PopupLyrics~
<img width="751" alt="Screen Shot 2023-09-16 at 11 46 37 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/ab072cb7-dbd9-48b2-a65d-10b50bd3949c">
*Chinese translation*

<img width="751" alt="Screen Shot 2023-09-16 at 11 46 23 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/20868246-8933-4e9c-b22d-821202607b05">
*English translation*

<img width="751" alt="Screen Shot 2023-09-16 at 11 45 51 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/b1ad870e-514b-4dae-8a53-74cca70aae88">
*Romaji translation*

<img width="751" alt="Screen Shot 2023-09-16 at 11 45 19 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/85f4ac26-9c5e-446e-96bb-10867a6f762f">
*Original*

## Features
- Way more stable [Netease API](https://github.com/Binaryify/NeteaseCloudMusicApi) to fetch from, allowing Netease lyrics to actually work
- Netease Chinese lyrics translation
- English translation through google translate (a bit slow)
- Romaji translation
## Work in Progress
- More options in display
- Online API deployment (Vercel)

See [the roadmap](https://github.com/Patrick-orz/PopupLyrics-Plus/projects?query=is%3Aopen) for more information.
## Dependencies
### [Spicetify](https://github.com/spicetify/spicetify-cli)
The extension PopupLyrics is based on the Spicetify-cli.

Spicetify installation steps are below (see [Spicetify docs](https://spicetify.app/docs/getting-started) for more details).
#### Windows
```iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex```
#### Linux and MacOS
```curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh```

### [Netease API](https://github.com/Binaryify/NeteaseCloudMusicApi)
The improved netease fetch requires an API to be hosted locally (online hosting coming soon).

Hosting steps are below (see [NeteaseAPI docs](https://binaryify.github.io/NeteaseCloudMusicApi/#/?id=%e5%ae%89%e8%a3%85) for more details).
#### Installation
```
git clone git@github.com:Binaryify/NeteaseCloudMusicApi.git
cd NeteaseCloudMusicApi
npm install
```
#### Hosting
In the NeteaseCloudMusicApi directory: 
```
node app.js
```
The server has to be running at http://localhost:3000 (the default port) when using the extensions and apps, don't close it!

## Installation
Download popupLyrics.js from this repo (not from /Archive!!), and place into the Spicetify Extensions directory.

Spicetify path are below.
|Platform|Path|
---------|-----
|Windows|%appdata%\spicetify\|
|Linux/MacOS|~/.config/spicetify|

## Usage
After hosting the API locally at http://localhost:3000, check the NeteaseCN service to enable it.

<img width="382" alt="Screen Shot 2023-09-14 at 11 50 25 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/f0615ed0-1092-4a1f-bb91-ae936a1d67fd">

Translation options can be changed in the Options section (needs to close and reopen PopupLyrics for it to take effect

<img width="389" alt="Screen Shot 2023-09-14 at 11 51 25 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/9bafe94e-bbc2-4b01-83ef-dd0a8c806922">

## Inspiration
[misaka10843/spicetify-popupLyrics-CN](https://github.com/misaka10843/spicetify-popupLyrics-CN)
