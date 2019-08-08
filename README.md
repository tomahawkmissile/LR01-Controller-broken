# LR01-Controller-broken
LR01 Broken supervisor controller layout. For display only.

**This does not work. I have abandoned this design for a new one which I will upload when I finish it.**

Features:
  - Quad core ARM Cortex-A53 TI AM6548 CPU + 2x R5F cores + real-time control units
  - 4GB DDR4-3200 ECC memory
  - 16GB eMMC flash + SDMMC
  - I2C,SPI,CAN,UART
  - 12V@10A supply MAX
  - 3 gigabit ethernet RJ45 connectors
  - 14 layer PCB

Why is this abandoned?
- I stumbled upon the fact that the DDR4 chips (all of them) had to be flipped for best operation so that the data lines could be closest to the SoC.
- I needed to critically fix PCI-e. (As you can probably tell)
- Too many layers, (cost driver)
- Not compact enough.
- Bad component/connector placement.

...
