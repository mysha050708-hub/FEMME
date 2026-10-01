# FEMME — run locally

FEMME is a small Hindi/English voice-and-text prototype. It needs Node.js (version 18 or newer) and no package installation.

## Start

1. Open PowerShell or Command Prompt in this folder (`outputs`).
2. Run `node server.js` (or `npm start`).
3. Open `http://127.0.0.1:4173` in Chrome or Edge.
4. Keep the terminal window open while using the app. Press Ctrl+C to stop the server.

To use a different port, set `PORT` before starting the server. For example in PowerShell: `$env:PORT=5000; node server.js`.

The text demo works without a microphone. Voice input depends on browser support and microphone permission. Guidance is a curated prototype and does not determine scheme eligibility or submit applications. It is not connected to Gemini or another AI service yet.
