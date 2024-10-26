# Music Suggestor

Music Suggestor is a project that analyzes user emotions and suggests songs based on their current emotional state. This project utilizes DeepFace for emotion detection and integrates with the Spotify API to fetch song recommendations.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- Emotion detection using DeepFace
- Integration with the Spotify API for song recommendations
- User-friendly interface with Jupyter Notebook
- Customizable and extendable architecture

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- pip (Python package installer)

### Clone the Repository

```bash
git clone https://github.com/eleonoraferns/music_suggestor.git
cd music_suggestor

```
### Set up a virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```

### Install the required dependencies using pip
```bash
pip install -r requirements.txt
```

### Create a Spotify App

Create an app on https://developer.spotify.com/ and record your unique client ID and secret

### Set up environment variables
Create a .env file in the project directory and add your Spotify API credentials. Use the following format:
```bash
SPOTIFY_CLIENT_ID=your_client_id
SPOTIFY_CLIENT_SECRET=your_client_secret
SPOTIPY_REDIRECT_URI=http://localhost:8888/callback
```
Make sure to replace your_client_id and your_client_secret with your actual Spotify API credentials.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or open an issue.

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push to your branch.
Open a pull request.

