# PopupLyrics-Plus
### Modded Spiceify [PopupLyrics](https://github.com/spicetify/cli/blob/main/Extensions/popupLyrics.js) to enable translations and more! 拥有翻译和更多功能的PopupLyrics~

<img width="751" alt="Screen Shot 2023-09-17 at 12 09 43 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/a7acaa19-e042-463f-9f0f-1ef6d1c9999d">

*Chinese translation*

<img width="751" alt="Screen Shot 2023-09-17 at 12 10 47 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/d670ce66-cb20-4683-86c4-eaf81e43cc0e">

*English translation*

<img width="751" alt="Screen Shot 2023-09-17 at 12 11 02 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/d5633ea9-10d7-4410-822d-01d84304774f">

*Japanese Romaji translation*

<img width="751" alt="Screen Shot 2023-09-17 at 12 11 14 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/05885cad-e681-4dd9-be57-1bed21ac8752">

*Original*

<img width="682" alt="Screen Shot 2024-04-20 at 11 44 41 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/bcabf2fb-c18d-4a87-aed6-1997bca08e4f">

*Chinese PinYin translation*

<img width="682" alt="Screen Shot 2024-04-20 at 11 46 41 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/09dd6637-3250-4084-a6e3-32ecc53273e8">

*Korean Romanja translation*

## ADDITIONAL Features
- Stabler self-deployed [Netease API](https://github.com/Binaryify/NeteaseCloudMusicApi) to fetch from, allowing Netease lyrics to actually work
- Netease Chinese lyrics translation option
- ~~English translation through [Translateer](https://github.com/Songkeys/Translateer) (EXPERIMENTAL)~~
- English translation through self-deployed modded [DeepTranslatorApi](https://github.com/nidhaloff/deep-translator-api)
    - Can be slow via first translation as API has to awake. Be patient on startup!
- Japanese romaji translation
- Korean romaja translation ([#7](https://github.com/Patrick-orz/PopupLyrics-Plus/pull/7))
- Chinese PinYin translation ([#10](https://github.com/Patrick-orz/PopupLyrics-Plus/pull/10))
## Work in Progress
- More options in display
- Language detection
- ~~Chinese & Korean romanization (MERGED [#7](https://github.com/Patrick-orz/PopupLyrics-Plus/pull/7))~~
- ~~Enhance & stabilize English translation (DONE to best of ability)~~
- ~~Online hosting (DONE)~~

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
A still up and running [online deployed version](https://netease-cloud-music-api-patrick-orz.vercel.app/) is used by default. (RIP repo...🙏)

If you would like to **self-host** for a possibly more stable api connection, instructions are below (see [NeteaseAPI docs](https://binaryify.github.io/NeteaseCloudMusicApi/#/?id=%e5%ae%89%e8%a3%85) for more details).

You can also deploy to vercel yourself, check the official docs for instructions.
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
Self-hosting means that the server has to be running at http://localhost:3000 (the default port) when using the extension, don't close it!

#### Applying Change
Last, in order for you to use the locally hosted api for fetching, change all instances of "https://netease-cloud-music-api-patrick-orz.vercel.app/" in the source code into "http://localhost:3000/".

## Installation
Download [popupLyricsPlus.js](https://github.com/Patrick-orz/PopupLyrics-Plus/blob/main/popupLyricsPlus.js) from the main branch (not from /Archive!!), and place into the Spicetify Extensions directory.

Spicetify paths are below.
|Platform|Path|
---------|-----
|Windows|%appdata%\spicetify|
|Linux/MacOS|~/.config/spicetify|

Push extension into Spicetify and apply

```
spicetify config extensions popupLyricsPlus.js
spicetify apply
```


## Usage

**Have NeteaseCN service at the top to acquire the best experience!**

<img width="400" alt="Screen Shot 2023-09-17 at 12 11 53 AM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/47c52793-572c-45f1-97f5-f86cd4705f44">

Translation options can be changed in the Options section

<img width="402" alt="Screen Shot 2024-04-20 at 11 54 22 PM" src="https://github.com/Patrick-orz/PopupLyrics-Plus/assets/132706084/7d0b21a4-42ff-4a44-8087-3a58c0437f21">

## Inspiration & Words
[misaka10843/spicetify-popupLyrics-CN](https://github.com/misaka10843/spicetify-popupLyrics-CN)

Self-deployed APIs: [NeteaseCloudMusicApi](https://netease-cloud-music-api-patrick-orz.vercel.app/) [DeepTranslatorApi](https://deep-translator-api.onrender.com)

Don't heisitate to start an issue if you run into any problems! (feature requests are fine as well)

🌟 means a lot to me!
