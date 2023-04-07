# Legonzaur.ElitistRestrictions

Mod for Titanfall2's Northstar

No campers, no strafing. Ape go fast.

## convars

### Speedgauge

Speedgauge settings adds a meter that fills when you go at a certain speed and empties when you don't go fast enough

- `kill_slow_players 0` Boolean. Kills pilots when their meter is empty. Overrides `damage_slow_players 0`
- `damage_slow_players 0` Boolean. Sets Pilot health to 1/10 when their meter is empty.
- `accepted_speed 260` Float. Determines the minimum accepted speed. 260 is pilot running speed.

- `bar_speedgauge_counter 0` Boolean. Gauge is shown by a bar on the bottom of the screen
- `text_speedgauge_counter 0` Boolean. Gauge is shown by a text on the bottom of the screen
- `burnmeter_speedgauge_counter 0` Boolean. Gauge replaces burnmeter. **Disables Titans and Boosts**
