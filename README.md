# MidiMonitor

Minimal Android app that receives USB MIDI input from a class-compliant
keyboard, filters/modifies MIDI messages, and displays them on screen.

## Features
- USB MIDI input via Android MIDI API
- Hot-plug device detection
- MIDI filtering (e.g. remove aftertouch)
- MIDI modification (e.g. transpose notes)
- Simple on-screen monitor

## Requirements
- Android 5.0 (API 21) or newer
- USB MIDI class-compliant keyboard
- USB OTG adapter (powered hub recommended)

## Build & Run
1. Open project in Android Studio
2. Enable USB debugging on your phone
3. Connect phone via USB
4. Plug MIDI keyboard into phone
5. Click **Run**

## Notes
- No native code
- No permissions beyond USB host
- Designed to be a clean base for MIDI processing apps
