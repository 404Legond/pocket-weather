# Pocket Weather

A hand-drawn, sketchy weather app with no API keys, no external dependencies, and full offline support.

## Live Demo

[https://sketchy-weather.netlify.app](https://sketchy-weather.netlify.app)

## Features

- GPS location detection
- Search any city worldwide
- Current conditions (temp, feels like, humidity, wind)
- 5-day forecast
- 12-hour hourly forecast
- UV Index with safety labels
- Air quality
- Moon phase
- °F / °C toggle
- Offline cache (24 hours)
- Auto-refresh (30 min)
- Fully responsive
- No API keys

## Why No API Keys?

Uses Open-Meteo (free, no key) and Nominatim (free geocoding).

## Technical Highlights

- Token bucket rate limiting (3 req/sec)
- AbortController for request cancellation
- localStorage cache with stale-while-revalidate
- Page Visibility API for battery efficiency
- Canvas 2D sketchy borders (no external libs)
- Inline moon phase calculation

## File Structure

pocket-weather/
├── weather.html
├── README.md
└── LICENSE

## Local Development

Open weather.html in your browser. No build step.

## License

MIT

## Questions?

Find me on GitHub: [404Legond](https://github.com/404Legond)
