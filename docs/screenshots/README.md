# Leaderboard Mascots — validation screenshots

Captured from a real PinSheet server (two seeded users) with this plugin
loaded, driven by headless Google Chrome. They show the plugin executing on
The Board (`/`): a deterministic pixel mascot + golf-pun nickname per player, a
gold crown on the rank-1 leader, and the mobile board-card layout.

### Desktop — standings table
![desktop board](https://raw.githubusercontent.com/malcolm-x-evo/pinsheet-leaderboard-mascots/main/docs/screenshots/board-desktop.png)

### Close-up — crown + nicknames
![closeup](https://raw.githubusercontent.com/malcolm-x-evo/pinsheet-leaderboard-mascots/main/docs/screenshots/board-closeup.png)

### Mobile — board cards
![mobile board](https://raw.githubusercontent.com/malcolm-x-evo/pinsheet-leaderboard-mascots/main/docs/screenshots/board-mobile.png)

Programmatic evidence from the same run: 4 row mascots, all with drawn
(non-transparent) pixels; `aria-label`s `"mascot: The Closer"` (leader) and
`"mascot: Duffer"`; computed mascot width 26px (size-token fallback).
