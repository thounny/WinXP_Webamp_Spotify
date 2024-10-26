# WinXP Webamp Spotify

A nostalgic web project that recreates a Windows XP-style desktop with a Webamp player that connects to Spotify. This project combines the look and feel of the Windows XP OS with the functionality of a modern Spotify player, allowing users to authenticate with their Spotify account and play their music through Webamp.

## Project Features

- **Windows XP-inspired UI**: A layout that mimics the classic Windows XP desktop, including a taskbar and a "Start" menu.
- **Webamp Integration**: The Webamp music player embedded in the page, styled to match the retro XP theme.
- **Spotify Authentication**: Users can log into their Spotify accounts to access their currently playing track.
- **Sync Playback**: Webamp syncs with Spotify to play users' Spotify music directly through the Webamp interface.
- **Real-Time Taskbar Clock**: A time display on the taskbar, updated in real-time to resemble the Windows XP experience.

---

## To-Do List

This list outlines the major tasks and features we plan to implement. Checkboxes will be marked as each task is completed.

### Project Setup

- [x] Create GitHub repository and add README
- [x] Invite collaborators [**Jordan Smith**](https://github.com/Origins96) to the repository

### Windows XP UI Layout

- [ ] Set up main HTML structure with containers for Webamp and taskbar
- [ ] Style the page background and taskbar to mimic Windows XP
- [ ] Add "Start" button and time display on the taskbar
- [ ] Implement JavaScript to update the time display every minute

### Webamp Integration

- [ ] Embed Webamp in the page and display it in a container
- [ ] Load a test audio track into Webamp for initial testing
- [ ] Style Webamp to fit the Windows XP theme

### Spotify Authentication

- [ ] Set up Spotify OAuth to allow user login
- [ ] Capture and store Spotify access token after login
- [ ] Create a "Login with Spotify" button to initiate authentication

### Sync Spotify Playback with Webamp

- [ ] Use Spotify API to fetch currently playing track
- [ ] Load Spotify track data (artist, title, preview URL) into Webamp
- [ ] Handle cases where track preview is unavailable
- [ ] Sync playback controls between Spotify and Webamp

### Final Testing and Deployment

- [ ] Test full application flow: login, play, sync
- [ ] Fix any bugs or styling issues
- [ ] Deploy project on GitHub Pages
- [ ] Verify live site functionality

---

## Installation and Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/WinXP_Webamp_Spotify.git
   cd WinXP_Webamp_Spotify
   ```

2. **Open `index.html`**:
   - Open the file in your preferred browser to view the project locally.

---
