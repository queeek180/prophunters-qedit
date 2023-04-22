# Prop Hunters - qEdit

This is a fork of [Prop Hunters - Huskle's Edition](https://github.com/zikaeroh/husklesph) which is a fork of [MechanicalMind's Prop Hunters](https://github.com/MechanicalMind/prophunters),
intended to fix a few bugs, add a few features and tweak things to my liking.

A full changelog can be found in [CHANGELOG.md](CHANGELOG.md).

## Improvements

For the full list, take a look at the [changelog](CHANGELOG.md), but here is a non-exhaustive list:

-   On death, taunts no longer persist into spectator mode.
-   The taunt menu remembers your mouse position when reopened.
-   Auto taunts are natively supported! - But disabled by default!
-   The `ph_endround` command forces a round to end on a tie.
-   Taunts can be restricted to a specific player model. See the taunt docs for more info.
-   Large props can properly re-disguise.
-   Spawn points are generated automatically from existing spawn points, leading to much greater success in spawning players when the map doesn't provide enough.
- Prop's now tpose by default! - Can by toggled with ph_props_tpose
- Prop's start in thirdperson! - can be toggled with ph_props_thirdperson
- Pre-round, post-round and round timers can all be adjusted with console commands!

## Development

Simply edit the lua files with your preferred text editor!


### Code style - Note, I will not be strictly following this but will keep it in mind. They are good guidelines

-   C-style operators (`not` -> `!`, `or` -> `||`, `and` -> `&&`).
-   Lua-style comments (`//` -> `--`), so GitHub's formatting doesn't implode.
-   Code must pass glualint.

## Contributors

-   MechanicalMind (original author)
-   Zikaeroh (huskle's edition)
-   foodflare (huskle's edition)
-   Yolopanther (huskle's edition)
-   queeek180
