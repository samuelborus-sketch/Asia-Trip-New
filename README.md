# Sam's Asia Trip 2025 — Parent Dashboard

A single-page travel dashboard built for my parents to follow along on my Southeast Asia trip — **May 30 to June 25, 2025**.

**Live site:** [your-url-here.pages.dev](https://your-url-here.pages.dev)

---

## What's on the dashboard

- **Live countdown** to departure (switches to "Day X of 25" during the trip, then "Trip Complete!")
- **Day-by-day timeline** — all 26 days with activities, color-coded by destination
- **Budget tracker** — paid vs. estimated spending with an animated progress bar
- **Editable trip info** — password-protected panel to post status updates for parents (saves to browser localStorage)
- **Need to Know** — emergency contacts, accommodation list, all 6 flights, entry requirements

## Destinations

| Color | Destination |
|-------|-------------|
| 🟣 Purple | Bangkok, Thailand |
| 🟢 Green | Chiang Mai, Thailand |
| 🔵 Blue | Hanoi + Ha Giang, Vietnam |
| 🟣 Pink | Phuket, Thailand |
| 🟢 Teal | Bali, Indonesia |

## Tech

Pure HTML/CSS/JS — no frameworks, no build step, no dependencies (except Google Fonts).
Works fully offline once loaded. Deploys as a static site on Cloudflare Pages.

## Updating trip info

Open the site → scroll to **Update Trip Info** → enter password `sam2025` → fill in the status message or any missing booking details → Save. Changes persist in localStorage on that device.
