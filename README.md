# Weather-App-MVP

A lightweight, static weather app MVP built with plain HTML, CSS and JavaScript. This repository contains a small front-end app that shows current weather and a weekly view, with simple UI controls for toggling between Celsius/Fahrenheit and Today/Week display.

## Table of Contents

- **Overview**: Project purpose and goals
- **Technologies**: Tools and libraries used
- **Key Features**: What the app does
- **Project Structure**: Important files and folders
- **Run Locally**: How to open and serve the app
- **Usage**: Quick guide to UI controls
- **Live Demo / Screenshots**: Placeholder for screenshots or deployment links
- **Contact**: Who to reach out to

## Overview

This project is a minimal viable product (MVP) for a weather UI. It focuses on a clean, component-like structure while remaining a static front-end app that can be easily extended or connected to any weather API.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript (ES Modules)

## Key Features

- Current weather display (temperature, summary)
- Toggle between Today and Week views
- Celsius / Fahrenheit switch
- Responsive layout with icon sets (images/ folder)
- Modular code split into `main.js`, `ui.js`, `utils.js`, and `weather.js`

## Project Structure

- index.html
- README.md
- images/ — icon sets used by the UI
- scripts/
  - main.js — app bootstrap and UI event wiring
  - ui.js — DOM update helpers (right-hand pane, etc.)
  - utils.js — small helper utilities
  - weather.js — location and weather retrieval logic
- styles/
  - style.css

## Run Locally

You can open the app directly by double-clicking `index.html`, but some browsers restrict module imports when serving files from the filesystem. It's recommended to run a simple local HTTP server.


Using Node (http-server):

```bash
cd Weather-App-MVP
npx http-server -p 8000
# then open http://localhost:8000
```

Or use the Live Server extension in VS Code to serve and auto-reload.

## Usage

- Use the Today / Week links (top-left) to switch between single-day and weekly summary views.
- Use the C / F controls (typically near the main temperature) to switch units.
- The UI updates the right-hand panel when new weather data is available.

## Live Demo / Screenshots

* [Live Demo](https://weather-app-silk-kappa-66.vercel.app/)

* Screenshots:


## Contact

Replace the placeholder below with your contact details so users can reach you:

- **Author**: Rahaf Hazem
- **Email**: rahafhazem2002@gmail.com
