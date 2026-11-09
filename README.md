# Arena Trip Calculator

A single-page calculator comparing the cost and time of getting to Crypto.com Arena (1111 S Figueroa St, Los Angeles) by personal car, rideshare, or public transit for 1–3 riders.

- Enter a home address, city, or ZIP for a live route lookup (Google Maps JavaScript API geocoder and Routes API for the event date and start/end times you enter: driving with typical traffic so you are seated 15 minutes before the start, and transit schedules there and home after the event ends, with a warning when there is no late transit home; falls back to OpenStreetMap Nominatim and OSRM). You can also type miles and minutes yourself.
- Every assumption (gas price, MPG/EV efficiency, parking, rideshare surge, tip, transit fare) is editable.
- Shows per-person cost, the rider count at which splitting a car/rideshare beats transit, and where the round-trip time goes.

No build step: open `index.html` in a browser, or serve it with GitHub Pages.
