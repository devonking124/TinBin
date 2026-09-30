# Forgeline

A top-down factory-automation game in a single self-contained file: `index.html`.
No dependencies, no assets — all art is drawn on Canvas 2D and all audio is synthesized with Web Audio.

Open `index.html` in any modern browser (desktop or mobile) to play. The game autosaves to localStorage.

Mine ore, pump water and oil, grow crops and trees, move everything on conveyors, and turn it into
118 items — alloys, pottery, paper, food, weapons & ammunition, electronics and nuclear fuel — ending in
**Final Matter**. Sell through eight kinds of market (from a cheap Market Stall to a container-ship Export Terminal, plus
specialist buyers for food, crafts, weapons and tech that pay a premium), take contracts, research five tiers of
tech with Research Points, keep pollution in check, explore caves through underground belts, and
relocate for permanent bonuses.

All content and balance numbers live in the `CONFIG & DATA TABLES` section at the top of the script.

Hand-mining is gated: early on you can only click common ores (iron, copper, coal, stone, sand, clay);
each level of **Better Pickaxes** unlocks pricier ores.

## Handy controls

| Key | Action |
| --- | --- |
| Space | Pause / resume |
| `,` / `.` | Slower / faster (1–3×) |
| U | Upgrade planner: click or drag a box to upgrade everything inside to the next tier |
| N | Jump to the next machine that needs attention (no power, fuel or recipe) |
| Shift+right-click or Ctrl+C | Copy a building's settings (recipe, filter, on/off) |
| Shift+click or Ctrl+V | Paste those settings onto another building |
| `/` | Search buildings |
| Z | Reset zoom |
