# RETRO//POCKET

**A DIY handheld gaming console built around Pokémon.**

RETRO//POCKET is a personal hardware project. I'm building a portable gaming device using an ESP32-WROOM-32, with the main goal of making something I can actually use to play Pokémon and interact with a Pokédex.

I'm starting with the hardware and getting each part working before moving on to the bigger features. No point building the entire interface if the display or controls aren't reliable yet.

## What I want to build

The main focus is Pokémon.

- **Pokémon games:** Work towards running compatible classic Pokémon games through an emulator.
- **Pokédex:** An offline Pokédex with Pokémon information, entries and sprites.
- **Game library:** Load supported game ROMs from a microSD card.
- **Custom interface:** A simple retro-style menu for launching games and accessing the Pokédex.
- **Physical controls:** Dedicated buttons for movement, selection and gameplay.
- **Audio:** Speaker output for game sounds and feedback.

## Hardware

### Currently working / available

- ESP32-WROOM-32
- 1.8-inch ST7735 TFT display
- Six tactile push buttons
- Passive piezo buzzer

### Planned upgrades

- Larger 2.4-inch TFT display (ILI9341, 320 × 240)
- microSD card reader and 32GB microSD card
- Audio amplifier and speaker
- Rechargeable battery and charging circuit
- Custom PCB
- 3D-printed enclosure

## Software

- PlatformIO
- Arduino framework
- C++
- Adafruit GFX
- Adafruit ST7735 / ST7789 display libraries

## Current progress

The ESP32 is running, and I've successfully wired and tested the ST7735 display. I've also uploaded basic firmware and tested screen output, including colours and text.

I'm currently working on the hardware foundation and planning the transition to a larger display and SD card storage.

## Development roadmap

- [x] ESP32 setup and basic testing
- [x] ST7735 display initialization
- [x] Basic display firmware
- [ ] Larger display integration
- [ ] microSD card integration
- [ ] Button input system
- [ ] Offline Pokédex
- [ ] NES emulator development
- [ ] Pokémon game compatibility research and testing
- [ ] Audio integration
- [ ] Custom PCB
- [ ] Portable enclosure and final assembly

## Why I'm building this

I wanted to build my own handheld instead of simply buying one. I'm interested in understanding how the hardware and software fit together, from controlling a display to loading game data and eventually running an emulator.

It's still a work in progress, and I'll be documenting the development, mistakes and improvements as I go.

---

**RETRO//POCKET — Built from scratch, one component at a time.**
