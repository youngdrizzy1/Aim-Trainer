# 🎯 Aim Trainer Game

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Post-blue)](https://www.linkedin.com/posts/eromosele-itoya_python-pygame-gamedev-activity-7349058650138632195-FRHu?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEbDOGsBGINDr5uoWo3fkmNHZc_HI1Qst6k)

A fun, interactive Aim Trainer game built with Python and Pygame. Test your mouse accuracy and reaction speed by clicking targets before they disappear. You’ve got 3 lives—don’t let them slip away!

## Features ✨
- 🎯 Dynamic Targets: Grow and shrink to challenge your timing
- 💔 Lives System: Start with 3 lives, lose one per miss
- 📊 Real-Time Stats: Track time played, speed (targets/sec), hits, and lives
- 🖥️ Smooth UI: Beautiful design for seamless play

## Screenshots 📸
|  Game in Progress | Final Result   |
|------------------|----------------|
| ![Game_Progress](screenshots/Game_progress.png) | ![Result](screenshots/Result.png) 

- Initial Screen: Start here by entering a YouTube URL.
- Video Details: See the thumbnail, title, and stats before downloading.
- Download Complete: Progress bar full, ready to save or clear!

## How to Use 🎥
1. Enter a valid YouTube URL in the input field.
2. Check out the video details (thumbnail, title, channel, etc.).
3. Hit "Download Video" and watch the progress bar roll.
4. Once done, click "Save Video to Device" to grab the file.
5. Use "Clear Download" to reset for the next video.
Note: Videos over 20 minutes might take a bit longer to download.

## Tech Stack 🛠️
- **Frontend**: Streamlit
- **Backend**: Python 3
- **Key Libraries**: 
  - `streamlit` for the UI
  - `pytubefix` for YouTube video downloading
  - `io.BytesIO`  for file buffering
  - `time`   for duration formatting

## Installation ⚙️
1. Clone repository:
```bash
git clone https://github.com/youngdrizzy1/Youtube-Downloader
cd Youtube-Downloader
```

2. Install dependencies:
```bash
pip install streamlit pytubefix
```

3. Run the application:
```bash
streamlit run app.py
```

## Live Demo 🌐
Check out the live version: [Youtube-Downloader-App](https://youtube-downloader0.streamlit.app/)
- Heads Up: The app works perfectly locally but may hit errors on Streamlit Cloud due to pytubefix or cloud restrictions. I’m on it—suggestions welcome!

## Known Issues ⚠️
Runs smoothly on local devices but faces deployment hiccups on Streamlit Cloud. Likely a pytubefix compatibility or network issue—help appreciated!

## Connect with Me 👋
[LinkedIn](https://www.linkedin.com/in/eromosele-itoya/) | 
[GitHub](https://github.com/youngdrizzy1)
