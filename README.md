<!-- omit in toc -->
# Jammming Web App - Codecademy Solo Portfolio Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Set Up the Project](#part-1-set-up-the-project)
  - [Configure Spotify API](#part-2-configure-spotify-api)
  - [Run the App](#part-3-run-the-app)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Jammming is a solo portfolio project developed as part of the Codecademy Full-Stack Engineer Career Path. It is a web app that allows users to search for songs, create custom playlists, and save those playlists to their Spotify accounts. The project showcases the use of React, state management, and API integration to build an interactive and functional music search and playlist creation application.

![Jammming Web App Screenshot](./screenshot.png)

## Features

- Search for songs using the Spotify API.
- View song details including name, artist, and album.
- Add songs to a custom playlist.
- Remove songs from the playlist.
- Save the playlist to your Spotify account.

## Technologies Used

- React
- HTML
- CSS
- JavaScript
- Spotify API

## Getting Started

### Part 1: Set Up the Project

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies using `npm install`.

### Part 2: Configure Spotify API

1. Create a Spotify Developer account (if you don't have one).
2. Create a new Spotify App to obtain the API credentials (Client ID).
3. Set up the Redirect URI in your Spotify App settings.
4. Create a `.env` file in the root of the project and add your Spotify API credentials:

REACT_APP_SPOTIFY_CLIENT_ID=YOUR_SPOTIFY_CLIENT_ID
REACT_APP_REDIRECT_URI=YOUR_REDIRECT_URI

### Part 3: Run the App

1. Start the development server with `npm start`.
2. Open your web browser and navigate to `http://localhost:3000`.

## Usage

1. On the home page, enter a search term for the song you want to find in the "Search for songs" input field.
2. Click the "Search" button or press Enter to initiate the search.
3. The search results will be displayed below the search bar. You can view the song details, including name, artist, and album.
4. To add a song to your custom playlist, click the "+" button next to the song.
5. To remove a song from the playlist, click the "-" button next to the song in the playlist section.
6. To save your custom playlist to your Spotify account, click the "Save to Spotify" button. You will be redirected to the Spotify login page if you are not already logged in.

## Contributing

As a solo portfolio project, contributions are not expected. This project was solely developed by Patrick Vicente as part of the Codecademy Full-Stack Engineer Career Path.

## License

This project is licensed under the [MIT License](LICENSE).
