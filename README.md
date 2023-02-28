# Trion T20 Development Board

# ***WORK IN PROGRESS***

Development board for Efinix Trion T20 FPGA.

- SPI and JTAG configuration from FT4232 IC.

- USB OTG.

- 100 Mbit/s ethernet.

- Wi-fi/Bluetooth connectivity.

- SD Card.

- Various buttons and leds.

- Rasberry Pi header for I/O connectivity.

- Standard SYZYGY port for LVDS I/O with configurable voltage levels. (Or 2 PMODS or Rasberry Pi MIPI connector NOT DECIDED YET)

- PCB is designed to be manufactored by JLCPCB using the 6 layer impedence controlled JLC3313 stack up. All of the impedence controlled track widths calculated acording to the JLC3313 stack up. Stack up is as follows;

---Signal

---Ground

---Signal

---Power

---Ground

---Signal

All of the high speed impedence controlled tracks are routed on top and bottom layers.

![t20 top](https://user-images.githubusercontent.com/79105578/221904231-6ed081d1-3776-47bf-bb15-15c087bf4cc6.PNG)

![t20 bottom](https://user-images.githubusercontent.com/79105578/221904371-238db9cc-388a-4ff9-8e5b-73a5268bd3ac.PNG)

![t20_1](https://user-images.githubusercontent.com/79105578/221904096-0a1442be-b596-4255-af8d-73d2c7108498.PNG)

![t20_2](https://user-images.githubusercontent.com/79105578/221904178-fa9e536f-52f1-4a69-9ac7-aa6426c6bf64.PNG)
