# Petal Arena

- Game is a single file named `petal-arena-v<GAME_VER>.html` (currently `petal-arena-v5.2.html`).
- Version gate: `GAME_VER` constant (search `const GAME_VER=`). When the user gives a version (or asks to bump it), set `GAME_VER` to that number (bump = +0.1; it is a plain number, so 4.9 goes to 5, not 4.10), rename the file with `git mv` to `petal-arena-v<version>.html`, commit and push to the working branch. `NEWEST_URL` is the fixed repo link `https://github.com/BoboTClol/BoboGames/`; do not change it on version bumps. Older builds then lock themselves.
