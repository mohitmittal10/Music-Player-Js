# Music Player Web Application

This is a web-based music player application that allows users to browse and play songs from various folders. The application features album display, song listing, playback controls, and the ability to save the last played song in local storage.

## Features

- **Display Albums**: Fetches and displays albums from a specified directory with metadata (title, description, cover image).
- **Play Songs**: Allows users to play, pause, skip to the next or previous song, and adjust the volume.
- **Song Progress and Duration**: Shows the current playback time and the total duration of the song.
- **Persist Last Played Song**: Saves the last played song in local storage and displays it when the page is reloaded.

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

### Prerequisites

- A web server to serve the application files.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/music-player-web-app.git
    ```

2. Navigate to the project directory:
    ```sh
    cd music-player-web-app
    ```

3. Place your song folders in the `songs` directory. Each folder should contain an `info.json` file with the album metadata and a `cover.jpeg` image for the album cover.

### Running the Application

1. Start your web server and serve the project directory.
2. Open your web browser and navigate to the server's address (e.g., `http://localhost:8000`).

## Folder Structure

- `index.html`: The main HTML file.
- `style.css`: The stylesheet for the application.
- `script.js`: The JavaScript file containing the application logic.
- `songs/`: Directory containing song folders with `info.json` and song files.

### Example `info.json`

Each album folder should contain an `info.json` file with the following structure:

```json
{
  "title": "Album Title",
  "description": "Album Description"
}
