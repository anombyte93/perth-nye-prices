# Perth NYE 2025 Price Comparison Dashboard

## Overview
Interactive price comparison dashboard for Perth New Year's Eve 2025 events, with focus on Ice Cream Factory (ICF) vs 48 competing events.

## Project Structure
```
perth-nye-prices/
├── index.html          # Main dashboard (TailwindCSS + Chart.js)
├── data/
│   └── prices.json     # All event pricing data
├── CLAUDE.md           # This file
└── README.md           # GitHub readme
```

## Key Findings

### Ice Cream Factory NYE 2025
- **Event**: NYE x ICF: OUTDOOR
- **Price Range**: $53.58 - $148.03
- **Time**: 6pm - 1am
- **Location**: Northbridge (92 Roe St)
- **Includes**: Multiple stages, national/international acts, Carlton Dry Pub, Red Bull Cabana, McDonald's Silent Disco, fireworks

### Price Distribution
| Category | Count | Avg Starting Price |
|----------|-------|-------------------|
| Free | 10 | $0 |
| Festival | 8 | ~$73 |
| Bottomless | 12 | ~$75 |
| Bar | 8 | ~$30 |
| Club/Bar | 4 | ~$32 |
| Premium | 4 | ~$166 |
| Dining | 5 | ~$83 |

### ICF Comparison
- **25 events** cheaper than ICF ($53.58)
- **12 events** similar price range ($50-$150)
- **11 events** more expensive than ICF max ($148+)

### Best Value Options
1. **FREE**: Elizabeth Quay - Roving performers, DJ, food trucks, 2x firework shows
2. **Bottomless**: Scarborough Beach Bar $69 - 2hr bottomless + share plates + DJs
3. **Festival**: ICF OUTDOOR from $53.58 - Perth's biggest summer festival

## Data Sources
- Ice Cream Factory official: icfpresents.com.au / hottestsummerever.com
- Eventbrite Australia
- Perth Is OK!
- The Urban List Perth
- Megatix / Moshtix
- Individual venue websites

## Research Date
December 10, 2025

## Deployment
Dashboard designed for GitHub Pages deployment:
```bash
gh repo create perth-nye-prices --public
git add . && git commit -m "Initial dashboard"
git push origin main
# Enable Pages in repo settings
```

## Tech Stack
- TailwindCSS (CDN)
- Chart.js (CDN)
- Vanilla JavaScript
- Static HTML (no build required)
