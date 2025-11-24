# Videos Random - Video Player

A simple single-page web application for playing videos.

## 📁 Structure

- `index.html` - Main video player page
- `videos/` - Directory containing all video files
  - VIDEO BH1.mp4
  - VIDEO BH2.mp4
  - VIDEO BV1.mp4
  - VIDEO BV2.mp4

## 🚀 Usage

1. Open `index.html` in your web browser
2. Or serve it with a local server:
   ```bash
   python3 -m http.server 8080
   ```
   Then navigate to `http://localhost:8080`

## ✨ Features

- Responsive grid layout that adapts to different screen sizes
- Individual video controls (Play/Pause, Restart)
- Beautiful gradient design
- Automatic video listing
- Shows total video count

## 🎬 Adding New Videos

To add new videos:
1. Place your `.mp4` files in the `videos/` folder
2. Update the video list in `index.html` (around line 136)
3. Refresh the page

## 📱 Responsive Design

The page is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
