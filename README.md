# whatismyloc

Single-page site that shows the visitor's **IP address, city, and country**, detected via the free [ipwho.is](https://ipwho.is/) API (no API key required).

## Usage

Open `index.html` in a browser, or serve the folder with any static server.

## How it works

On page load, `index.html` calls `https://ipwho.is/`, which returns geolocation data for the requesting IP, and renders the IP, city, country.

