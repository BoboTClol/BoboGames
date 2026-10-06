# Petal Arena

- Game is a single file: currently `petal-arena-v7.html` (this is the file the user supplied as "v7"; its `GAME_VER` is 8 — the user has not said which numbering to keep, so ask before renaming/bumping).
- Version gate: `GAME_VER` constant (search `const GAME_VER=`). When the user gives a version (or asks to bump it), set `GAME_VER` to that number (bump = +0.1; it is a plain number, so 4.9 goes to 5, not 4.10), rename the file with `git mv` to `petal-arena-v<version>.html`, commit and push to the working branch. `NEWEST_URL` is the fixed repo link `https://github.com/BoboTClol/BoboGames/`; do not change it on version bumps. Older builds then lock themselves.
- The user (and a co-founder) sometimes edit the game file themselves and re-upload it. Treat the newest uploaded file as the base, diff it against the repo copy first, and keep their changes.
