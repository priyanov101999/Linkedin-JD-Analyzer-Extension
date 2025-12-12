# LinkedIn JD Analyzer

A Chrome extension that extracts **experience requirements**, **tech stack**, and **citizenship mentions** from LinkedIn job descriptions and displays a floating summary box.

## Setup
1. Clone or download this repo.
2. Open Chrome and go to `chrome://extensions`.
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the project folder.

## Usage
Open any LinkedIn job posting (`linkedin.com/jobs/*`).  
The JD summary box appears automatically and updates dynamically.

## Tech
- Chrome Extension (Manifest V3)
- Content scripts
- MutationObserver for dynamic updates
