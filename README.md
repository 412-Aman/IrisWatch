# 🔮 IrisWatch

**Real-time global intelligence & finance dashboard** — a curated world monitor built with a lavender & beige aesthetic.

Live news streams, market data, economic indicators, geopolitical intelligence, and AI-powered analysis — all in one view.

---

## ✨ Features

| Category | What's included |
|----------|----------------|
| **Live News** | Al Jazeera, Bloomberg, Sky News — live video streams |
| **Markets** | Real-time stock quotes, commodities, sector heatmap |
| **Finance** | Economic indicators, trade policy, supply chain tracking |
| **Crypto** | BTC ETF Tracker, stablecoins, crypto markets |
| **Intelligence** | Strategic risk overview, intel feeds, live intelligence |
| **AI Insights** | AI strategic posture, predictions, threat analysis |
| **Global** | Regional news (US, Europe, Middle East, Africa, Asia) |
| **Map** | Interactive globe with military bases, earthquakes, protests, flights |

## 🎨 Design

Custom **lavender & beige** color palette:
- 🌙 Dark mode — dusky plum backgrounds with warm cream text
- ☀️ Light mode — warm beige with lavender accents

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Copy env template and add your API keys
cp .env.example .env.local

# Start dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## 🔑 API Keys

All keys are free. Add them to `.env.local`:

| Key | Source | Powers |
|-----|--------|--------|
| `GROQ_API_KEY` | [console.groq.com](https://console.groq.com) | AI insights & strategic posture |
| `FINNHUB_API_KEY` | [finnhub.io](https://finnhub.io) | Stock & commodity data |
| `FRED_API_KEY` | [fred.stlouisfed.org](https://fred.stlouisfed.org/docs/api/api_key.html) | Economic indicators |
| `EIA_API_KEY` | [eia.gov/opendata](https://www.eia.gov/opendata/) | Energy & oil prices |
| `OPENROUTER_API_KEY` | [openrouter.ai](https://openrouter.ai) | AI fallback |
| `UPSTASH_REDIS_*` | [upstash.com](https://upstash.com) | Cross-user caching |
| `CLOUDFLARE_API_TOKEN` | [dash.cloudflare.com](https://dash.cloudflare.com) | Internet outage data |

## 🌐 Deploy to Vercel

1. Push this repo to GitHub
2. Import at [vercel.com](https://vercel.com)
3. Add your API keys as environment variables
4. Deploy — done!

The project includes `vercel.json` with all API routes pre-configured.

## 📦 Tech Stack

- **Frontend**: TypeScript, Vanilla JS, CSS custom properties
- **Build**: Vite 6
- **Maps**: deck.gl / MapLibre
- **APIs**: Finnhub, FRED, EIA, Groq, CoinGecko, USGS, NASA EONET
- **Hosting**: Vercel (free tier)

---

Built with 💜 by [412-Aman](https://github.com/412-Aman)

Based on [worldmonitor](https://github.com/elie/worldmonitor)
