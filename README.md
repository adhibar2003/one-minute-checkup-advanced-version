# 1MINCheckUp — Upgraded Hackathon Prototype

This is a single-dashboard frontend-only demo with simulated vitals:
- Heart Rate (BPM)
- Blood Pressure (Systolic/Diastolic)
- Blood Sugar (mg/dL)
- Echo Cardiograph (simulated waveform)

Data and readings are stored in localStorage. This is a demo prototype (not a medical device).

## Run locally
npm install
npm run dev

## Run on GitHubBox / Codesandbox
Upload to GitHub and open with GitHubBox. vite.config.js includes `server.allowedHosts: true` to allow random subdomains.
