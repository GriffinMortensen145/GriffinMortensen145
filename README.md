# Sounding

A 2D mining and survival roguelike that runs in the browser. You're a miner cut off at the top of a procedurally generated cave system. It's pitch dark, and the creatures down here hunt by sound. Your scanner sends out echo pulses that show the walls for a few seconds, but every pulse can be heard.

**Play:** https://griffinmortensen145.github.io/GriffinMortensen145/

## How it plays

- **Echo scanning.** Space sends a pulse. Quiet (1) shows a small area and barely makes noise, Normal (2) shows more, and Powerful (3) lights up a huge area and wakes everything nearby.
- **Noise and light.** Footsteps, digging, fighting and pulses are all noise. Crawlers and burrowers track sound, shriekers and stalkers are drawn to your headlamp, and shriekers scream to call others when they spot you. Shift lets you sneak silently.
- **Mining.** Dig through rock for copper, iron, quartz and cobalt. Hard strata separate each zone, so you need a better pickaxe to get through.
- **Stations.** Build stations to recharge, heal, bank ore and craft. Creatures won't come near them. If you die, you're recalled to your deepest station, which burns out, and the ore you were carrying is lost. With no station, the run is over.
- **Crafting.** Upgrade your pickaxe, scanner, headlamp, battery, armor and ore pack, and make ladders, glowsticks, decoy chimes, stun charges and medkits.
- **Five zones.** Upper tunnels, deep stone, crystal hollows, the magma deep, and the hollow at the bottom, where something is waiting.

## Controls

| Key | Action |
| --- | --- |
| A / D | Move (Shift to sneak) |
| W / S | Jump, climb ladders |
| Space | Echo pulse |
| 1 / 2 / 3 | Quiet, normal or powerful pulse |
| Left mouse | Dig, attack |
| Right mouse | Place selected item |
| Q or mouse wheel | Change selected item |
| F | Headlamp on or off |
| G | Throw decoy chime |
| E | Stun charge |
| R | Medkit |
| C | Craft (at a station) |
| Esc | Pause |
| M | Mute |

Every run uses a new seed. Type a seed on the title screen to replay a specific cave.

The whole game is one file, `index.html`, with no build step.
