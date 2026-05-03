# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A zero-dependency browser clock (`index.html`) that tells time through icons:

- **Central icon** – one of 24 clock-face emoji (🕐–🕛 on the hour, 🕜–🕧 on the half-hour) matching the current hour and whether the minute is before or after :30.
- **Minute ring** – SVG ring of 60 markers. Quarter-hour positions (0, 15, 30, 45) are rendered as diamond shapes; 5-minute marks as circles; individual minutes as small circles. Past minutes glow blue, the current minute glows red with a soft halo.
- **Period icon** – emoji reflecting time of day: 🌙 night → 🌅 dawn → ☀️ day → 🌤️ midday → 🌆/🌇 evening.
- **Day icon** – planetary day symbols (☀️ Sun, 🌙 Mon, 🔥 Tue, 💧 Wed, ⚡ Thu, 💫 Fri, 🪐 Sat).

## Running

Open `index.html` directly in a browser — no build step, no server, no dependencies.
