# Ninjas — Greenhouse Gas (GHG) Monitoring & Emissions Visualization Platform

**Ninjas** is a greenhouse gas (GHG) monitoring and data visualization platform built during a hackathon competition. Built with **Next.js**, **deck.gl**, **Three.js**, and **Leaflet**, it turns emissions data into interactive maps, a 3D globe, and rich charts — making climate data easy to explore and understand.

## Features

- **Interactive emissions maps** — geospatial visualization of greenhouse gas data with deck.gl geo-layers, Leaflet, and React Simple Maps
- **3D globe view** — explore emissions on an interactive Three.js globe (`three-globe`, React Three Fiber)
- **Data dashboards & charts** — emissions trends and breakdowns rendered with Chart.js, Recharts, and D3.js
- **CSV data support** — parse and load emissions datasets directly from CSV files with PapaParse
- **Modern, animated UI** — Framer Motion animations, Tailwind CSS + daisyUI styling, and React Icons

## Tech Stack

- **Framework:** Next.js 14 + React 18
- **Language:** JavaScript
- **Mapping & 3D:** deck.gl, Leaflet / React Leaflet, React Map GL, React Simple Maps, Three.js, three-globe
- **Charts & Data:** Chart.js, Recharts, D3.js, PapaParse, Axios
- **Styling:** Tailwind CSS + daisyUI

## Getting Started

Install dependencies and run the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

Other scripts:

```bash
npm run build   # production build
npm run start   # serve the production build
npm run lint    # run ESLint
```

---

⭐ If you find this project useful, consider giving it a star — contributions and feedback are welcome!
