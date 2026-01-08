# CLAUDE.md - AI Assistant Guide for KAB Studio

## Overview

**KAB Studio** is a creative development studio that builds apps, games, and digital experiences. We create in public through streaming and content, building community while shipping products.

**Parent Brand of:**
- **Food KAB** - Food delivery platform (separate repo: `food-kab-nexus-elite`)
- **KAB Games** - Browser and native games (KAB Rush, Tower Defense, etc.)
- **Client Work** - Custom development for businesses

**Content Platforms:**
- **YouTube** - Long-form streams and VODs of building sessions
- **YouTube Shorts** - Clips from streams
- **TikTok** - Short-form clips and highlights
- **Skool** - Community and educational content

---

## Business Information

**Legal Entity:** The Food KAB LLC (DBA: KAB Studio, Food KAB)

**Contact:**
- **Business:** (214) 984-3346

**Location:** Springtown, TX area

---

## Repository Structure
kab-studio/
├── CLAUDE.md # This file - AI assistant guide
├── README.md # Public project overview
├── ROADMAP.md # Vision, phases, priorities
│
├── website/ # KAB Studio main website
│ ├── webflow/ # Webflow embed files
│ └── assets/ # Images, icons
│
├── games/ # KAB Games collection
│ ├── kab-rush/ # 3-lane dodging game
│ └── tower-defense/ # 4-player co-op (planned)
│
├── streaming/ # Streaming infrastructure
│ ├── obs/ # Scene collections, profiles
│ ├── overlays/ # Stream graphics
│ └── privacy-checklist.md # What to hide during streams
│
├── content/ # Content strategy & assets
│ ├── skool/ # Community structure
│ ├── youtube/ # Channel setup
│ └── tiktok/ # Strategy notes
│
├── brand/ # Brand assets & guidelines
│ ├── logos/ # KAB Studio logos
│ └── colors.md # Official color palette
│
└── clients/ # Client project templates

---

## Brand Guidelines

### Colors

| Name | Hex | Usage |
|------|-----|-------|
| **KAB Gold** | `#ffc805` | Primary accent, CTAs, highlights |
| **KAB Purple** | `#8b5cf6` | Secondary accent, gradients |
| **Dark BG** | `#0a0a0f` | Primary background |
| **Dark Surface** | `#12121a` | Cards, elevated surfaces |

### Design Style
- **Theme:** Dark mode with neon accents (Tron/Cyber aesthetic)
- **Effects:** Glassmorphism, glows, subtle gradients
- **Typography:** Clean sans-serif (Inter, system fonts)

---

## Games

### KAB Rush (Complete)
**Type:** 3-lane endless dodger
**Platform:** Web (HTML5 Canvas)
**Files:** `games/kab-rush/`

### Tower Defense (Planned)
**Type:** 4-player co-op tower defense
**Platform:** PC/Web (Godot 4)
**Inspiration:** CoD Zombies + WotLK defense

---

## Streaming Setup

### Content Pipeline
Long Stream Session (2-4 hours)
│
▼
YouTube VOD (full archive)
│
├──► Clips (5-15 min) ──► Skool Lessons / YouTube Videos
│
└──► Shorts (30-60 sec) ──► YouTube Shorts / TikTok


### OBS Hotkeys (Suggested)
| Key | Action |
|-----|--------|
| F9 | Toggle Privacy Mode |
| F10 | BRB Scene |
| F11 | Main Scene |
| F12 | Mute/Unmute Mic |

### Privacy - ALWAYS HIDE:
- `.env` files and API keys
- Supabase/Square dashboards
- Customer data (names, addresses, phones)
- Personal accounts (email, banking)
- Client project details

---

## Related Repositories

| Repo | Purpose |
|------|---------|
| `food-kab-nexus-elite` | Food KAB delivery platform |
| `kab-studio` | This repo - studio brand, games, content |

---

*Last updated: January 8, 2026*

