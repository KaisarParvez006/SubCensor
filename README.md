# SubCensor
# SubCensor

**SubCensor** is a Python-based tool to automatically detect and replace explicit or inappropriate words in `.srt` subtitle files. It also helps generate labels for Audacity and allows offset correction for syncing subtitles with audio/video tracks.

---

## 🚀 Features

- Replaces offensive words with safe alternatives.
- Supports full customization of word replacements.
- Generates:
  - Filtered SRT file (with cleaned text).
  - Audacity label file to identify time segments with explicit content.
  - Offset-adjusted label file for syncing.
- Optional creation of fully censored SRT version with masked content.

---

## 📂 How to Use

1. **Upload your `.srt` file** to the project directory.
2. **Update the filename** and `audio_sub_titles_offset_seconds` in the script.
3. Run the script in your Python environment or Jupyter notebook.
4. Process the output files:
   - `filtered.srt`
   - `original_audacity_labels.txt`
   - `offset_corrected_audacity_labels.txt`

5. Use Audacity and LosslessCut for audio silencing and subtitle/audio replacement.

---

## ⚙️ Configuration

- Modify the `explicit_words_replacement` dictionary to add or change word replacements.
- Adjust the `audio_sub_titles_offset_seconds` variable to correct subtitle timing.

---

## 🧠 Requirements

- Python 3.x
- No external dependencies (standard library only)

---

## 🔐 Disclaimer

This tool is intended for educational and responsible content editing use. Make sure to respect content rights and follow platform guidelines when distributing modified media.
