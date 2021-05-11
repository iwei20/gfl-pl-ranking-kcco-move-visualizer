# GFL PL Ranking Map 1 KCCO Movement Priority Visualizer

## Why?

Expand AI behavior is weird. It's not consistently predictable when just looking at the map. The hope is that this tool will mimic as closely as possible the underlying logic used for enemy pathing so we don't have to stare at a bunch of JSON like neanderthals.

## How to Install

Just download the thing and open the index.html file in your browser. No internet required. No fancy installation tools. Just browser. Or use [this online version](https://emerald-devel.github.io/gfl-pl-ranking-kcco-move-visualizer/index.html). Whatever floats your boat.

## How to Use

- Left-click a node to change its faction ownership.
- Right-click a node to mark it as being occupied by a mob. One click gives it a normal mob (small dot) and a second click gives it a deathstack (large dot).
- Ctrl + right-click a node to mark it as being occupied by an ally. One click gives it an NPC (small dot) and a second click gives it a deployed echelon (large dot).
- Once you have your map in the desired state, just click the big orange button. This will show the expected enemy turn movements. Clicking elsewhere will revert back to the pre-calculation view.
- Importing and exporting of the map state can now be done via standard copy and paste shortcuts. Simply use Ctrl+C to copy the map state and Ctrl+V to restore from a map state currently stored in your clipboard.

## Disclaimer

Requires field testing. The pathing calculated is based on assumptions derived from experiments, not on any actual reverse-engineering or dev-verified information. Discrepancies may exist. Use at your own risk.

## Other

Want to help improve this? Write some code and make a pull request. If it's a valuable update, I'll probably approve it. Just try to keep the no-internet thing working.
