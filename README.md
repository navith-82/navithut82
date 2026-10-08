# Battambang Heritage Walking Tour
# ដំណើរទស្សនកិច្ចតាមផ្លូវបេតិកភណ្ឌក្រុងបាត់ដំបង

A bilingual (English and Khmer) heritage website for 14 historic locations in Battambang, Cambodia.
It has an interactive walking map, a QR code and icon for every location, and an embedded video for each place.

Started as an AUPP Liger Leadership Academy Exploration, August 2026.

## How the site is built
The whole site is one file: `index.html` (plain HTML, CSS and JavaScript, no build step).

## How to update it
Open `index.html` and edit the data near the top of the `<script>`:

- `SITES`: the 14 locations (English and Khmer text, and the YouTube playlist id in `list`).
  Add `video: "VIDEO_ID"` to a location to play one exact video from its playlist.
- `PHOTOS`: the photo for each location.
- `ASSETS`: the map icon and QR code for each stop number.
- `TEACHERS` and `STUDENTS`: the names on the About page.

## Put it online with GitHub Pages
1. Open the repository on GitHub, then **Settings > Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
3. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

YouTube videos play inside the page on GitHub Pages.
