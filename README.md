# ColStag

Keyboard project around staggered columns, over a laptop.

## Why ?

Keyboard traditionnal layouts suck. Nothing new here, QWERTY is a remnant from a pre-ergonomy history.

Dvorak-based layouts improve it by reducing how much fingers move, yet key rows are still staggered in contradiction with natural finger orientation.

Luckily, custom desktop keyboards come to the rescue, but as much as I love my ergodox plank:

- forefinger is still more stretched than all other fingers
- columns are still not aligned with fingers
- BÉPO layout has this "W" key beyond the 12th plank column, leading to some remapping cumbersome to get around when using the laptop's keyboard
- the plank does not fit over a laptop keyboard

Whenever one switches from its beloved custom-mapped ortholinear keyboard, to a supremely classic keyboard (laptop or not), one is not happy.

## How ?

1. tilt left and right halfves of the keyboard to align with finger's natural axis (around ±15-20°)
2. shift columns to fit each finger's length
3. add missings keys when compared to QWERTY: "B" and up to "\]"
4. keep a single board to use over a laptop keyboard and still allow use of touchpad

## Inspiration

- [Atreus](https://awesomeopensource.com/project/technomancy/atreus) for tilted halves in one plate (common among others)
- [Catboard](http://catboard.klava.org/) for the extra columns and nice attention to the thinkpad red thing in the middle to avoid touching
- [Kyria](https://splitkb.com/products/kyria-pcb-kit) for thumb key layout and low-profile switch & caps example
- [Keyboardio Model 100](https://shop.keyboard.io/) for the integrated wrist rests

## Features

### Kept

- All letters on the 3 central rows of a classic keyboard: most used on regular keyboard layouts should not be moved nor re-mapped for maximum compatibility.
- Arrow keys as for a 60%/laptop: usage already in muscle memory and no move layout under JKLM nor SDEF on laptops.
- Integrated wrist rests to compensate for keycaps height, hollow on center to free touchpad. Might allow for regular keys instead of locking on low-profiles.
- SPACE as 2 keys: allows re-mapping other useful like BACKSPACE or RETURN.
- Lower and Raise modifier: soooo useful on Plank

### Unsure

Low-profile or not?

Flat keyboard is very desirable, unobtrusive and doesn't hamper typing with keyboard over the laptop. Regular switches and keycaps would raise this and require wrist rests to compensate.

- Kailh choc height: 11mm + 3mm key = 14mm
- Regular Cherry MX: 18.5mm + 6.5mm key = 25mm (+11mm)

Conclusion, need to do some cardboard prototype to find out:

- test with plank on laptop, already as flat as regular can get.
- test with a mockup
- test with some tilting and wrist rests.

### Discarded

- No F[1-12] keys: use is too sparse to justify board area, and layouts not standardized anyway
- No number row: although could help to transition, it takes too much effort for little gain.
- No numpad.
- No centered keys as on Typematrix: index finger already has 2 columns to cover, doing with a third makes the whole hand move...

### Needed

- number row: skipped, modified chars re-mapped on close positions
- numpad: on a layer, centered around K key (so left hand free for modifiers)
- F[1-12]: on a layer in 3 x 4 block around home row on right side (so left hand free for modifiers)
- arrows: dedicated keys (optionnaly also under JKLM on a layer)
