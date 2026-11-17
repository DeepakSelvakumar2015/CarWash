# Car Wash Finder

A single-page website that shows every car wash within a 5 km radius of your location or of any address you search.

- **Use my location** (browser geolocation) or search an address (OpenStreetMap Nominatim)
- Car wash data from OpenStreetMap via the Overpass API (no API key needed)
- Interactive Leaflet map with the 5 km radius and numbered pins
- List sorted by distance with hours, type, directions, phone and website links
- Filters: Automatic, Self-service, Hand wash, Open 24/7
- Mobile-friendly, with dark mode

## Run it

Open `index.html` in a browser. "Use my location" requires the page to be served over `https://` or from `localhost`, for example:

```bash
python3 -m http.server 8000
```

then open http://localhost:8000. Address search works either way.
