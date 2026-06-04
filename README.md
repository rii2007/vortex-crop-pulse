#  Crop Market Price Pulse

> A real-time, multi-lingual agricultural platform built to empower farmers with live APMC mandi prices. Features an interactive Leaflet map, automated device GPS location tracking, smart side-by-side market comparisons, and a built-in voice search engine to maximize crop returns.

## 📑 Table of Contents
- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage Guide](#usage-guide)
- [The Team](#the-team)

##  About the Project
**Crop Market Price Pulse** bridges the gap between the agricultural field and the digital world. Modern farms generate massive amounts of data, and our goal is to translate that complex agricultural data into a clean, accessible UI. 

This platform helps farmers track crop health, forecast weather impacts, and, most importantly, **find the absolute best market price for their yield** across nearby APMC mandis. 

##  Key Features
* ** Interactive Price Map:** Integrated with `Leaflet.js` to plot real-world mandi coordinates, giving farmers a visual representation of nearby markets.
* ** Live Device GPS:** Uses the browser's Geolocation API to automatically find the user and filter market data based on their regional proximity.
* ** Voice Recognition Search:** Built-in Web Speech API integration allows farmers to search for crops by simply speaking the crop name (Supports English and Hindi voice inputs).
* ** Native Multi-Language Support:** Fully localized UI with instant, seamless switching between English, Hindi, Punjabi, Gujarati, and Marathi without page reloads.
* ** Smart Market Comparison:** Automatically extracts the top 2 best-performing markets for a selected crop and places them head-to-head for easy side-by-side analysis.
* ** Dynamic UI & Animations:** Features a flashing hero recommendation card that updates instantly to highlight the absolute highest profit margin available.

## 🛠️ Tech Stack
This project is built to be extremely lightweight and fast, relying primarily on vanilla web technologies:
* **HTML5** (Semantic structuring)
* **CSS3** (Custom responsive design, grid/flexbox layouts, CSS animations—*No Bootstrap or Tailwind required*)
* **Vanilla JavaScript** (DOM manipulation, data sorting, translation logic)
* **Leaflet.js & OpenStreetMap** (Interactive mapping)
* **Web Speech API** (Voice-to-text recognition)
* **Geolocation API** (Location tracking)

##  Getting Started

Because this project is built entirely with frontend technologies and encapsulated in a single file, setup is incredibly simple.

### Prerequisites
You only need a modern web browser (Google Chrome, Microsoft Edge, Safari, or Firefox).

### Installation & Execution
1. Clone the repository to your local machine:
```bash
   git clone [https://github.com/rii2007/vortex-crop-pulse.git](https://github.com/rii2007/vortex-crop-pulse.git)
