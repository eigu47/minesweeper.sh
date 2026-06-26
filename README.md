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
- `-f` - set full screen size board.
- `-m MINES` – set the mine count (default `10`).
- `-p PERCENT` - set mines to a percentage of total tiles.

If you want to pass options when piping from `curl`, append them after `bash -s --`, like this:
```bash
curl eiguchipablo.dev/minesweeper | bash -s -- -s 16x16 -m 40
```

### Controls

- Arrow keys or `WASD` – move the cursor (wraps around the edges).
- `Space` or `Enter` – reveal the tile under the cursor.
- `R` – restart the board.
- `H` - show help/controls.
- `Ctrl+C` – quit game.
