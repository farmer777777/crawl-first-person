# Crawl First Person — browser build

Play: **https://farmer777777.github.io/crawl-first-person/**

An unofficial first-person adaptation of **Dungeon Crawl Stone Soup 0.34.1**,
compiled to WebAssembly so it runs in a desktop browser (Chrome, Edge,
Firefox). Saves stay in your browser (IndexedDB); clearing site data deletes
them.

## Controls

| Input | Action |
| --- | --- |
| Click the game | Lock the mouse (mouse look) |
| Esc | Release the mouse lock (browser standard) |
| Mouse / WASD | Look / move |
| Left click | Attack |
| Right click | Toggle the menu cursor (original commands and menus) |
| E | Interact: doors, stairs, hatches, shafts, items |
| 1–8 | Quickslots |
| Q | Next visible enemy |
| Hold Tab | Look behind |

The game is turn based underneath. Moving, attacking and casting advance
time by their native action costs; while an awake enemy is in view, time
also passes slowly when you stand still.

## Source

The engine is GPL v2 or later. The corresponding source for this build
(modified Crawl source, first-person renderer, web build scripts) is
attached to the [releases](../../releases) of this repository; see
`FIRST-PERSON.md` inside it for build instructions. The
original first-person project and its Windows builds:
https://github.com/gjinnovation3rd-prog/kunjang-aidx-crawl-first-person

## Credits and licences

- Dungeon Crawl Stone Soup, its team and contributors (GPL v2+):
  `licenses/CREDITS.txt`, `licenses/LICENSE.txt`.
- Weapon art: Diverse Weapons by RealAKP (`licenses/diverse-weapons.txt`).
- Noto Sans KR (SIL OFL, `licenses/NotoSansKR-OFL.txt`).
- Lua, libpng, PCRE and other components: see `licenses/`.
- Sound effects are synthesised by a script in the source; no third-party
  audio is included.

This is an unofficial adaptation. No endorsement by the DCSS team or the
asset authors is implied.
