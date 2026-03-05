# NFI WHEELS Inventory Locator

## Overview
The NFI WHEELS Inventory Locator application is designed to assist users in tracking and managing wheels inventory effectively.

## Installation Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/<owner>/wheels-locator.git
   cd wheels-locator
   ```
2. **Install dependencies:**
   Make sure you have `npm` or `yarn` installed, then run:
   ```bash
   npm install
   # or
   yarn install
   ```

## How to Use
1. **Start the application:**
   ```bash
   npm start
   # or
   yarn start
   ```
2. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.
3. **Follow the on-screen instructions** to manage your wheels inventory.

## Deploying on GitHub Pages
1. **Build the application:**
   ```bash
   npm run build
   # or
   yarn build
   ```
2. **Deploy to GitHub Pages:**
   To deploy, you can use the `gh-pages` package:
   ```bash
   npm install gh-pages --save-dev
   ```
   Then add this to your `package.json` scripts:
   ```json
   "deploy": "gh-pages -d build"
   ```
   Finally, run:
   ```bash
   npm run deploy
   ```
   Your application should now be live on GitHub Pages!