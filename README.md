# 🎵 Music Playlist

An interactive React application that allows users to search and delete tracks from a dynamic playlist. Built using functional UI components, lists & keys, state management, and conditional rendering.


### Refer to the image below:

<br/>
<div style="text-align: center;">
  <video style="max-width:80%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12);outline:none;" loop="true" autoplay="autoplay" controls="controls" muted>
    <source src="https://assets.ccbp.in/frontend/content/react-js/music-playlist-output.mp4" type="video/mp4">
  </video>
</div>
<br/>

## 🚀 Features

### ✅ Initial Track Rendering
- Renders all items from `initialTracksList`.
- Each track displays:
  - 🎵 Image (`imageUrl` with `alt="track"`)
  - 📝 Name & Genre
  - ⏱ Duration
  - ❌ Delete button (`data-testid="delete"`)

### 🔍 Live Search Functionality
- Case-insensitive filtering of tracks based on `name`.
- Filters on every keystroke.
- Empty search displays full list.
