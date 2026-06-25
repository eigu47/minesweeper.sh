# Minesweeper.sh

Minesweeper clone that runs in a terminal.
Only with Bash.

## Quick start

```bash
curl eiguchipablo.dev/minesweeper | bash
```

### Optional arguments

- `-h` – show the help/controls screen.
- `-s WIDTHxHEIGHT` – choose the board size (default `8x8`).
- `-m MINES` – set the mine count (default `10`).

### Controls

- Arrow keys or `WASD` – move the cursor (wraps around the edges).
- `Space` or `Enter` – reveal the tile under the cursor.
- `R` – restart the board.
- `Ctrl+C` – quit game.
