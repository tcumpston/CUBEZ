# Changelog

## 1.0.1 — 27 August 2026

First public release for Windows. CUBEZ has been playable in a browser at
wombyland.com; this is the same game as a native download.

**The game**

- A word game in three dimensions: build straight lines of lettered cubes
  through open space, along any of the three axes.
- Crossword rules in the round — every word a move creates must be valid, not
  only the line you meant to build. Invalid moves are rejected and cost nothing.
- One point per letter, counting cubes already on the board as well as the ones
  you place. Two bonus points for a word that also reads validly backwards,
  including palindromes.
- Wildcard cubes that can stand for any letter, fixed once placed.
- Play against the machine at four difficulties: Easy, Medium, Hard, Nightmare.
- A 172,822-entry dictionary from the public-domain ENABLE word list, driving
  both word validity and the machine's difficulty ranking.
- Definitions from WordNet, shown when the machine plays a word.
- `CHECK` panel for looking a word up without spending your turn.
- Free camera orbit around the play space, and right-click to spotlight a
  single word while everything else fades.
- Undo, per-cube take-backs, and tray rearrangement before committing a move.

**Known limitations**

- The game is not code-signed, so Windows SmartScreen will warn on first run,
  and Smart App Control may block it outright. See the README.
- No application icon yet; the game uses the default Unity icon.
- The window is fixed at 1920 x 1080 full screen and is not resizable.
