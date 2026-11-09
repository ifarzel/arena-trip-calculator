# Arena Trip Calculator

A single-page calculator comparing the cost and time of getting to Crypto.com Arena (1111 S Figueroa St, Los Angeles) by personal car, rideshare, or public transit for 1–3 riders.

- Enter a home address, city, or ZIP for a live route lookup (Mapbox geocoding, falling back to OpenStreetMap Nominatim; Mapbox traffic-aware routing for the coming Saturday: leaving home 5:45 PM, leaving the arena 10:30 PM; falls back to OSRM with a rough traffic multiplier). You can also type miles and minutes yourself.
- Every assumption (gas price, MPG/EV efficiency, parking, rideshare surge, tip, transit fare) is editable.
- Shows per-person cost, the rider count at which splitting a car/rideshare beats transit, and where the round-trip time goes.

No build step: open `index.html` in a browser, or serve it with GitHub Pages.
