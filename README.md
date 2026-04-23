# 🌍 Atom's Trips

Interactive travel planning pages — itinerary, packing list, weather info, and trip memories all in one place.

## 📋 Trips

| Trip | Dates | Destinations | Status |
|------|-------|-------------|--------|
| [Bromo-Bali 2026](./index.html) | 01-09 May 2026 | East Java × Bali | 📝 Planned |

## 🚀 Local Development

```bash
# Start localhost server
cd atom-trips
python3 -m http.server 8080
# Open http://localhost:8080
```

## 📁 Structure

```
atom-trips/
├── index.html          # Bromo-Bali Trip 2026
├── README.md           # This file
└── LICENSE             # MIT
```

## 🛠 How It Works

Each trip is a single self-contained HTML file with:
- **Dark theme** responsive design
- **Flight details** with airline codes and times
- **Daily timeline** with weather, what-to-wear, and hotel info
- **Interactive packing checklist** (click to check off items)
- **Temperature guide** per location
- **Safety reminders** and travel tips
- **Navigation dots** for quick day jumping

No build tools, no dependencies — just open in a browser.

## 📝 Adding New Trips

1. Create a new HTML file: `YYYY-trip-name.html`
2. Follow the same structure as `index.html`
3. Update the trips table in this README
4. Commit and push

## 📄 License

MIT
