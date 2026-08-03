# Audio Cue Mapper v2026 - audio analysis tool 2026

> **Map sync cues from audio in the browser for animation pipelines: local analysis, waveform review, and After Effects export in v2026.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nlambert45/audio-cue-mapper-sync?style=flat-square)](https://github.com/nlambert45/audio-cue-mapper-sync)

---

<p align="center">
  <a href="https://nlambert45.github.io/audio-cue-mapper-sync/">
    <img src="https://img.shields.io/badge/Download-Audio%20Cue%20Mapper%20Latest-brightgreen?style=for-the-badge" alt="Download Audio Cue Mapper">
  </a>
</p>

> **[Download Latest Build - Audio Cue Mapper v2026](https://nlambert45.github.io/audio-cue-mapper-sync/)**

---

[Download Latest Build](https://nlambert45.github.io/audio-cue-mapper-sync/)

---

## What Audio Cue Mapper Is

Audio Cue Mapper runs in the browser and targets jobs where hit points and timing matter more than heavy offline suites. Load media, study the waveform, mark strong moments, and shape that material into cues you can hand off to animation or edit work—without installing a desktop analyzer.

Everything stays on the client. You get onset work, tempo insight, and exportable cue data in one place, so raw files become structured timing you can act on.

---

## What You Get

- Audio and video review entirely in the browser
- Waveform views built for cue hunting
- Onset detection via spectral flux
- Peak picking with cues grouped by tier
- Structural segmentation for longer pieces
- Tempo estimates when rhythm drives the cut
- JSX export aimed at After Effects
- Fully local processing on the client

---

## Getting It Running

1. Grab or clone the repo:
   - `git clone https://github.com/nlambert45/audio-cue-mapper-sync.git
2. Open the project in any setup that can load web pages, or put it behind a local static server you already use.
3. Start from the main HTML file in the project root.

With a static server, bring the server up first, then open the app in the browser. The design assumes local client execution.

---

## How You Work With It

1. Bring an audio or video file into the UI.
2. Use the waveform to locate anchors and likely cue spots.
3. Check onset output, then tighten results with peak picking and tiers.
4. Apply segmentation and tempo estimation when you need a clearer read on form and pace.
5. Export cue data as After Effects JSX when timing is ready for motion work.

A common path:
- run analysis on the machine
- lock in cue placements
- tune timing relationships
- ship JSX into After Effects

---

## Configuration

Session behavior lives in the browser. When settings exist, they usually sit in local app state or project-side files rather than on a remote config service.

Example configuration shape:

{
  "analysis": {
    "onsetDetection": true,
    "peakPicking": true,
    "segmentation": true,
    "tempoEstimation": true
  },
  "export": {
    "format": "after-effects-jsx"
  }
}

---

## Requirements

- A current browser that can handle client-side media work
- Ability to reach the audio or video files on your machine
- Memory and disk headroom matched to the clips you load
- A way to open or serve the HTML entry point

---

## FAQ

**Is processing fully browser-local?**  
Yes. The stack is built around client-side analysis.

**Which media types are in scope?**  
Browser-based audio and video analysis are supported.

**Is there a path into motion design tools?**  
Yes. After Effects JSX export is included.

**Load failures—where do I start?**  
Confirm browser version, file access, and how you are serving the app, then reload and retry.

**How do I pick up newer builds?**  
Pull the newest release or build from the project download link when you want the current version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
