<div align="center">

# Liquify

**A glass-inspired Spotify theme with rounded controls and custom video backgrounds.**

[![Spotify 1.3.6](https://img.shields.io/badge/Spotify-1.3.6-1DB954?logo=spotify&logoColor=white)](https://www.spotify.com/download/)
[![Spicetify](https://img.shields.io/badge/Spicetify-2.45.3-F5C2E7)](https://spicetify.app/)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue)](LICENSE.txt)

[Installation](#installation) · [Video backgrounds](#video-backgrounds) · [Credits](#credits)

</div>

> **Originally created by [NMW](https://github.com/NMWplays).**
> This community fork, maintained by [kr1zk](https://github.com/kr1zk), adds local video backgrounds and interface fixes for Spotify 1.3.6.1921.g7086c071a617.
> Visit the [original Liquify repository](https://github.com/NMWplays/Liquify) for NMW's work.


*Preview from the original Liquify theme by NMW. This fork includes the additions described below.*


## Features

**Liquify offers:**

- Many customization options
-  `Beatiful Lyrics`, `Spicy Lyrics` and `Lucid Lyrics` are supported by default
- Video backgrounds
- Beautiful dynamic colors (Just enable dynamic button colors in the settings and your good to go)
- Modern, rounded UI
- And much more!

***⚠️IMPORTANT: TO MAKE YOUR THEME WORK PERFECTLY, YOU NEED TO INSTALL LIQUID LYRICS FROM SPICETIFY MARKETPLACE, OR DIRECTLY FROM [LIQUIFY LYRICS](https://github.com/NMWplays/Liquid-Lyrics) GITHUB.***

## Theme screenshots

<details>
<summary>Click to watch screenshots</summary>
<img width="1919" height="1029" alt="Homescreen" src="https://github.com/user-attachments/assets/a7d50e6e-56be-4a8b-8ea6-8835655d4cdf" />

<img width="1919" height="1029" alt="Playlist" src="https://github.com/user-attachments/assets/5375a463-10a4-428e-8e5c-f43d76e03509" />

<img width="1919" height="1030" alt="Search" src="https://github.com/user-attachments/assets/71d1c7a5-bca6-47d3-880c-8c0e85c45bce" />

<img width="1919" height="1030" alt="Artist-Page" src="https://github.com/user-attachments/assets/60151e06-8a6a-4548-a882-1c267c18e7ca" />

<img width="1919" height="1028" alt="Artist-Page2" src="https://github.com/user-attachments/assets/fa9bdb4f-666e-4380-9ee3-2da6b33be730" />

<img width="1919" height="1030" alt="Liquify-Settings" src="https://github.com/user-attachments/assets/0ab96146-4868-468c-8a22-7cb03fa992c1" />

<img width="1919" height="1030" alt="Popup" src="https://github.com/user-attachments/assets/59b2f2e9-b273-4f2a-9d06-7e562be21f8d" />

<img width="1919" height="1029" alt="Settings" src="https://github.com/user-attachments/assets/f37cfbef-7d3e-4ed4-bab5-0dfeae4362aa" />

<img width="1919" height="1030" alt="Fullscreen" src="https://github.com/user-attachments/assets/7b147a4f-6f48-4123-bf65-96b4a94d44e0" />

</details>




## Installation

You need the **Spotify desktop app** and [Spicetify](https://spicetify.app/). This fork targets **Spotify 1.3.6** with **Spicetify 2.45.3**.

1. [Download this fork](https://github.com/kr1zk/Liquify/archive/refs/heads/main.zip) and extract it.
2. Place the extracted folder in your Spicetify `Themes` directory and name it `Liquify-main`:

   | Platform | Themes directory |
   | --- | --- |
   | Windows | `%APPDATA%\spicetify\Themes\` |
   | Linux / macOS | `~/.config/spicetify/Themes/` |

   The folder should contain `color.ini`, `user.css`, `theme.js`, and the complete `assets` directory. Keep the assets included: they provide local video conversion.

3. Run these commands in your terminal:

   ```shell
   spicetify config current_theme Liquify-main
   spicetify apply
   ```

Open **Liquify Settings** in Spotify to customize the theme.

<details>
<summary><strong>Updating an existing installation</strong></summary>

Replace the theme files and the `assets` directory with the latest files from this fork, then run `spicetify apply` again.

</details>

## Video backgrounds

Give Spotify an animated background using a video from your computer.

1. Open **Liquify Settings → Background → Custom**.
2. Under **Background Library**, click **Add photos or videos** and select an MP4 or WebM file.
3. Click its thumbnail to activate it, then adjust **Background Blur** and **Background Brightness**.

Videos loop without sound, and your selected background is saved between sessions. Photos are still supported.

Two optional controls let you pause the background:

- **Pause video when Spotify is not the active window**
- **Pause video when music is paused**

Video playback always pauses while the Spotify window is hidden.

<details>
<summary><strong>Formats, conversion, and saved backgrounds</strong></summary>

- Compatible MP4 and WebM files play directly. MP4 files that Spotify cannot decode are automatically converted to WebM using the bundled converter.
- Conversion runs locally on your computer. Your video is not uploaded, and the original file is left unchanged.
- Automatic conversion accepts MP4 files up to **256 MiB** and produces video at up to **1080p / 30 FPS**.
- Background photos and videos are stored locally. They are not included when exporting your theme configuration, so import them separately on another device.

</details>

## Credits

- **[NMW](https://github.com/NMWplays)** — creator of the [original Liquify theme](https://github.com/NMWplays/Liquify).
- **[kr1zk](https://github.com/kr1zk)** — maintenance of this fork, compatibility fixes, and video background support.
- **[Sanoojes](https://github.com/sanoojes)** — creator of [Glassify](https://github.com/sanoojes/spicetify-glassify), which inspired Liquify.
- **[Spicetify](https://spicetify.app/)** — the customization framework that makes this theme possible.

Original Liquify community: [Discord](https://discord.gg/QRMnrgjhvq).

## License

Distributed under the [GNU Affero General Public License v3.0](LICENSE.txt).

The bundled video converter includes third-party components with their own licenses and source references in [`assets/liquify-video`](assets/liquify-video/).
