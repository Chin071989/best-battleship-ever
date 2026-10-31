# Best Battleship Ever

A single-file browser version of Battleship. No install or build step: open `index.html` in any modern browser.

## Features
- 10x10 boards with the classic fleet: Carrier (5), Battleship (4), Cruiser (3), Submarine (3), Destroyer (2)
- Manual ship placement (hover preview, `R` to rotate, click a placed ship to move it) or Randomize
- Computer opponent with Easy, Normal, and Hard (probability-based targeting) difficulty
- Animated ocean boards, splash markers for misses, and full hull reveal for sunk ships
- Synthesized "boom" sound effects on hits (bigger blast when a ship sinks)
- Original looping pirate-style background music during battle, or load your own music file
- Shot, hit, and accuracy stats for both sides

## Play
Open `index.html` directly, or serve the folder locally:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```
