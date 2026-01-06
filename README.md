# Personal Watch Tracker

An easy way to track the watches you like! It's a simple, single-file application to track your watch collection and wishlist. It runs entirely in your browser with no server or login.

## Features

* **Zero Setup:** Just download the HTML file and open it in any browser.
* **Persistent:** Your data is saved automatically in your browser (LocalStorage).
* **Visual Gallery:** View your watches in a card view with a scrollable image carousel.
* **Detailed Tracking:** Store name, price, multiple images, description, tags, and purchase links.
* **Search & Sort:** Filter by tag or name; sort by price or date added.
* **Portable:** Export your collection to a JSON file to backup or move to another device.

## Quick Start
Use it online here -> https://naveentuyo.net/watch-tracker/

## How Set Up Locally

1.  **Installation:**
    * Download the `index.html` file.
    * Place it in any folder on your computer (e.g., `Documents/Watches`).

2.  **Running the App:**
    * Double-click the `index.html` file. It will open in your default web browser.

## How to Use
1.  **Adding a Watch:**
    * Click the **+ Add Watch** button.
    * Fill in the details.
    * **Images:** Paste image URLs (right-click an image online -> "Copy Image Link"). You can add multiple images by pasting one URL per line.

2.  **Editing a Watch's Details**
    * Click the **Edit** button that appears when hovering over a watch.
    * Change the details you wish.
    * Click **Save Changes**

3.  **Backup / Sync:**
    * Click **Export JSON** to save a backup of your data to your machine.
    * Click **Import JSON** to load that backup on a different computer or browser.

## Tech Stack

* **HTML5**
* **Tailwind CSS** (via CDN)
* **Vue.js 3** (via CDN)
* **LocalStorage** (for data persistence)

## Important Note

Since this runs locally in your browser, clearing your browser's "Site Data" or "LocalStorage" will wipe your list. **Always use the "Export JSON" feature to back up your collection regularly.**
