# chip-8-emulator

[Following this article](https://tobiasvl.github.io/blog/write-a-chip-8-emulator/)

## Steps

- [✅] Setup Project
- [✅] Setup SDL
- [❌] Read Binary files
- [❌] Setup Memory
- [❌] Setup fonts
- [❌] Initilize a display
- [❌] Create the Stack
- [❌] Setup Timers
- [❌] Create the keypad
- [❌] Create the Fetch/Decode/Execute loop
- [❌] Set up instrictions

## Chip-8 Specs

Memory: Direct Access to 4Kb ram
Display: 64x32 px; Monochrome
One program counter
One 16-bit register called I that points to locations in memory
Stack for 16-bit addresses
8-bit delay timer, decremented at a rate of 60 Hz until 0
8-bit sound timer beeps when not 0
16 8-bit variable registers 0-F called V0 through VF
VF is a flag register
