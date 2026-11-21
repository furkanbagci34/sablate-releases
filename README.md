<p align="center"><img src="https://sablate.com/icon-512.png" width="96" height="96" alt="Sablate icon"></p>

# Sablate: offline subtitle generator for Windows and macOS

Sablate makes subtitles for your videos on your own computer. It transcribes speech with Whisper, translates the subtitles into other languages, styles them and burns them into the video, with no upload. It runs on Windows and Mac.

**[Download Sablate](https://sablate.com/download)** · [Latest release](https://github.com/furkanbagci34/sablate-releases/releases/latest) · [Microsoft Store](https://apps.microsoft.com/detail/9pl1t4r72x32) · [User guide](https://sablate.com/docs) · [Release notes](https://sablate.com/changelog) · [Website](https://sablate.com)

<img src="https://sablate.com/docs/en/13-editor-shell@2x.webp" alt="Sablate's editor: an English transcript made with Local Whisper, Spanish and Turkish translations made offline with Argos, and the subtitle over the video with the timeline below">

## What Sablate does

- **Transcribe video and audio into subtitles.** Whisper runs on your computer and recognizes 100 spoken languages, detecting the language for you. It uses an NVIDIA graphics card on Windows and the graphics chip on Apple silicon Macs, and falls back to the processor.
- **Translate subtitles into other languages.** Each translation is a separate layer of the same job. Argos translates fully offline; DeepL, OpenAI and Claude work with your own API key.
- **Edit subtitles in a real editor.** Retime lines on the timeline, split and merge them, find and replace, keep a glossary of terms, and import `.srt` and `.vtt` files.
- **Style captions with 13 presets.** Hormozi, Beast, Reels, One Word, Karaoke (word by word), Pop, Classic, Podcast, Creator, Highlighter, Impact, Minimal and Cinema, framed for 16:9, 9:16 or 1:1.
- **Burn subtitles into the video.** Export an `.mp4` with the subtitles burned in, or subtitle files: `.srt`, `.vtt`, `.txt`, `.ass`, and an `.mkv` with one subtitle track per language.
- **Cut the silences.** Cuts removes the parts where nobody speaks and filler sounds such as "um" and "uh", and the subtitles stay in sync with the cut video.
- **Clean up the voice.** Turns down fan, traffic and room hum in your exports, with Light and Strong settings, and can export just the audio as `.m4a`.

Sablate gives you four Whisper models to choose from:

| Model | Whisper model | Plan |
|---|---|---|
| Fast | tiny | Free and Pro |
| Balanced | small | Free and Pro |
| Accurate | large-v3-turbo | Pro |
| Best | large-v3 | Pro |

<img src="https://sablate.com/docs/en/21-style-panel@2x.webp" alt="Sablate's style panel: frame choices for 9:16, 1:1 and 16:9 and caption presets such as Hormozi, Beast, Reels, One Word, Karaoke and Pop, next to the video preview">

## Free and Pro

- **Free**, with no account: videos up to 10 minutes, 3 transcription jobs a month, the Fast and Balanced models, one offline translation layer, the full editor and GPU acceleration. Subtitle files carry a small Sablate credit line, and burned-in videos a small corner mark.
- **Pro**, $29 once: unlimited length and jobs, every Whisper model, cloud providers with your own key, unmarked burn-in, `.ass` and `.mkv` export, batch jobs and one-click export of every language, word-level editing and karaoke, and custom presets. Buy Pro once — every Pro update free for life. Pro Monthly is $5.99 a month. See [pricing](https://sablate.com/pricing).

## Works offline

The speech models and Argos language packs download once; after that, transcription, offline translation and burn-in run without an internet connection. Pro needs a connection once, to activate your license key; after that the app checks the license about once a day when it is online, and Pro keeps working when it is not. Your audio and video stay on your computer unless you turn on a cloud provider yourself.

## Download and system requirements

| Platform | File | Requirements |
|---|---|---|
| Windows | `Sablate-Setup-<version>.exe` (installer) or `Sablate-Portable-<version>.exe` | Windows 10 or 11, 64-bit |
| macOS | `Sablate-<version>-arm64.dmg` (Apple silicon) or `Sablate-<version>-x64.dmg` (Intel) | macOS 12 Monterey or later |

Download from [sablate.com/download](https://sablate.com/download), the [latest release](https://github.com/furkanbagci34/sablate-releases/releases/latest) here, or the [Microsoft Store](https://apps.microsoft.com/detail/9pl1t4r72x32). The speech models are downloaded inside the app when you first need them. The app checks this repository for updates.

The interface is in English and Turkish. Subtitles can be made in 100 languages.

## Coming from Subtitle Edit, Submagic or MacWhisper?

Online caption tools such as Submagic and VEED work on an uploaded copy of your video. Sablate makes the same kind of styled captions on your own computer, with no subscription required. If you use Subtitle Edit or another Whisper app, Sablate adds translation layers, caption presets and burn-in in one place. The [comparison of offline subtitle generators](https://sablate.com/blog/offline-subtitle-generators) goes through the options, and there are side-by-side pages for [Submagic](https://sablate.com/blog/submagic-alternative), [VEED](https://sablate.com/blog/veed-alternative), [Descript](https://sablate.com/blog/descript-alternative) and [MacWhisper on Windows](https://sablate.com/blog/macwhisper-alternative-windows).

## About this repository

This repository holds Sablate's release builds and the update feed the app reads. The source code is not public. For questions and bug reports, use [sablate.com/support](https://sablate.com/support).
