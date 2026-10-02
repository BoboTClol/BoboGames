# Petal Arena

- Game is a single file: `petal-arena-v3_4.html`.
- Version gate: `GAME_VER` constant (search `const GAME_VER=`). When the user asks to bump/release the version, increment it by 0.1 (it is a plain number, so 4.9 goes to 5, not 4.10), commit and push to the working branch. Older builds then lock themselves.
