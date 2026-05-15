# madebydavid

Personal portfolio site for David Johansson — iOS, web, and AI engineer based in Stockholm.

**Live:** [madebydavid.se](https://madebydavid.se) *(coming soon)*

## What's inside

A single-file static site (`animated-v2.html`) showcasing:

- **RecipeBud** — flagship iOS app, live on the App Store
- **7-Stage Recipe Scraper** — Python/FastAPI backend with Playwright, FFmpeg, GPT-4 Vision
- **Hanna** — voice AI cooking assistant (WebSockets + OpenAI streaming)
- **Client work** — production websites for LD Luxury (Stockholm) and Komplett Bygg (Västerås)

## Tech

- **Vanilla HTML / CSS / JavaScript** — no build step, no framework, no dependencies
- All styling in `<style>` block, all behavior in `<script>` block
- Scroll-snap scenes, IntersectionObserver-driven animations
- Glassmorphism + dynamic typography + custom cursor

## Run locally

```bash
python3 -m http.server 3333
```

Then open [http://localhost:3333/animated-v2.html](http://localhost:3333/animated-v2.html)

## Deploy

Hosted on [Vercel](https://vercel.com). Push to `main` → auto-deploys.

## Easter eggs

- **3 rapid clicks on the `DJ` logo** unlocks hidden stats
- **Konami code** (↑ ↑ ↓ ↓ ← → ← → B A) triggers a hue-shift effect
- **`J` / `K`** or arrow keys to navigate scenes from the keyboard
- **`0`–`4`** to jump to a specific scene

## Contact

- Email — djohansson1515@gmail.com
- GitHub — [@howudoin123](https://github.com/howudoin123)
- LinkedIn — [david-johansson](https://www.linkedin.com/in/david-johansson-1b361a333/)
