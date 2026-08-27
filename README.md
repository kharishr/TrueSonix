**🎧 TrueSonix
The Precision Audiophile Library Manager & Diagnostic Tool**

TrueSonix is a powerful desktop utility designed to deep-scan, diagnose, and curate massive music libraries. Built for audiophiles who demand perfect metadata and audio fidelity, TrueSonix analyzes tracks for clipping, calculates LUFS ReplayGain, spots "fake" upscaled lossless files, and provides an entire suite of bulk-tagging tools.

**Fun Fact: TrueSonix was conceptualized, designed, and fully coded over a single weekend using AI Pair Programming!
**

✨ Key Features
  Deep Audio Diagnostics: 
  Decodes audio waveforms to calculate True Peak, clipping percentage, LUFS ReplayGain, and Dynamic Range (TT-DR and LRA).
  
  Lossless Authenticity Scanner: Automatically detects frequency cutoffs to expose lossy files (like 128kbps MP3s) that have been falsely upscaled into FLAC or WAV formats. You can even right-click a track to view a generated Frequency Spectrogram.
  
  Unified Entity Manager: 
  A dedicated tool to clean up messy Artist, Composer, and Lyricist tags. Features a Fuzzy Spell Checker (to easily merge "AR Rahman" and "A.R. Rahman") and a smart tool to split combined artists (e.g., changing "Artist A & Artist B" into properly separated tags).
  
  Intelligent Tag Studio: 
  A massive bulk-editor for text fields (Genre, Album, Year, etc.). Includes Find & Replace, Overwrite, Append, Prefix, and quick-formatting (Title Case, Trim Spaces).
  
  Global Gain Override: 
  Manually shift the ReplayGain of a batch of tracks to match a specific baseline volume. Includes a preview mode with an "Auto-Fix" safety limiter to prevent tracks from clipping.
  
  Universal Compatibility: 
  Built with a brute-force ID3v2.3 saving mechanism, ensuring that tags saved to .wav, .flac, and .mp3 files are 100% visible across Windows and all media players.

🚀 Getting Started (No Installation Required)
TrueSonix is packaged as a standalone executable.

Go to the Releases page on this GitHub repository.

Download the latest TrueSonix.exe file.

Double-click the .exe to run the application (no installation necessary).

**📖 Quick Usage Guide
**
  1. Scanning Your Library
  Click Folder in the top-left to select your music directory.
  
  Use Fast Scan to instantly read existing ID3/FLAC metadata without opening the audio waveform.
  
  Use Deep Analyze to process the actual audio files. This calculates ReplayGain, True Peak, and checks for upscaled fakes. (Note: Deep Analyze takes longer, especially on large libraries).
  
  2. Filtering & Viewing Data
  Select specific folders on the left pane to instantly filter the Diagnostics Table.
  
  Right-click any column header to quickly filter by specific genres, albums, or dynamic range scores.
  
  Right-click any track in the table to view its full technical specifications or generate a Spectrogram.
  
  3. Fixing Tags & Volume
  Highlight multiple tracks and select Save Tags to embed the calculated ReplayGain and DR metrics directly into the files.
  
  Use Fix artist info to open the Master-Detail entity manager to clean up spelling mistakes across your library.
  
  Use Tag Studio to mass-update genres, albums, and years.
