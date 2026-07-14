# Aviation Vibe-Coding Showcase — Build Prompt

Paste this whole file to your coding assistant. It asks the assistant to build a batch of small aviation-themed demo projects that showcase the range of what "vibe coding" can produce in a 3-hour, beginner, HTML/CSS/JS-only workshop.

## Context for the assistant

I'm prepping a 3-day "vibe coding" workshop for beginner students (mostly aviation majors, some Software Engineering) at an academic tourism program. Students will use Gemini (gemini.google.com) with Canvas to describe an app in plain English and get a live HTML/CSS/JS preview — no installs, no frameworks, no build tools.

Before running the workshop, I want a showcase set of example projects to demo "look what's possible," all staying in the aviation theme but spanning different *types* of apps — a simple game, an informational reference, a practical tool, and a fun personal page — not just one format repeated four times.

## Hard constraints (apply to every project below)

- **HTML/CSS/JS only** — a single, self-contained `.html` file per project. Inline `<style>` and `<script>`, no external libraries, no npm, no build step.
- **Must run by opening directly in a browser** and by pasting into Gemini Canvas — no server, no APIs, no external data fetches.
- **Beginner-readable code** — clear variable names, short functions, a few plain-English comments explaining each section. Assume the person reading it has never coded before.
- **Aviation-themed** — every project should feel like it belongs in an aviation/airport world (aircraft, airports, flight, ATC, pilots, checklists, etc.), even the silly ones.
- **Playable/usable in under a minute**, no login, no setup screens.
- **Visually clean but simple** — a title, a bit of color, legible text. Don't over-engineer the styling; this needs to look achievable by a first-time coder in a couple of prompts.

## Deliverable

Build one HTML file per project below, named as indicated, plus a short `README.md` that lists all projects with a one-line description of each (for me to skim before the workshop).

---

## Project 1 — Game: "Landing Challenge"
**File:** `landing-challenge.html`
**Category:** Simple game (Day 2 style)

A short timing/reflex game: a plane descends toward a runway and the player clicks/taps (or presses spacebar) at the right moment to "land" it smoothly. Track a score or streak ("Perfect landing!" / "Bounced!" / "Go around!"). Keep the whole game on one screen, no scrolling, restart button when it ends.

## Project 2 — Game: "Which Aircraft Are You?" Quiz
**File:** `aircraft-personality-quiz.html`
**Category:** Quiz/game (Day 2 style)

A 5-question personality quiz ("Do you prefer speed or comfort?", "Window or aisle?", etc.) that maps answers to a result: Cessna 172, Fighter Jet, Boeing 747, or Glider — each with a fun one-paragraph description and an emoji/icon. Show a progress bar across the questions and a "play again" button at the end.

## Project 3 — Informational: "Aircraft 101" Flip-Card Encyclopedia
**File:** `aircraft-101.html`
**Category:** Informational reference (Day 1/3 style)

A grid of 6–8 flip cards, each showing an aircraft type on the front (e.g., Boeing 737, Airbus A320, Cessna 172, Boeing 747, fighter jet, helicopter) and 2–3 quick facts on the back when clicked/tapped. Pure CSS flip animation, no images required (use emoji or simple CSS shapes as icons).

## Project 4 — Informational: Phonetic Alphabet Trainer
**File:** `phonetic-alphabet-trainer.html`
**Category:** Informational / practice tool (Day 3 style)

Shows a random letter (A–Z) and the student types or picks the correct NATO phonetic word (Alpha, Bravo, Charlie...). Give instant feedback (correct/incorrect), keep a running score, and a "next letter" button. Optional: a reference table below the game showing the full alphabet.

## Project 5 — Practical Tool: Pre-Flight Checklist
**File:** `preflight-checklist.html`
**Category:** Practical tool (Day 3 style)

A checklist of 8–10 common pre-flight items (seatbelt sign, fuel check, weather briefing, etc.) as checkboxes, with a progress bar that fills as items are checked and a "Cleared for takeoff!" message when 100% complete. Include a reset button.

## Project 6 — Practical Tool: Flight Time & Unit Converter
**File:** `flight-tools.html`
**Category:** Practical tool (Day 3 style)

A small two-in-one utility: (1) enter distance + speed to calculate flight time, and (2) convert between knots/km-h and feet/meters. Simple form inputs, instant calculation on input change (no submit button needed), clear labeled results.

## Project 7 — Fun/Personal: Boarding Pass Profile Generator
**File:** `boarding-pass-profile.html`
**Category:** Personal/fun (Day 1 style)

A form where a student types their name, a dream destination, and picks a "seat," then generates a stylized boarding-pass card below (or replaces the form) with that info, a fake flight number, and a barcode-style visual (CSS stripes are fine, no real barcode needed). Include a "download as image" nice-to-have if easy, otherwise skip.

## Project 8 — Mini-Simulation: Cockpit Dashboard Toy
**File:** `cockpit-dashboard.html`
**Category:** Interactive toy (stretch/demo piece)

A playful, non-functional "cockpit panel" with a few clickable switches/buttons that light up or toggle state, an altitude readout that animates up/down via a slider, and a throttle slider that changes an on-screen speed number. No real flight logic — purely a satisfying, clicky interactive demo piece.

---

## Also produce

- `README.md` — one line per project (name, file, category, one-sentence description) so I can skim the showcase before the workshop.
- Keep each HTML file under ~150 lines where possible, so it's easy to project on a screen and walk through with students without scrolling forever.
