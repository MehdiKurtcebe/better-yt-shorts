<div align="center">

![BYS Icon](./src/assets/icons/bys-128.png)

# Better YouTube Shorts v3

![Current Version](https://img.shields.io/amo/v/better-youtube-shorts?label=version)
[![Chrome Web Store users](https://img.shields.io/chrome-web-store/users/icnidlkdlledahfgejnagmhgaeijokcp?label=chrome)](https://chrome.google.com/webstore/detail/better-youtube-shorts/icnidlkdlledahfgejnagmhgaeijokcp)
[![Firefox Add-on users](https://img.shields.io/amo/users/better-youtube-shorts?label=firefox)](https://addons.mozilla.org/en-US/firefox/addon/better-youtube-shorts)
![Chrome Web Store](https://img.shields.io/chrome-web-store/rating/icnidlkdlledahfgejnagmhgaeijokcp)
![License: MIT](https://img.shields.io/github/license/ynshung/better-yt-shorts)
</div>

Control your YouTube shorts just like a normal YouTube video! Features include progress bar, seeking, playback speed, auto skip and more. You can also customize the keybinds to your liking!

## ⚠️ Development Notice
This branch is currently a work in progress and there are countless unimplemented/broken features that have yet to be addressed.

View the [roadmap](./ROADMAP.md) for a list of development goals.

---
### Development Guide
1. Fork the project on Github
2. Clone your fork
3. Open the working directory in the terminal
4. run `npm i` to install all dependencies (ensure [node and npm are installed](https://nodejs.org/en))
5. Once finished, run `npm run dev` to start developing. It will also create the distribution (dist)
6. Open Chrome, and type `chrome://extensions` in the searchbar
7. Toggle `Developer Mode` with the switch at the top-right of that page
8. Drag and drop the `dist` directory into that page to load the unpacked extension

Note that the content script will only work on the shorts page of youtube, though the popup should work anywhere.

Also note that, so long as the `npm run dev` is active, the extension will automatically update and refresh.

## Installation

* Firefox Add-on: https://addons.mozilla.org/en-US/firefox/addon/better-youtube-shorts

## Features
* **Progress bar** at the bottom with time and duration
* **Seeking** 5 seconds backward and forward with arrow keys
* **Auto skip** short when current one ends
* Auto skip short with likes below custom threshold (e.g. 500 likes)
* Auto open comment section on each short
* Decrease and increase **playback speed** with keys U and O
* Revert to normal speed with I or by clicking the speed button
* Control **volume** with the volume slider or with - and =, mute audio with M
* Mini timestamp and speed above the like button (can be scrolled on!)
* Navigate to next or previous short **without animation** with W and S
* Go to the next **frame** or previous frame with . and , while paused
* **Customizable** keybinds

### Default Keybinds
| Action               | Shortcut   |
|----------------------|------------|
| Seek Backward (+5s)  | ArrowLeft  |
| Seek Forward (-5s)   | ArrowRight |
| Decrease Speed       | KeyU       |
| Reset Speed          | KeyI       |
| Increase Speed       | KeyO       |
| Decrease Volume      | Minus      |
| Increase Volume      | Equal      |
| Toggle Mute          | KeyM       |
| Next Frame           | Comma      |
| Previous Frame       | Period     |
| Next Short           | KeyS       |
| Previous Short       | KeyW       |

## Screenshots

![image](https://user-images.githubusercontent.com/80070435/219866197-2401c0d0-2632-45ed-9152-f1024828f46f.png)
![image](https://user-images.githubusercontent.com/80070435/219866370-d1acbd50-049b-47ef-9688-19d1dc4efe91.png)
![image](https://user-images.githubusercontent.com/80070435/219866388-13770811-674d-4681-be32-c7d27f35c000.png)

## Issues / Suggestion
If you faced any issue with the extension or any suggestion that can help to improve the extension, you may create an issue [here](https://github.com/ynshung/better-yt-shorts/issues) or if you know how to code, fork the repo, make the necessary changes and create a pull request.

You may leave your feedback in this [Google Form](https://forms.gle/pvSiMwDeQVfwyALfA).

## License

MIT License
