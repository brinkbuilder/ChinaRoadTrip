# Salt & Starlight — Qinghai + Gansu Road Trip

A self-contained, English road-trip planner for two people. It includes a 13-day full-route itinerary, booking and packing checklists, a budget tracker, practical trip notes, and a small couples' memory journal.

## Open it locally

This is a static site with no install step or build process.

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

For a local web server instead, run this from the repository folder:

```powershell
npx serve .
```

Then open the address printed in the terminal.

## Update the site

Edit `index.html`, test it locally, then publish the change:

```powershell
git add index.html
git commit -m "Update road trip planner"
git push
```

The checklists, budget, names, countdown date, and memories are stored only in each visitor's browser using local storage. They are not saved to GitHub or the hosting provider.

## Hosting

This repository is configured for static hosting:

- **GitHub Pages:** publish from the `main` branch and `/ (root)` folder.
- **Vercel:** import `brinkbuilder/ChinaRoadTrip`, leave the framework preset as **Other**, and deploy. Every push to `main` can deploy automatically.

There are no environment variables, API keys, databases, or paid services required.
