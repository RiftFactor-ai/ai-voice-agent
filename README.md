# AI Voice Agent - Portfolio Demo

A single-page demo/landing page showcasing AI-powered voice agents for businesses. Built as a portfolio piece for **RiftFactor**, an AI agency specializing in conversational AI solutions.

## What It Demonstrates

- **AI Voice Agent Concept** -- An always-on virtual receptionist that answers calls, books appointments, handles FAQs, routes calls, and speaks 30+ languages.
- **Industry-Specific Conversations** -- Pre-built example dialogues for dental offices, law firms, real estate, restaurants, and auto repair shops.
- **Clear Value Proposition** -- 48-hour deployment, transparent pricing, no per-minute fees.

## Features

- Hero section with interactive phone mockup showing a live AI conversation
- Six capability cards (24/7 answering, booking, FAQs, routing, multilingual, analytics)
- Three-step "How It Works" flow
- Five industry cards with realistic sample conversations
- Three-tier pricing (Starter $299/mo, Professional $599/mo, Enterprise custom)
- CTA section with email and phone actions
- Smooth scroll navigation with fade-in animations (Intersection Observer)
- Fully responsive (mobile-first)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | Semantic HTML5 |
| Styling | Tailwind CSS (CDN) |
| Icons | Lucide Icons (CDN) |
| Typography | Inter (Google Fonts) |
| Animations | CSS transitions + Intersection Observer API |
| Build Tools | None -- zero dependencies, static file |

## Running Locally

Open `index.html` in any modern browser. No build step, no server required.

```bash
open index.html
# or
python3 -m http.server 8000  # then visit http://localhost:8000
```

## Design Decisions

- **Dark theme** with indigo/purple accent palette -- conveys technical sophistication
- **Phone mockup** in the hero section -- immediately communicates "voice/phone" without relying on stock photos
- **Real conversation examples** per industry -- prospects can see themselves using the product
- **No emoji as UI icons** -- Lucide icons throughout for a professional, consistent look
- **Minimal JavaScript** -- only Lucide initialization and scroll-triggered fade animations

## Brand

**RiftFactor** -- AI agency that builds and deploys custom AI agents for businesses.

- Primary accent: Indigo/purple gradient (`#6366f1` to `#a78bfa`)
- Background: Near-black (`#0a0912` / `#0f0d1a`)
- Typography: Inter, weights 300-900
- Logo mark: Zap icon in gradient square

---

Built by RiftFactor.
