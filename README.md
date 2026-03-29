# Spotify Clone 🎵

A web-based music player inspired by Spotify, built with HTML, CSS, and JavaScript.

## Features
- 🎵 Play, pause, next and previous song controls
- 🔊 Volume control and mute/unmute
- ⏱️ Seekbar with real-time time display
- 📁 Multiple album support with cover images
- 📋 Dynamic song list in sidebar
- 📱 Responsive design with hamburger menu

## Tech Stack
- HTML
- CSS
- JavaScript (Vanilla)
- Node.js (Local Development Server)

## How to Run
1. Clone the repository
git clone https://github.com/minhajshah23/Spotify-Clone.git

2. Open the project in VS Code

3. Start a local server on port 3000

4. Add your own mp3 files inside each album folder

5. Open http://127.0.0.1:3000 in your browser

## Album Format
Each album folder inside songs/ must contain:
- cover.jpg — album cover image
- info.json — album metadata
- .mp3 files — your own songs

### info.json format
{
    "title": "Album Title",
    "description": "Album description"
}

## Note
Songs are not included in this repository due to GitHub file size limits.
Add your own mp3 files inside the songs/ folder following the album format above.

## Credits
- Built following the Sigma Web Development Course by CodeWithHarry
- UI inspired by Spotify