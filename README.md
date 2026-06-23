# 101 Conversations in Intermediate Italian 🎧

Interactive listening practice web app for **101 Conversations in Intermediate Italian** by Olly Richards.

## Features

- **101 Italian dialogues** with **edge-tts** Italian audio (Elsa neural voice)
- **Chinese translations** for every paragraph
- **3-speed control**: 0.6x (slow) / 1x (normal) / 1.4x (fast) via `audio.playbackRate`
- **Per-paragraph audio** with play progress bar
- **Play all** mode for continuous listening
- **Toggle** Italian original text show/hide
- **Toggle** Chinese translation show/hide
- **Vocabulary list** with word pronunciation
- **Progress tracking** via localStorage
- **Keyboard navigation**: ← → for prev/next, Space to stop
- **Responsive design**: mobile, tablet, desktop

## How to Use

Open `index.html` in any browser. The app loads `enhanced_conversations.json` (with embedded base64 audio) or falls back to `conversations.json`.

## Tech Stack

- Pure HTML/CSS/JS (no frameworks)
- edge-tts (Azure Neural TTS, Italian Elsa voice)
- Web Audio API (`playbackRate` for speed control)
- GitHub Pages ready

## Credits

Book: *101 Conversations in Intermediate Italian* by Olly Richards
