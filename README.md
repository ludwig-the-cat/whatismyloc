# whatismyloc

Single-page site that shows the visitor's **IP address, city, and country**, detected via the [httpbin.agrd.dev](https://httpbin.agrd.dev/get) endpoint (no API key required).

## Usage

Open `index.html` in a browser, or serve the folder with any static server.

## How it works

On page load, `index.html` calls `https://httpbin.agrd.dev/get`, which returns the requesting IP plus Cloudflare geolocation data (`cf.city`, `cf.country`), and renders the IP, city, and country.

