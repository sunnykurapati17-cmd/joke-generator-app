# Joke Generator App

A simple, responsive joke generator web application built with HTML, CSS, and JavaScript.

## Features

- Fetches random jokes from JokeAPI v2
- Safe for work (NSFW content filtered out)
- Handles both single-line and two-part jokes
- Copy-to-clipboard functionality
- Responsive design for mobile and desktop
- Error handling for network issues
- Auto-loads a joke on page open

## How to Use

1. Open `index.html` in any modern web browser
2. Click "Get New Joke" to fetch a random joke
3. Use "Copy Joke" to copy it to your clipboard

## API

This app uses the JokeAPI v2: https://v2.jokeapi.dev/

## Customization

You can modify the API URL to get specific joke categories:
- Programming: `https://v2.jokeapi.dev/joke/Programming?blacklistFlags=nsfw,religious,political,racist,sexist,explicit&type=single`
- Dark: `https://v2.jokeapi.dev/joke/Dark?blacklistFlags=nsfw,religious,political,racist,sexist,explicit&type=single`
- Any: `https://v2.jokeapi.dev/joke/Any?blacklistFlags=nsfw,religious,political,racist,sexist,explicit&type=single`

## File Structure

- `index.html` - Main application file (HTML, CSS, and JavaScript all in one)
- `README.md` - This file

## License

Free to use and modify for personal and educational purposes.
