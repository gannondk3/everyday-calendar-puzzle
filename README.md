# Everyday — a wooden calendar puzzle, on screen

A single-file, dependency-free web version of the classic wooden "everyday calendar" puzzle: cover every cell on the 7×7 board **except** today's month and day using 8 fixed pieces (seven pentominoes and one hexomino).

**[Play it live](#)** *(link becomes active once GitHub Pages is enabled — see below)*

## Features

- 🗓️ Solves for any date, not just today — pick one with the date field
- 🧩 Tap a piece then tap the board to place it, or drag it directly
- ↔️ Rotate and flip pieces with buttons, or arrow keys (← → rotate, ↑ ↓ flip)
- 🤖 "Solve for me" — a backtracking exact-cover solver finds a valid layout instantly
- 📱 Touch-friendly, with auto-scroll while dragging near the screen edge
- 🪵 No frameworks, no build step, no dependencies — it's one HTML file

## Verified solvable

Every one of the 366 possible dates (including Feb 29) was checked computationally with a backtracking exact-cover solver before shipping, so the puzzle is always solvable, and "Solve for me" will always succeed.

## Running it

Just open `index.html` in a browser — locally, or hosted anywhere.

## Deploying with GitHub Pages

1. Push this repo to GitHub (see below).
2. Go to **Settings → Pages** in the repo.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — your game will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## License

MIT — see [LICENSE](LICENSE).
