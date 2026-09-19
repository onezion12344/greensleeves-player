# Greensleeves — Nine Orchestrations from One Score

**One traditional tune. Nine arrangements. One pipeline.**

Every track in this collection is generated from the *same* machine-readable score — the same
melody events, the same bar grid, the same tempo — and only the orchestration changes. Because
they share one rhythmic skeleton, any two versions can be swapped for each other without the
timing moving. That is the point of the experiment.

▶ **[Listen to all nine in the browser](https://onezion12344.github.io/greensleeves-player/)**

---

## The tracks

| # | Title | Length | Style | MP3 | WAV master |
|---|-------|--------|-------|-----|------------|
| 1 | **Strings & Harp** | 1:16 | Harp arpeggios rolling under a full string choir, with a solo flute tracing the tune an octave above. The classic reading, and the one the rest were built around. | [mp3](tracks/strings_harp.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/strings_harp.wav) |
| 2 | **Symphony** | 1:16 | The whole orchestra in the room: violins and violas divided, flutes and oboe overhead, horns in the middle, timpani marking the ground. | [mp3](tracks/symphony.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/symphony.wav) |
| 3 | **String Quartet** | 1:08 | Four players, no safety net — first violin takes the tune while viola and cello hold the repeating four-bar ground beneath it. | [mp3](tracks/string_quartet.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/string_quartet.wav) |
| 4 | **Harp Solo** | 1:16 | One harp doing three jobs at once: the tune in the upper register, arpeggios rolling underneath, and the bass line played by the thumb. | [mp3](tracks/harp_solo.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/harp_solo.wav) |
| 5 | **Organ & Choir** | 1:09 | Church registration — organ manuals, a wordless choir pad and pedal bass. Solemn, slow-breathing, and the oldest sound in the set. | [mp3](tracks/organ_choir.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/organ_choir.wav) |
| 6 | **Piano & Echo** | 1:09 | A single soft piano left wet with a two-tap echo. The quietest track here, and the one that sounds most like a memory. | [mp3](tracks/piano_echo.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/piano_echo.wav) |
| 7 | **Music Box & Celesta** | 1:09 | Music box and celesta over a barely-there string halo. The fairytale version — sized for a title card. | [mp3](tracks/music_box.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/music_box.wav) |
| 8 | **March** | 1:08 | Snare rudiments and a brass band: the tune squared off into a processional, with the clock left exactly where it was. | [mp3](tracks/march.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/march.wav) |
| 9 | **Soviet March** | 0:37 | Trumpets and cornets carrying the tune over block brass chords, tuba on the pulse and a rudimental snare. The only track that changes the tempo — and the only one that marches. | [mp3](tracks/soviet_march.mp3) | [wav](https://github.com/onezion12344/greensleeves-player/releases/download/v1.0.0/soviet_march.wav) |

Total running time: **10:13**.

**To listen:** the [player page](https://onezion12344.github.io/greensleeves-player/) plays all
nine in the browser, no download. **To keep:** every MP3 is an individual file in
[`tracks/`](tracks/), and every WAV master is a separate download in the
[v1.0.0 release](https://github.com/onezion12344/greensleeves-player/releases/tag/v1.0.0) —
there is no bundled archive, and nothing is zipped.

Each track is independently addressable — its own file path, its own download, and its own anchor
on the player page (`.../#soviet-march`, for example), so a video chapter can deep-link to one
track. The player page itself is [`index.html`](index.html) in this repository, published with
GitHub Pages; it works opened straight from disk too.

> The `wav` links in the table above point at release assets; use the
> [player page](https://onezion12344.github.io/greensleeves-player/) or the
> [v1.0.0 release](https://github.com/onezion12344/greensleeves-player/releases/tag/v1.0.0)
> for downloads.

---

## Where the files live

| Format | What it is | Where | Why there |
|--------|------------|-------|-----------|
| **MP3** (192 kbps) | Listening copy | `tracks/` — in the repository | Small enough for the player page to stream straight from the browser, so nobody has to download anything to hear a track |
| **WAV** (44.1 kHz / 16-bit stereo) | The masters, loudness-normalised | [Release v1.0.0](https://github.com/onezion12344/greensleeves-player/releases/tag/v1.0.0) — one asset per track | ~12–14 MB each. As release assets they stay individually downloadable without putting ~110 MB of audio into git history forever |
| **MIDI** | The written parts, one file per arrangement | `midi/` — in the repository | A few KB each; the clearest evidence that all nine come from the same score |

All nine tracks are normalised to one shared loudness target (`I=-16 LUFS`, true peak ≤ −1.5 dBFS),
so switching between them does not produce a level jump.

---

## Rights

**All rights reserved.** This is a public repository, not an open-source one.

- **Greensleeves** — traditional English melody (16th century), **public domain**. No copyright is
  claimed in the melody itself.
- **The arrangements, the realisations and the recordings** — **© 2026 OneZion. All rights reserved.**
- **No third-party recording is used.** No commercial music, no sample library, no licensed master.
  Every note here was synthesised for this project.
- The pipeline that generated these arrangements is **not published** and is not open source.
  Nothing in this repository grants any licence to it.

You are welcome to listen, to link to this page, and to download the tracks for your own private
listening. Redistribution, re-uploading, use in your own videos or products, sampling, remixing,
and use for machine-learning training are **not** permitted without written permission.

See **[LICENSE](LICENSE)** for the full terms and **[CREDITS.md](CREDITS.md)** for how the audio was
made and the third-party notices that ship with it.

---

## 中文

**一首传统曲调，九种配器，同一条流水线。**

这个合辑里的每一轨都来自**同一份机器可读的乐谱** —— 同样的旋律事件、同样的小节网格、同样的速度，
变的只有配器。因为九版共享同一个节奏骨架，任意两版都可以互换而不产生错位。这正是这次实验想验证的事。

- **在线试听（无需下载）**：<https://onezion12344.github.io/greensleeves-player/> —— 页面上九轨各带一个播放器。
- **九版目录**：见上表。每轨有独立链接、独立文件路径，视频分 P 可直接深链到单轨（如 `.../#soviet-march`）。
- **格式**：`tracks/` 是 MP3（192 kbps，可直接在浏览器播放）；WAV 母带（44.1 kHz / 16-bit）在
  [Release v1.0.0](https://github.com/onezion12344/greensleeves-player/releases/tag/v1.0.0) 里，**每轨单独一个附件**，没有打包压缩包；
  `midi/` 是每版的分谱 MIDI。
- **响度**：九版统一归一到一个目标（`I=-16 LUFS`，真峰值 ≤ −1.5 dBFS），互相切换不会跳音量。

### 版权声明

**保留所有权利（All rights reserved）。** 这是公开仓库，**不是开源项目**。

- **《Greensleeves》旋律**：16 世纪英格兰传统曲调，**公有领域**。旋律本身不主张版权。
- **配器、实现与录音**：**© 2026 OneZion，保留所有权利。**
- **未使用任何第三方录音** —— 没有商业唱片、没有采样库、没有授权母带，所有声音都是为本项目合成的。
- 生成这些版本的**流水线（skill）不开源**，本仓库不授予任何相关许可。

欢迎试听、链接、以及为个人收听而下载。**未获书面许可，不得**转载、搬运、二次上传、用于自己的视频或产品、
采样、改编，或用于机器学习训练。完整条款见 **[LICENSE](LICENSE)**，制作与第三方声明见 **[CREDITS.md](CREDITS.md)**。
