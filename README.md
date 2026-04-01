# YTDJ - Precision YouTube DJ Player

Demo: https://maruzilla.github.io/YTDJ/

**YTDJ** is a high-performance web-based video player designed for music enthusiasts and DJs who want precise control over YouTube content. It allows for millisecond-perfect cueing, ultra-fine playback speed adjustments, and playlist management with metadata.

## 🚀 Key Features

- **Precision Playback Control**: Adjust speed from **0.75x to 1.5x** in **0.01 increments** for perfect beat-matching or deep listening.
- **Millisecond Cueing**: Save specific timestamps ("Set Cue") with 3-decimal precision and jump back to them instantly.
- **Dynamic Playlist**: Manage your setlist with Title, URL, Custom Speed, Start Position, and Memos.
- **Data Portability**: 
  - **Export** your playlist to **CSV** for backup or external editing.
  - **Import** CSV files to restore your DJ sets instantly.
- **Pro UI**: Sleek, high-contrast **Cyan-on-Dark Gray** interface optimized for low-light environments.
- **Direct Loading**: Paste any YouTube URL (standard or shortened) to load tracks immediately.

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3 (Cyberpunk Dark Mode)
- **Logic**: Vanilla JavaScript (ES6+)
- **API**: [YouTube IFrame Player API](https://google.com)

## 📖 How to Use

1. **Load a Track**: Paste a YouTube URL into the input box and click **"Load"**.
2. **Fine-tune Speed**: Use the slider to adjust the tempo (0.01 steps).
3. **Mark your Cue**: 
   - Click **"Set Cue"** at the exact moment you want to remember.
   - Use **"Jump to Cue"** to return to that spot instantly.
4. **Build Playlist**: Add a memo and click **"Add to Playlist"** to save the current configuration (Speed + Timestamp).
5. **Load/Save Set**: Use the **Import/Export** buttons to manage your playlist via CSV files.

## ⚙️ Installation & Deployment

Since this is a client-side application, no backend is required.

1. Clone the repository:
   ```bash
   git clone https://github.com
