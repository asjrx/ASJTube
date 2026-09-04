<div align="center">

<img src="icon/icon.png" width="110" alt="ASJTube">

# ASJTube

**Downloads, background audio and an ad-free YouTube — without changing how the app looks.**

<sub>79 languages</sub>

Add the source in Sileo, Zebra, Cydia or Installer:

```
https://asjrx.github.io/
```

[**ASJ Tweaks on Telegram**](https://t.me/ASJTweaks) — new tweaks and update notes

</div>

---

## Where it lives

One place: an **ASJTube** tab in YouTube's own bar. The settings, the library and everything else are behind it — no floating buttons, no gestures to learn.

<p align="center">
  <img src="screenshots/settings.png" width="31%" alt="The ASJTube tab">
  <img src="screenshots/library.png" width="31%" alt="My Library">
  <img src="screenshots/quality.png" width="31%" alt="Choosing a quality to save">
</p>

Saving works from four places: the button in the row under the video, a long press on the player, the button on a Short, and YouTube's own Download row.

---

## Features

### Downloads
<img src="screenshots/quality.png" width="30%" align="right" alt="The quality sheet">

- **Save any video or Short** — every rung the video has, with the size before you commit
- **My Library** — a feed of what you saved, laid out like Home
- **Playlists**, **Watch later** and a **storage bar**
- Background playback and Picture in Picture for your own files

<br clear="right">

### Playback
<img src="screenshots/player.png" width="30%" align="right" alt="The library player">

- **Watch videos in high quality** — pinned to the best rendition the video has
- **Background Playback** — audio keeps going when you leave the app or lock the screen
- **Picture in Picture** — starts on its own, no button to press
- **Autoplay when a video finishes**, and no suggested grid at the end
- **Progress bar in Shorts**

<br clear="right">

### Ads
<img src="screenshots/shorts.png" width="30%" align="right" alt="The save button on a Short">

- **Remove Ads** — feed, search, Shorts and the player alike
- An ad is refused at the model, before a card is ever built, so there is no flash and no gap
- Non-skippable breaks are seeked past; skippable ones are skipped the moment the app allows it
- The Premium prompts, the upsell panels and the in-app surveys are all declined

<br clear="right">

### Extras
<img src="screenshots/clear.png" width="30%" align="right" alt="Clear Mode on a Short">

- **Lyrics** for the song a video plays
- **Spoken translation** — dub a clip into another language, on the device
- **Clear Mode** — the whole interface out of the way on a Short
- **Copy text** from any label with a long press
- **Hide Shorts**, **hide the create button**, **open the app on Shorts**
- **Require Face ID to open**
- **Open links in Safari** instead of the in-app browser

<br clear="right">

**79 languages** — the panel follows YouTube's own language, so an Arabic install gets Arabic screens without setting anything. Right-to-left languages mirror with the text.

---

## Install

### Jailbroken

Add the source above, or download a package from [Releases](../../releases) and install it with Sileo, Zebra or Cydia.

| Jailbreak | Package |
|---|---|
| Dopamine / palera1n (rootless) | `ASJTube` — `iphoneos-arm64` |
| checkra1n / unc0ver and similar (rootful) | `ASJTube` — `iphoneos-arm` |
| roothide | `ASJTube (roothide)` |

Sileo, Zebra and Cydia pick the right architecture on their own; roothide is a separate entry.

### TrollStore

Fully supported, with a build of its own that keeps YouTube's own entitlements and its app extensions intact.

**[asjrx.github.io/trollstore/tube](https://asjrx.github.io/trollstore/tube)** — iOS 14.0–16.6.1, and 17.0 on some devices.

One link: on an iPhone with TrollStore it hands the file straight over, anywhere else it just downloads.

### Not jailbroken, no TrollStore

Download `ASJTube-1.0_21.32.4.ipa` from [Releases](../../releases) and sign it with Sideloadly or eSign — or take `ASJTube-1.0_21.32.4.dylib` and inject it into your own copy of YouTube.

> The dylib is self-contained and does not need Cydia Substrate, so any injector works.
> YouTube itself is not distributed here — bring your own copy.

---

## Notes

- Built against YouTube **21.32.4**
- arm64 and arm64e
- Screenshots are from a real install, not mockups

<div align="center"><sub>by <a href="https://github.com/asjrx">ASJRX</a></sub></div>
