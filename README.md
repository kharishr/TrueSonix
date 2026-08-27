<div align="center">
  
# 🎧 TrueSonix 
**The Precision Audiophile Library Manager & Diagnostic Tool**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgray)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

> *Fun Fact: TrueSonix was conceptualized, designed, and fully coded over a single weekend using AI Pair Programming!*

TrueSonix is a powerful desktop utility designed to deep-scan, diagnose, and curate massive music libraries. Built for audiophiles who demand perfect metadata and audio fidelity, TrueSonix analyzes tracks for clipping, calculates LUFS ReplayGain, spots "fake" upscaled lossless files, and provides an entire suite of bulk-tagging tools.

---

## ✨ Key Features

* 🔍 **Deep Audio Diagnostics:** Decodes audio waveforms to calculate True Peak, clipping percentage, LUFS ReplayGain, and Dynamic Range (TT-DR and LRA).
* 🚨 **Lossless Authenticity Scanner:** Automatically detects frequency cutoffs to expose lossy files (like 128kbps MP3s) that have been falsely upscaled into FLAC or WAV formats. Right-click a track to view a generated **Frequency Spectrogram**.
* 🧹 **Unified Entity Manager:** A dedicated tool to clean up messy Artist, Composer, and Lyricist tags. Features a **Fuzzy Spell Checker** (to easily merge "AR Rahman" and "A.R. Rahman") and a smart tool to split combined artists.
* 🏷️ **Intelligent Tag Studio:** A massive bulk-editor for text fields (Genre, Album, Year, etc.). Includes Find & Replace, Overwrite, Append, Prefix, and quick-formatting (Title Case, Trim Spaces).
* 🎚️ **Global Gain Override:** Manually shift the ReplayGain of a batch of tracks to match a specific baseline volume. Includes an "Auto-Fix" safety limiter to prevent clipping.
* 💾 **Universal Compatibility:** Built with a brute-force ID3v2.3 saving mechanism, ensuring that tags saved to `.wav`, `.flac`, and `.mp3` files are 100% visible across Windows and all media players.

---

## 🚀 Getting Started (No Installation Required)

TrueSonix is packaged as a standalone executable. 

1. Go to the [Releases page](../../releases) on this GitHub repository.
2. Download the latest `TrueSonix.exe` file.
3. Double-click the `.exe` to run the application (no installation necessary).

---

## 📖 Quick Usage Guide

### 1. Scanning Your Library
* **Folder:** Click in the top-left to select your music directory.
* **Fast Scan:** Instantly reads existing ID3/FLAC metadata without opening the audio waveform.
* **Deep Analyze:** Processes the actual audio files to calculate ReplayGain, True Peak, and check for upscaled fakes. *(Note: Takes longer on large libraries).*

### 2. Filtering & Viewing Data
* **Filter:** Select specific folders on the left pane to instantly filter the Diagnostics Table.
* **Quick Filter:** Right-click any column header to quickly filter by specific genres, albums, or dynamic range scores. 
* **Spectrogram:** Right-click any track in the table to view its full technical specifications or generate a visual Spectrogram.

### 3. Fixing Tags & Volume
* **Save Tags:** Highlight multiple tracks and select to embed the calculated ReplayGain and DR metrics directly into the files.
* **Fix artist info:** Open the Master-Detail entity manager to clean up spelling mistakes across your library.
* **Tag Studio:** Mass-update genres, albums, and years.

---

## 📸 Screenshots

*(Tip: Drag and drop your screenshots directly into the GitHub editor below these headers to upload them!)*

**The Diagnostics Dashboard**
<!-- Drop image here -->

**Detecting Upscaled Fakes (Spectrogram)**
<!-- Drop image here -->

**Unified Entity Manager**
<!-- Drop image here -->

**Tag Studio**
<!-- Drop image here -->

---

## 🛠️ Under the Hood
For developers curious about the stack, TrueSonix is written in **Python 3** and utilizes:
* `tkinter` / `sv_ttk` for the GUI.
* `mutagen` for robust audio metadata read/write operations.
* `soundfile` and `numpy` for fast audio decoding and matrix operations.
* `pyloudnorm` for ITU-R BS.1770-4 loudness compliance.
* `matplotlib` for plotting frequency spectrums.

---

## 🤝 Feedback & Contributions
If you encounter a bug, have a feature request, or just want to say hi, feel free to open an **Issue** on this repository!
