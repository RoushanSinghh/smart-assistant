This is a [Plasmo extension](https://docs.plasmo.com/) project bootstrapped with [`plasmo init`](https://www.npmjs.com/package/plasmo).

## Getting Started

1. Clone this repository.
2. Load the extension in Chrome by navigating to `chrome://extensions/`, enabling "Developer mode," and selecting "Load unpacked."
3. Run the development server:

```bash
pnpm dev
# or
npm run dev
```
4. Open a webpage, click the extension icon, and start chatting with AI !

Open your browser and load the appropriate development build. For example, if you are developing for the chrome browser, using manifest v3, use: `build/chrome-mv3-dev`.

# SmartAssistant Chrome Extension

## Overview

This Chrome extension allows users to interact with AI directly on any webpage.

## Features

- Click on the Chrome extension icon to open a popup modal.
- Enter a command and send to receive a streaming response from AI .
- Popup modal dimensions: 500px x 500px.

## Technologies Used

- TypeScript
- React
- Plasmo Framework
- [Tailwind CSS](https://tailwindcss.com/) (Bonus points!)

## Project Structure

- **src/**: Contains the source code of the Chrome extension.
- **assets/**: Holds static assets.

## Demonstration

Check out the [demonstration video](./demo-video.mp4) for a quick overview.

## Repository
- Backend repository: [Link to Backend Repo](_backend_repo_link)
