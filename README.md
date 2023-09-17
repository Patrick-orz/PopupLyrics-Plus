# PopupLyrics-Plus
### Modded Spiceify [PopupLyrics](https://github.com/spicetify/spicetify-cli/tree/master/CustomApps/lyrics-plus) to enable translations and more! 拥有翻译和更多功能的PopupLyrics~

*Chinese translation*

<img width="751" alt="Screen Shot 2023-09-17 at 12 09 43 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/a7acaa19-e042-463f-9f0f-1ef6d1c9999d">

*English translation*

<img width="751" alt="Screen Shot 2023-09-17 at 12 10 47 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/d670ce66-cb20-4683-86c4-eaf81e43cc0e">

*Romaji translation*

<img width="751" alt="Screen Shot 2023-09-17 at 12 11 02 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/d5633ea9-10d7-4410-822d-01d84304774f">

*Original*

<img width="751" alt="Screen Shot 2023-09-17 at 12 11 14 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/05885cad-e681-4dd9-be57-1bed21ac8752">

## Features
- Way more stable [Netease API](https://github.com/Binaryify/NeteaseCloudMusicApi) to fetch from, allowing Netease lyrics to actually work
- Netease Chinese lyrics translation
- English translation through [SimplyTranslate Web](https://codeberg.org/SimpleWeb/SimplyTranslate-Web) (a bit slow)
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
The server has to be running at http://localhost:3000 (the default port) when using the extension, don't close it!

## Installation
Download [popupLyrics.js]([https://github.com/Patrick-orz/PopupLyrics-Plus/blob/main/popupLyrics.js) from this repo (not from /Archive!!), and place into the Spicetify Extensions directory.

Spicetify path are below.
|Platform|Path|
---------|-----
|Windows|%appdata%\spicetify\|
|Linux/MacOS|~/.config/spicetify|

Push extension into Spicetify and apply

```
spicetify config extensions popuplyrics.js
spicetify apply
```

## Usage
Host the Netease API locally at http://localhost:3000.

**Have NeteaseCN service at the top to have the best experience!**

<img width="400" alt="Screen Shot 2023-09-17 at 12 11 53 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/47c52793-572c-45f1-97f5-f86cd4705f44">

Translation options can be changed in the Options section

<img width="395" alt="Screen Shot 2023-09-17 at 12 12 13 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/b16a1b42-2bd7-41e8-9c0a-6a730480ec46">

## Inspiration & Words
[misaka10843/spicetify-popupLyrics-CN](https://github.com/misaka10843/spicetify-popupLyrics-CN)

Don't heisitate to start an issue if you run into any problems! (feature requests are fine as well)
