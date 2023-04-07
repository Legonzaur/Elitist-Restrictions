# Legonzaur.ElitistRestrictions

Mod for Titanfall2's Northstar

Begone Campers

Begone SMGs

Don't roast me on this

## convars

### Loadout

- `remove_melee 0` Completely removes the ability to melee, even with a grapple
- `force_weapons 0` Replaces SMGS + Assault Rifles by a Kraber and RE45 by a B3 Wingman
- `patch_weapons 0` Modifies some weapons (mostly antititan) to make them stronger against pilots
- `force_boosts 0` Replaces SmartPistol by Phase Rewind and Pilot turret by HoloPilot Nova

### Speedgauge

Speedgauge settings adds a meter that fills when you go at a certain speed and empties when you don't go fast enough

- `kill_slow_players 0` Boolean. Kills pilots when their meter is empty. Overrides `damage_slow_players 0`
- `damage_slow_players 0` Boolean. Sets Pilot health to 1/10 when their meter is empty.
- `speedgauge_multiplier 1.0` Float. Set to 0.5 to half the size of the speedgauge. set to 2 to double it. Does not impacts visuals.
- `accepted_speed 260` Float. Determines the minimum accepted speed. 260 is pilot running speed.

- `bar_speedgauge_counter 0` Boolean. Gauge is shown by a bar on the bottom of the screen
- `text_speedgauge_counter 0` Boolean. Gauge is shown by a text on the bottom of the screen
- `burnmeter_speedgauge_counter 0` Boolean. Gauge replaces burnmeter. set pilot boost meter multiplier to 0 to make it work.
