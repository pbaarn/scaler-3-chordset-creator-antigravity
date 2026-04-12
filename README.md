# Dr. Harmony: Scaler 3 Chordset Creator for Antigravity

This repository contains the configuration and instructions for using **Antigravity** (Google DeepMind's agentic AI) as a professional music theory specialist and Scaler 3 chordset generator.

## 🎯 What is this?

This project provides a **System Instruction (Rule)** that transforms Antigravity into "Dr. Harmony"—an expert capable of interpreting complex musical moods, genres, and artist styles into valid Scaler 3 XML chordsets. 

The included XML files in `/chordsets` are examples of what Dr. Harmony can generate in seconds.

## 🛠 Setup in Antigravity

To use Dr. Harmony in your own workspace:

1.  **Clone this repo** into your workspace.
2.  **Add the Rule:** Ensure the file `chordset-specialist.md` is in your workspace root or mentioned in your `.gemini/rules` configuration.
3.  **Activate:** Simply start a chat with Antigravity and ask for a chordset. The agent will automatically reference the `chordset-specialist.md` rule.

## ⌨️ Sample Prompts

You can get as specific or as atmospheric as you want. Here are some successful examples:

### Artist Styles
> "Generate a bank of chords that Steely Dan would use, focusing on the Mu Major voicing."

> "Create a bank of chords for a Toto-style arena rock anthem, wide voicings with plenty of sus4 movements."

### Genre & Mood
> "Create a bank with heavy clustered chords for modern RnB / Neo-Soul."

> "Generate 4 different banks with 10-12 chords each for different atmospheres (e.g. Nordic Noir, Cyberpunk, Elysium Garden). Surprise me."

### Theory-Based
> "Create a jazz bank in Eb Minor focusing on minor 9ths and 11ths for smooth voice leading."

## 🎹 Importing Outputs

When Antigravity generates an XML block:
1.  Ask it to **"save the xml to a local file"**.
2.  Open **Scaler 3**.
3.  Go to the **Open/Import** menu and select the generated `.xml` file.
4.  Scaler 3 will automatically detect the chord names and voicings.

## 📂 Example Outputs
Check the `/chordsets` directory to see high-quality examples of what this tool produces:
*   `artist_styles/` - Steely Dan, Toto, Jazz, etc.
*   `atmospheres/` - Nordic Noir, Cyberpunk, etc.
*   `seventies_pop/` - Traditional song-writer harmony.

---
*Powered by Antigravity Music Theory Engine*
