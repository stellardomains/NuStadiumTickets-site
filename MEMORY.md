# NuStadiumTickets.com Project

## Overview
- Domain: NuStadiumTickets.com
- Single-page HTML site (no framework, no build step)
- Affiliate ticket comparison site for Inter Miami CF at Nu Stadium
- Links out to SeatGeek for ticket purchases

## Color Palette — Inter Miami Pink + Black + Gray (logo stays purple)
```
--p1: #E0548E        (deep pink — buttons, accents)
--p2: #F2709C        (mid pink — hover states, gradients)
--p3: #F8A4C8        (pastel pink — text accents, labels)
--p4: #FDCFE0        (light pink)
--p5: #FFF0F6        (near-white pink)
--blk: #0A0A0A       (true black background)
--s1: #111111        (section bg dark)
--s2: #1A1A1A        (card bg)
--s3: #242424        (hover bg)
--s4: #2E2E2E
--s5: #383838
--mu: #7A7A7A        (muted text)
--di: #A8A8A8        (dim text)
--tx: #D9D9D9        (body text)
--wh: #F5F5F5        (headings)
--gold: #F5C842      (prices, ratings)
--teal: #2DD4BF      (MLS tags)
--logo1: #6B21C8     (purple — logo ONLY)
--logo2: #B47AFF     (light purple — logo "Stadium" text ONLY)
```

## Fonts
- **Black Han Sans** — headlines, section names, prices
- **Plus Jakarta Sans** — body, UI, navigation

## Nu Stadium Facts
- **Capacity**: 26,700
- **Location**: 1900 NW 37th Ave, Little Havana, Miami (NOT Fort Lauderdale)
- **Opens**: April 4, 2026 — Inter Miami vs Austin FC, 7:30 PM ET
- **Design**: Multi-tier bowl with upper (200s) and lower (100s) + club + suites

## Seating Sections (from official Ticketmaster virtual venue)
### Upper Bowl (200s) — Blue (#4FC3F7)
- West: 202-214
- East: 225-239
- South: 215-224
- NW corners: 202, 203, 204
- NE corners: 236, 237, 238
- SW corners: 212, 213, 214
- SE corners: 225, 226, 227, 228
- North: 201, 239

### Lower Bowl (100s) — Purple (#8B3FE8 in map)
- West (N→S): 101, 105, 106, 107, 108, 109, 110, 111, 113, 115
- East (N→S): 139, 135, 134, 133, 132, 131, 130, 129, 127, 125
- South: 115, 116, 117, 123, 124, 125, 127

### Club Level (C sections) — Dark Purple (#5B1FA8)
- North: C140, C141, C142, C143, C144, C145, C146, C147, C148, C149
- South: C118, C119, C120, C121, C122

### Supporters — Safe Standing (Brown #C8956E)
- North end: SS26-SS33 (La Familia)
- Groups: The Siege, Vice City 1896, Southern Legion, Nación Rosa y Negro, IMS.MMXX

### Field Suites (Red #E53935)
- FS1-FS18 along north pitchside (ERGO Next Field Level Suites)

### East Field Level (Gold #F5C842)
- East 1, East 2, East 3, East 4 (south pitchside)

### Platinum Suites (Gold #F5C842)
- PS26-PS33 (very top north end)

## Premium Options (official names)
- Pitchside Seats
- ERGO Next Field Level Suites
- East Club
- Nu Club
- West Club
- Loge Boxes
- Audi Executive Level Suites
- Platinum Level Suites

## Site Sections
1. **Nav** — fixed, logo + Schedule/Seat Map/FAQ + Buy Tickets CTA
2. **Countdown strip** — live countdown to April 4 opener
3. **Hero** — "Find Your Perfect Seat" + stats (26.7K, 18 games, $57+, #1)
4. **Schedule** — filterable game list (All/MLS/Cup/Hot), links to SeatGeek
5. **Seat Map** — SVG interactive map with zone pills, tooltip hover, sidebar detail panel with canvas-rendered view preview
6. **Why Us** — 6-card grid
7. **FAQ** — accordion, 2-col grid
8. **Footer** — affiliate disclaimer

## Dev Server
- `python3 -m http.server 8080` from project dir
- http://localhost:8080
