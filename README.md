# Aventen-Formosa-Sync
Introduction to the Aventen Formosa Sync on Github
![Anew2_2K (2)](https://github.com/avencan/Aventen-Formosa-Sync/assets/140997610/1c519d4e-4e21-4dd1-9aa2-11c8559b3667)
# Features
The Aventen Formosa Sync is a high-performance development board equipped with a 600 MHz RT1060 MCU (overclockable to a GHz - at the right conditions) , built-in WiFi 5 capability + bluetooth with audio, USB OTG, and an array of advanced features like RGB LEDs, USB-C connectivity, and comprehensive battery management. Designed for versatile applications, from IoT makers looking for the best for all projects to industrial solutions and professionals, it offers a seamless blend of power and innovation in an compact, breadboardable formfactor.

| Name                       | MCU                  | PSRAM | FLASH | Built-in SD Card Slot | Built-in WiFi/Bluetooth | Onboard LED | Header Pins | USB Connector | Ethernet       | Debugging | Aux LDO 1A | Chip Antenna + IPX w RF Switch | Battery Support (JST) + USB LiPo Charge |
|----------------------------|----------------------|-------|-------|------------------|-------------------------|-------------|-------------|---------------|----------------|----------|------------|--------------------------------|----------------------------------------|
| Aventen Formosa Sync       | NXP MIMXRT106SDVL6B  | 8MB   | 16MB  | Y                | WiFi 5 - Murata 1ZM      | RGB + LED   | 35          | USB-C         | 10/100 LAN8720A | SWD/JTAG      | Y          | Y               | Y                                      |

# Status
We are in the prototype stage, and not alot of details have been posted online about this board. We have finished and confirmed our first prototype, and are now finishing bootloader and IDE software support, we are on track to finishing by the end of 2023.

- More details to come soon 

Crowdfunding on Crowdsupply: https://www.crowdsupply.com/aventen/aventen-formosa-sync

# Add on boards

- RJ45 LAN8720A Ethernet Board: https://github.com/avencan/Aventen-Formosa-Sync/tree/main/RJ45/RJ45%20Board
![RJ45 Board](https://github.com/avencan/Aventen-Formosa-Sync/assets/140997610/86d3339a-ee96-42e9-ad54-488362c2029c)

# Strategy 
Aventen Formosa Sync - Strategy for Makers and Professionals

The NXP RT1060 board stands poised to offer a transformative experience for both casual makers and professional developers. To ensure accessibility and flexibility, a dual-faceted approach for board initialization and use is proposed.

For the makers and hobbyists, the primary goal is to ensure an out-of-the-box experience akin to "plug-and-play". This can be achieved by pre-installing a robust bootloader tailored for standard platforms like Arduino and PlatformIO. This approach  reduces the learning curve and allows immediate access to a familiar development environment, thus making it an attractive proposition for a vast majority of hobbyists. In addition to compatibility with standard Arduino libraries, it's crucial that this bootloader can be updated or even restored by users to maintain the board's versatility.

On the other hand, professional developers often demand a deeper level of control over their hardware. This necessitates direct MCU access without any bootloader restrictions. To cater to this, the board can expose SWD (Serial Wire Debug) pins + JTAG, allowing for direct programming and advanced debugging. This ensures that the board remains compatible with professional toolchains and environments like MCUXpresso, giving seasoned developers the freedom to exploit the full potential of the MCU.

# Please submit an issue for suggestions thanks :)
