# Distorted Comms
A simple-to-use mod for Among Us that makes Comms Sabotage more powerful!

![Demo](https://github.com/ahmed-dardery/distorted-comms/raw/main/demo/main.gif)

## How it works
In game, when an impostor calls the Comms Sabotage, all players's unique distinctive features are removed and instead they all become similar to each other! This makes this (usually useless) sabotage much more powerful!


## Configuration
After running the game with mod installed at least once, a configuration file should be present at `\BepInEx\config\mod.dardy.distortedcomms.cfg`. This allows changing the following settings under header `[Distortion]`:

| Option | Description | Default |
| :-----: | :---------: | :-----------: |
| Duration | The duration (in seconds) in which the fading out / fading in occurs. | 3 |
| Back | The back color (RGBA in hex) of the distorted player when comms are active | 7F7F7FFF |
| Body | The body color (RGBA in hex) of the distorted player when comms are active | 7F7F7FFF |

Of course, you can leave them as-is.

**NOTE: the config parser doesn't implement any error detection, so be careful**

## Bug Reports
Due to circumstances, I haven't had the chance to thoroughly test this mod. If you encounter any issues you are more than welcome to post it in the Issues section!

## Special Thanks

- **Reactor**: Modding API that makes modding so much easier.
- **BepInEx**: The game patcher used to enable modding for the game.
- **Woodi-dev**, **NotHunter101**: inspiration to start modding Among Us, code-snippets to help understand the ins and outs.
- **Brybry16**: install instructions lifted directly from his mod.
