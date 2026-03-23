# Battle of Brains

A live scoreboard web app for quiz competitions and team battles. Create teams, track scores round by round, and display an animated leaderboard on the big screen.

## Features

- **Custom Teams** — Add any number of teams with custom names before starting
- **Live Scoreboard** — Animated rankings that reorder in real-time as scores change
- **Round Tracking** — Advance through rounds with per-round score history
- **Configurable Points** — Set custom correct/wrong point values
- **Undo Support** — Revert the last score action per team
- **Edit Names** — Rename teams on the fly during the game
- **Auto-Save** — Game state is saved to localStorage and can be resumed
- **Export CSV** — Download scores as a CSV file

## Tech Stack

- [Vue 3](https://vuejs.org/) (CDN)
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- Single HTML file — no build step required

## Usage

1. Open `src/battle_of_brains.html` in a browser
2. Add teams and click **Start Battle**
3. Use the admin panel to give/deduct points each round
4. The scoreboard updates and animates automatically

## Deploy

Host as a static site on GitHub Pages, Netlify, or any static hosting provider.
