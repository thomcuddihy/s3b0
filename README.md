# S3B0

## Stars Wars Fantasy Flight dice roller bot for Discord

[Discord Bot entry.](https://top.gg/bot/506265070888681472)

## Usage

A Star Wars Fantasy Flight dice roller bot for Discord.

Created for a bunch of rebels to play Age of Resistance on Discord, but we might as well share it to the rest of the galaxy because those dice rolls are weird.

```text
/swoll [[number=1][die type]]...

Die Types:
    a: Ability
    p: Proficiency
    c: Challenge
    d: Difficulty
    b: Boost
    s: Setback
    f: Force (can't be chained)
    t: Ten (d10) (can't be chained)
    h: Hundred (d100) (can't be chained)

Example:
    /swoll 3a1p2c1b2s
    /swoll 3f
    /swoll h
```

## Notes

Needs environmental variable S3B0_TOKEN to be set if you want to run this yourself. See `set_env.sh.example` for a Linux/OSX method.

Using py-cord v2 library.

Please open an issue for any bugs or feature requests.
