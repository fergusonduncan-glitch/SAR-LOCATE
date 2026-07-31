SAR Locate is a lightweight, web-based Search and Rescue (SAR) command and sector planning application. It is designed for rescue teams to rapidly calculate search perimeters around an Initial Planning Point (IPP), automatically detect key ground features (footpaths, roads, and open spaces), and log searched areas in real time.

🌟 Features

⚬ Flexible Initial Planning Point (IPP) Placement:

	⚬ Search by UK Postcode (powered by postcodes.io).

	⚬ Direct Decimal Coordinates (Latitude/Longitude).

	⚬ what3words address lookup fallback.

	⚬ Interactive Drag & Drop Pin directly on the map.

⚬ Dynamic Search Perimeter Calculation:

	⚬ Automatically sets a standard 300m initial sector circle.

	⚬ Dynamically enlarges the search radius based on elapsed time (hours and minutes) and estimated average walking speed (‭$\text{Radius} = 300\text{m} + (\text{Time} \times \text{Speed})$‬).

⚬ Automated Feature Analysis (Overpass API):

	⚬ Fetches and highlights all roads, footpaths, tracks, parks, and open green spaces within the search perimeter.

⚬ Interactive Sector Tracking:

	⚬ Click on any highlighted feature on the map to mark it as Searched (turns grey and dashed).

	⚬ Clicking again re-opens the area if re-searching is required.

⚬ Real-time Searched Log:

	⚬ Logs searched feature names, types, and timestamp of completion.

	⚬ Features can be reviewed or cleared directly from the side panel.

🚀 Quick Start

No build step or server installation is required. The entire application runs directly in any modern web browser.

Running Locally

1. Download or clone this repository:

[bash]
git clone [https://github.com/your-username/sar-locate.git](https://github.com/your-username/sar-locate.git)


2. Open index.html in your web browser.

🌐 Free Hosting via GitHub Pages

You can host this application for free using GitHub Pages:

1. Create a public repository on GitHub.

2. Upload index.html and README.md to your repository's main branch.

3. In your repository, navigate to Settings > Pages.

4. Set Source to Deploy from a branch and choose main / / (root).

5. Click Save. Your site will be live within 1–2 minutes.

🛠️ Built With

⚬ Map Engine: Leaflet.js & OpenStreetMap

⚬ Geographic Data: Overpass API & osmtogeojson

⚬ Geocoding: postcodes.io & Nominatim

⚬ UI & Styling: Tailwind CSS & FontAwesome
