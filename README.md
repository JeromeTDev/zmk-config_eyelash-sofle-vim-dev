# Eyelash Sofle Vim Dev Keymap

US-International ZMK keymap for the **Eyelash Sofle Split Keyboard**, optimized for **Vim users and developers**, with German character support via RA() combos.

---

## Features

- **Vim-friendly layout**  
  - Press `J + K` simultaneously to send `ESC` in Normal mode.
- **US-International base layout**  
  - Works on `English (US, intl., with dead keys)` in your OS.
- **German character support**  
  - `ä` → RA(Q)  
  - `ö` → RA(P)  
  - `ü` → RA(Y)  
  - `ß` → RA(S)
- **Coding/Developer optimizations**  
  - Layer 1: Navigation shortcuts (arrows, Home/End, PgUp/PgDn)  
  - Layer 2: Symbols and numpad for fast coding  
- **RGB control combos** (if your board supports it)

---

## Layers Overview

### Layer 0 – Base
Standard typing layer with US-Intl keys and RA() combos for German characters.

### Layer 1 – Navigation + Extras
Hold the left thumb key to access navigation: arrows, Home/End, PgUp/PgDn, and function keys.

### Layer 2 – Symbols & Numbers
Hold the right thumb key to access symbols, brackets, and numpad – optimized for coding.

---

## Combos

| Combo | Keys | Output |
|-------|------|--------|
| `JK`  | J + K | ESC (Vim Normal Mode) |
| `AE`  | Q + W | ä |
| `OE`  | P + O | ö |
| `UE`  | Y + U | ü |
| `SS`  | S + D | ß |

> You can modify combos in `behaviors.dtsi` / `keymap.dtsi` to fit your workflow.

---

## Installation

1. Fork or clone this repo.
2. Build your keymap using [ZMK build instructions](https://zmk.dev/docs/development/building).  
3. Flash the resulting firmware to your Eyelash Sofle keyboard.
4. Enjoy Vim-friendly coding with German support!

---

## For German Users / Deutsche Nutzer

This keymap supports German characters via RA() combos – perfect for **beginners switching from a US layout**.

---

## License

MIT License – feel free to fork and adapt for your own keymap.
![Sofle键位图](keymap-drawer/eyelash_sofle.svg)

