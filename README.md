# Macropad

Hack Club's first wireless macropad with haptics powered by a Raspberry Pi Pico W!!
Consists of 11 Cherry MX Switches with per key RGB lighting, two EC-11 Rotary Encoders and an 0.91inch OLED Display.

<img width="919" height="679" alt="Screenshot 2026-06-30 at 12 10 52 AM" src="https://github.com/user-attachments/assets/6b23fc83-e0d1-4f8d-b58e-1fa6ee238ac2" />

I've made this as in my experience off the shelf macropads are way too expensive for the features they offer and are also very generic.
This is an alternative that is actually unique with multiple customizable switches, rotary encoders, a display, Wireless & Wired connectivity and insanely good haptics.

## Fully customizable ofc; But this is what I've planned to do:

- 9 * customizable witches for different functions.
- 2 * switches for switching between different modes/profiles of the macropad.
- 1 * rotary encoder to switch between different modes/profiles of the marcopad.
- 1 * rotary encoder for any customizable function.
- OLED Display will display the current mode, and is customizable.

# PCB
<img width="791" height="553" alt="Screenshot 2026-06-30 at 12 09 11 AM" src="https://github.com/user-attachments/assets/6e1fbc27-82d8-46d3-bdff-7aa02a43c275" />
<img width="757" height="541" alt="Screenshot 2026-06-30 at 12 09 26 AM" src="https://github.com/user-attachments/assets/11bd815a-d1b6-4a8d-be01-1d4ebd646d00" />

I am using JST connector footprints so that I can integrate the daughter modules to the main PCB seamlessly.

# Schematics
<img width="967" height="643" alt="Screenshot 2026-06-30 at 12 22 28 AM" src="https://github.com/user-attachments/assets/7fc7e8dc-42b9-428f-847a-203aa43e52eb" />

I am using the TP4056 module for charging the battery; MT3608 for boosting the single cell voltage; DRV2605l for accurately driving the haptics motors; Raspberry Pi Pico W for controlling everything, one more reason as to why I chose this MC is its amount of GPIO's and wireless connectivity.

