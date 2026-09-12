# Controls

Every binding the game ships with. The table below is generated from the game's own keymap,
so it says what the code says.

Full controller support. The pad has no digits, so **X** fires each equipped ability in
turn rather than pretending to be a number row. One press takes the next ready slot and
advances, and the bar marks which one is next. That is the *only* way a controller reaches
an ability, which is why it stayed when the keyboard's equivalent went.

There is no keyboard key for "next ability". `5`–`8` each fire a specific one, which says
more than a key that fires whichever happens to be ready.

## Flight and menus

| Does | Keyboard | Gamepad |
|---|---|---|
| Thrust / up | `W / Up` | `D-Pad Up` |
| Down | `S / Down` | `D-Pad Down` |
| Steer left | `A / Left` | `D-Pad Left` |
| Steer right | `D / Right` | `D-Pad Right` |
| Eject / confirm | `Enter / Space` | `A` |
| Back / menu | `Esc / Q` | — |
| Pause | `Esc` | `Start` |
| Confirm | `Y / Enter` | — |
| Fire next ready ability (pad only) | — | `X` |
| Fire power-up slot 1 (pad: X, in turn) | `5` | — |
| Fire power-up slot 2 (pad: X, in turn) | `6` | — |
| Fire power-up slot 3 (pad: X, in turn) | `7` | — |
| Fire power-up slot 4 (pad: X, in turn) | `8` | — |
| Open the E-SHOP (hats) | `E` | `X` |
| Cycle thruster style | `T` | `B` |
| Cycle vector font | `F` | — |
| Increase thrust power | `2` | `RB` |
| Decrease thrust power | `1` | — |
| Increase spin speed | `+` | — |
| Decrease spin speed | `-` | `LB` |
| Reset | `R` | — |

The spin-rate pair is bound to `Minus` and `Equal`. It reads as `+` everywhere you see it
in-game, because the vector font has no `=` glyph and the renderer silently draws nothing
for a character it cannot find — a hint saying `=` would render as a hole.

Since the throttle keys stop where your engine does, how far `1`/`2` will wind depends on
what you have bought from the E-SHOP. Turn that off under SETTINGS → GAMEPLAY TUNING →
THROTTLE CEILING if you preferred it unbounded.

## Keys that are not in that table

These are handled directly rather than as bindable actions, so they are keyboard-only.

| Does | Key |
|---|---|
| Open the command line | `Ctrl+C` |
| Zen mode — take the instruments off | `Z` |
| Layout inspector (a development overlay) | `L` |

## The command line

`Ctrl+C` opens it from anywhere except a text field, and the game freezes behind it. Bug
reports and ideas are filed from here: type `REPORT` and it asks you for the rest. `HELP`
lists what else it does. `:Q` or `EXIT` closes it. `Esc` is just a key in there.

A phone has no `Ctrl`. Open the same command line from **SETTINGS → INTERFACE → BUG OR
SUGGESTION**, which starts a report, or from **SETTINGS → ADVANCED SETTINGS → COMMAND LINE**.
It brings its own on-screen keyboard.

## Where the settings are

**SETTINGS** from the main menu or the pause screen. Its KNOBS AND LEVERS box holds five
pages: GAMEPLAY TUNING, DIFFICULTY AND ASSISTS, NARRATION AND VOICE, INTERFACE, and ADVANCED
SETTINGS.

Most gameplay levers are **locked** on those pages until you find THE CONTROL ROOM, which
is a place in the game rather than a menu. Two kinds of setting are never locked:
accessibility ones, and anything that ships switched **on** — a feature you did not choose
should not need a side quest to switch off.
