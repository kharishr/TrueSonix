<div align="center">
  
<!-- Replace the src link with the actual raw GitHub link to your icon if it doesn't load automatically -->
<img src="app_icon.png" width="80" alt="TrueSonix Logo">

# TrueSonix 
**The Precision Audiophile Library Manager & Diagnostic Tool**

<!-- Functionality Badges (Modern Sharp Edges) -->
![Audio Diagnostics](https://img.shields.io/badge/Audio_Diagnostics-0078D7?style=flat-square)
![Lossless Verification](https://img.shields.io/badge/Lossless_Verification-005A9E?style=flat-square)
![Metadata Curation](https://img.shields.io/badge/Metadata_Curation-003366?style=flat-square)

<!-- Tech Stack Badges (Classic Rounded Edges) -->
![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?logo=python&logoColor=white&style=flat)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white&style=flat)
![License](https://img.shields.io/badge/License-MIT-4CAF50?style=flat)
</div>

> **The Origin Story:** I built TrueSonix out of pure frustration. I had thousands of audio files that needed serious curation, but existing tools fell short. Manually checking spectrograms for upscaled fakes took forever, and standard volume normalizers ruined the dynamics of my music. Instead of settling, I spent a weekend pair-programming with AI to build a custom solution. Two days and thousands of lines of Python later, TrueSonix was born.

TrueSonix is a standalone Windows desktop utility designed to deep-scan, diagnose, and curate massive music libraries. It gives you the analytical evidence and the batch-editing tools you need to clean up your collection and guarantee perfect audio fidelity.

---

## ✨ Key Features

### 🔍 Deep Audio Diagnostics
* **Lossless Authenticity Scanner:** Stop guessing if your files are genuine. TrueSonix detects frequency cutoffs to expose lossy files (like 128kbps MP3s) falsely upscaled into FLAC or WAV formats. Generate high-resolution **Frequency Spectrograms** with a single right-click.
* **Fidelity Metrics:** Decodes audio waveforms to calculate True Peak, clipping percentages, LUFS ReplayGain, and Dynamic Range (TT-DR and LRA).
* **"Pest" Filter:** A one-click toggle to instantly isolate "Bad" or "Source Limited" files hidden deep inside massive libraries.

### 🏷️ Ultimate Metadata Curation
* **Unified Entity Manager:** A master-detail interface to clean up messy artist catalogs. Automatically split combined tags (e.g., "Artist A & Artist B") and use the **Fuzzy Spell Checker** to merge misspellings (like "AR Rahman" and "A.R. Rahman") across your entire library.
* **Intelligent Tag Studio:** A massive bulk-editor for text fields with a dynamic preview. Includes Find & Replace, Overwrite, Append, Prefix, and quick-formatting (Title Case, Trim Spaces).
* **Universal Compatibility:** Built with a custom, brute-force ID3v2.3 saving mechanism to ensure that tags saved to `.wav`, `.flac`, and `.mp3` files are 100% visible across Windows and all modern media players.

### 🎚️ Global Gain Override
* **Shift ReplayGain:** Manually shift the ReplayGain of a batch of tracks to match a specific baseline volume. 
* **Clipping Protection:** Includes a clipping prediction engine and an "Auto-Fix" safety limiter that mathematically scales back tracks to prevent distortion before you save.

### 🔒 Offline Analysis Mode
* **Smart Imports:** Export your scan data to Excel/CSV. If you import a scan from a disconnected external drive, TrueSonix detects missing files and asks to enter Offline Mode.
* **Virtual Folder Tree:** In Offline Mode, TrueSonix dynamically reconstructs your library's folder structure in memory, completely locking down all file editing capabilities so you can safely filter, view, and analyze massive datasets without risking accidental metadata writes.

---

## 🚀 Getting Started (No Installation Required)

TrueSonix is packaged as a ready-to-use, standalone Windows executable. 

1. Navigate to the **[Releases](../../releases)** section on the right side of this repository.
2. Download the latest `TrueSonix.exe` file.
3. Double-click the file to run the application instantly.

---


## 🛠️ Under the Hood
For developers curious about the stack, TrueSonix is written in **Python 3** and utilizes:
* `tkinter` / `sv_ttk` for the sleek, dark-mode Windows 11 GUI.
* `mutagen` for robust audio metadata read/write operations.
* `soundfile` and `numpy` for fast audio decoding and matrix operations.
* `pyloudnorm` for ITU-R BS.1770-4 loudness compliance.
* `matplotlib` for plotting frequency spectrums.

---

## 🤝 Support & Connect

If this tool helped you organize your massive library, saved you hours of manual tagging, or rescued your sanity, I'd love to hear about it! 

Drop a thanks, let me know how it worked for you, or connect with me on LinkedIn: 
**[Harish Reddy](https://www.linkedin.com/in/hareesh-reddy/)**
