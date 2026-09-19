# Credits

## The music

**Greensleeves** — traditional English melody, in circulation since the 16th century.
**Public domain.** No copyright is claimed in the melody itself.

**Arrangement, orchestration, realisation and recording** — © 2026 OneZion.
**All rights reserved.** See [LICENSE](LICENSE).

Nine orchestrations were written from one score and rendered to audio for this collection. No
third-party recording, commercial master, sample library or licensed music appears anywhere in it.
Nothing is quoted from any existing recording.

## How the audio was made

1. **Score.** All nine arrangements derive from a single machine-readable model of the tune: the
   same note events, the same 22-bar grid in 6/8, the same tempo. Only the orchestration differs,
   which is why any two tracks can be swapped without the timing moving.
2. **Parts to MIDI.** Each arrangement's parts were written out as a Standard MIDI File, one file
   per arrangement — those are the files in `midi/`.
3. **Synthesis.** `fluidsynth` rendered each MIDI through the **MuseScore_General** soundfont.
4. **Mixing and mastering.** `ffmpeg` applied per-arrangement tone shaping, then one shared
   loudness target across all nine (`loudnorm I=-16:TP=-1.5:LRA=11`, 44.1 kHz, 16-bit stereo).
5. **Encode.** `ffmpeg` encoded the listening copies at 192 kbps MP3.

The pipeline itself — the generator, the score parser, the orchestration code — is **not
published** and is not open source. It is not part of this repository.

## Third-party notices

### MuseScore_General soundfont

The recordings were synthesised with the MuseScore_General soundfont (v0.2). That soundfont is
**not** included in this repository and is not redistributed here.

The soundfont's own embedded metadata records:

```
INAM  MuseScore_General v0.2
IENG  Frank Wen, Michael Cowgill & S. Christian Collins - see license file for details
ICOP  Frank Wen 2000-02, Michael Cowgill 2014-17, S. Christian Collins 2018-20
ICMT  Released under the MIT license. Please see "MuseScore_General-License.md" for more information.
```

Copyright © Frank Wen 2000–2002, Michael Cowgill 2014–2017, S. Christian Collins 2018–2020.
Released under the **MIT licence**. Under the MIT terms, the copyright notice and the permission
notice must be retained wherever the work — or a substantial portion of it — is redistributed.
Both are reproduced here. The full licence text ships with the soundfont as
`MuseScore_General-License.md`; the soundfont is available from the MuseScore project at
<https://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General.sf3>.

The MIT permission notice, in its standard form:

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software
> and associated documentation files (the "Software"), to deal in the Software without
> restriction, including without limitation the rights to use, copy, modify, merge, publish,
> distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the
> Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or
> substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING
> BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
> NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
> DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

This notice concerns the soundfont as a piece of software. It does not place the Recordings in
this repository under the MIT licence: the Recordings remain **all rights reserved**, as stated in
[LICENSE](LICENSE).

### Tools

- **FluidSynth** — © 2000–2023 Peter Hanappe and others — GNU LGPL v2.1. Used as a renderer.
- **FFmpeg** — © the FFmpeg developers — LGPL/GPL. Used as a mixing and encoding tool.

Both are used as tools; their licences govern the programs, not the audio they produced.
