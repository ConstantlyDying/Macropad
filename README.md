## NOTE:
Will make the CAD and Firmware soon:)


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

# Bill Of Materials:

| SR. No: | Name:                     | Quantity: | Unit Price: (INR) | Total Price:(INR) | Unit Price: (USD) (Approx) | Total Price:(USD)(Approx) | Link:                                                                                                            |
|---------|---------------------------|-----------|-------------------|-------------------|----------------------------|---------------------------|------------------------------------------------------------------------------------------------------------------|
| 1       | Raspberry Pi Pico W       | 1         | ₹631.00           | ₹631.00           | $7.00                      | $7.00                     | https://robu.in/product/raspberry-pi-pico-w/                                                                     |
| 2       | EC11 Rotary Encoder       | 2         | ₹55.00            | ₹110.00           | $1.00                      | $2.00                     | https://robu.in/product/hongyan-ec11h-7ce20p1zy20-rotary-encoder-with-push-button-switch-vertical-plug-in-5-pin/ |
| 3       | Cherry MX Switch*35 pack  | 1         | ₹1,880.00         | ₹1,880.00         | $20.00                     | $20.00                    | https://keychron.in/product/cherry-mx-switch-set/                                                                |
| 4       | TP4056 Module             | 1         | ₹15.00            | ₹15.00            | $1.00                      | $1.00                     | https://robu.in/product/tp4056-1a-li-ion-lithium-battery-charging-module-mini-usb/                               |
| 5       | MT3608 Module             | 1         | ₹35.00            | ₹35.00            | $1.00                      | $1.00                     | https://robu.in/product/mt3608-2a-max-dc-dc-step-up-power-module-booster-power-module/                           |
| 6       | DRV2605L Module           | 1         | ₹1,200.00         | ₹1,200.00         | $13.00                     | $13.00                    | https://robu.in/product/adafruit-drv2605l-haptic-motor-controller-stemma-qt-qwiic/                               |
| 7       | OLED Display              | 1         | ₹600.00           | ₹600.00           | $7.00                      | $7.00                     | https://robu.in/product/waveshare-128x32-general-0-91inch-oled-display-module/                                   |
| 8       | SK6812 mini - e LEDS      |           | --                | --                | --                         | --                        | Sourced Locally                                                                                                  |
| 9       | Battery (3.7v)            | 1         | ₹500.00           | ₹500.00           | $6.00                      | $6.00                     | Sourced Locally                                                                                                  |
| 10      | SPDT Switch               | 1         | ₹600.00           | ₹600.00           | $7.00                      | $7.00                     | https://robu.in/product/1-month-warranty-261/                                                                    |
| 11      | JST Connectors (Assorted) | --        |                   |                   |                            |                           | Sourced Locally                                                                                                  |
| 12      | PCB Fabrication           | 1         | ₹1,700.00         | ₹1,700.00         | $17.00                     | $17.00                    | JLC PCB                                                                                                          |
|         |                           | TOTAL:    | ₹7,216.00         | ₹7,271.00         | $80.00                     | $81.00                    |                                                                                                                  |


