# Forgeline

A top-down factory-automation game in a single self-contained file: `index.html`.
No dependencies, no assets — all art is drawn on Canvas 2D and all audio is synthesized with Web Audio.

Open `index.html` in any modern browser (desktop or mobile) to play. The game autosaves to localStorage.

Mine ore, pump water and oil, grow crops and trees, move solids on conveyors and liquids through pipes, and turn it into
200+ items — alloys, pottery, paper, food, weapons & ammunition, electronics and nuclear fuel — ending in
**Final Matter**. Sell through eight kinds of market (from a cheap Market Stall to a container-ship Export Terminal, plus
specialist buyers for food, crafts, weapons and tech that pay a premium), take contracts, research five tiers of
tech with Research Points, keep pollution in check, explore caves through underground belts, and
relocate for permanent bonuses.

All content and balance numbers live in the `CONFIG & DATA TABLES` section at the top of the script.

Hand-mining is gated by pickaxe research — Iron (tier I), Steel (II: cobalt), Titanium (III: gold),
Diamond (IV: uranium) and Orichalcum (V: mystic ores). Caves start sealed: **Cave Expedition** opens them
for rare minerals, and **Abyssal Descent** opens the deepest caves where orichalcum, adamantite, mythril and
aether glow.

Highlights: crude oil heaters and fractional separators (diesel & gasoline), fracking, liquid metallurgy
(melt metals and pour them into a Liquid Alloyer), cars, trucks and electric cars, LEDs and lasers, laser
drills, a Game Studio factory with presets, Mk2 versions of most buildings, waste that costs money to dump,
smog that slows crops, a Machine Index, Hard/Impossible Eco Quests, a relocation token shop, map sizes up
to 2048², and themes, accent colours, cursors and terrain palettes in Settings.

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
| H | Item Dex & Machine Index |
