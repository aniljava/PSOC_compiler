Demo 2a - LCD and LED
---------------------
This demo flashes LED2 at 0.5Hz and turns on LED1 whilst SW2 is pressed (P6_1)

Key points:
  * Minimal system setup
  * No config.hex (ie no config data)
  * Busy wait to drive LED

Code Dependencies:
  * Essentially no Cypress code
  * No CMSIS

Hardware Setup:
  * Requires CYC8KIT-050

  * Set up the CYC8KIT-050 as folows
      - Two wires:
          P6_0 (connector P9) to LED1 (connecor P6)
          P6_6 (connector P9) to LED2 (connecor P6)
      - Connect 2 line LCD
