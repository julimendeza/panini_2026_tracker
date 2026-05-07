# Panini FIFA World Cup 2026 — Sticker Tracker

A bilingual (🇪🇸 / 🇬🇧) standalone HTML sticker tracker for the official Panini FIFA World Cup 2026 album. No installation needed — just open the file in any browser.

---

## How to use

1. Open `Panini_FWC2026_Tracker.html` in any modern browser (Chrome, Firefox, Safari, Edge).
2. Click any sticker box to cycle through three states:
   - **Empty** — you don't have it yet
   - **✓ Green** — you have it (owned)
   - **★ Gold** — you have a duplicate
3. Your progress saves automatically in the browser's localStorage.

---

## Album structure

| Section | Stickers | Notes |
|---|---|---|
| ✦ FWC Intro Foil | 20 | Stickers `00` + `FWC1–FWC19` — all foil |
| 48 Teams × 20 stickers | 960 | Sticker 1 of each team is a foil badge |
| 🥤 Coca-Cola Bonus | 14 | Stickers `CC1–CC14` |
| **Total** | **994** | |

---

## Features

- **Bilingual** — toggle between Spanish 🇪🇸 and English 🇬🇧 at any time
- **3-state tracking** — owned ✓, duplicate ★, missing (empty)
- **Foil sticker animations** — shimmer changes colour with state (green → silver → gold)
- **Team completion** — gold glowing header when all 20 stickers in a team are collected
- **Progress bar** — global % tracker at the top, mini bar per team
- **Filters** — view All / Incomplete / Complete / Not Started
- **Export Progress** — downloads a new copy of the HTML file with your data baked in, so you can transfer it to another device or share with someone
- **Print-friendly** — File → Print works cleanly

---

## Transferring your progress

Your ticks are stored in the browser's `localStorage`, which is tied to the device and browser you're using.

To move your progress to another device:
1. Click **↓ Export Progress** (or **↓ Exportar progreso**)
2. A new HTML file downloads with all your sticker states embedded
3. Open that file on the other device — no setup needed

---

## Team list

The 48 teams follow the official Panini album catalog:

Argentina 🇦🇷 · Algeria 🇩🇿 · Austria 🇦🇹 · Australia 🇦🇺 · Belgium 🇧🇪 · Bosnia and Herzegovina 🇧🇦 · Brazil 🇧🇷 · Canada 🇨🇦 · Cape Verde 🇨🇻 · Colombia 🇨🇴 · Congo DR 🇨🇩 · Croatia 🇭🇷 · Curaçao 🇨🇼 · Czechia 🇨🇿 · Ecuador 🇪🇨 · Egypt 🇪🇬 · England 🏴󠁧󠁢󠁥󠁮󠁧󠁿 · France 🇫🇷 · Germany 🇩🇪 · Ghana 🇬🇭 · Haiti 🇭🇹 · Iran 🇮🇷 · Iraq 🇮🇶 · Ivory Coast 🇨🇮 · Japan 🇯🇵 · Jordan 🇯🇴 · Mexico 🇲🇽 · Morocco 🇲🇦 · Netherlands 🇳🇱 · New Zealand 🇳🇿 · Norway 🇳🇴 · Panama 🇵🇦 · Paraguay 🇵🇾 · Portugal 🇵🇹 · Qatar 🇶🇦 · Saudi Arabia 🇸🇦 · Scotland 🏴󠁧󠁢󠁳󠁣󠁴󠁿 · Senegal 🇸🇳 · South Africa 🇿🇦 · South Korea 🇰🇷 · Spain 🇪🇸 · Sweden 🇸🇪 · Switzerland 🇨🇭 · Tunisia 🇹🇳 · Türkiye 🇹🇷 · Uruguay 🇺🇾 · USA 🇺🇸 · Uzbekistan 🇺🇿

---

## Notes

- Sticker numbers are **relative per section** (1–20 per team), matching the physical album layout
- The team list follows the official Panini catalog; some qualification spots were still subject to playoffs at time of creation
- Data is stored locally — clearing browser data will erase progress (use Export to back up)

---

*Made with Claude · Anthropic · 2026*
