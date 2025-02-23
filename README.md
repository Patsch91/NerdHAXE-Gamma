<img src="https://github.com/Patsch91/NerdHEX-Gamma/blob/main/Images/NHG-Logo dark.png" width="250px">

**The NerdHaxe-Gamma is a 6-Asic-Miner based on the [NerdQAxe+(+)](https://github.com/shufps/qaxe) / [Nerdaxe](https://github.com/BitMaker-hub/NerdAxeUltra) and inspired by [OSMU](https://osmu.wiki/) and the [Bitaxe](https://github.com/bitaxeorg)**

<img src="https://github.com/Patsch91/NerdHEX-Gamma/blob/main/Images/Front PCB.png" width="250px"> <img src="https://github.com/Patsch91/NerdHEX-Gamma/blob/main/Images/Backside PCB.png" width="250px">

# Specifications
- **Open Source:** All design files are provided, and suggestions/improvements are always welcome.
- **Standalone:** Using the T-Display S3 with WiFi and works without an external controller.
- **Performance:** ~7.35 TH/s average at around 120 watts (measured at the wall, including a MW UHP-200-12).
- **Case:** DIY Idea for a 3D-printed case with an integrated PSU.

# Software / Firmware
The NerdHaxe-Gamma uses the [ESP-Miner](https://github.com/shufps/ESP-Miner-NerdQAxePlus) by shufps and the [Webflasher](https://shufps.github.io/nerdqaxe-web-flasher/) is recommended as the easiest way to flash the NerdHaxe-Gamma (or any other Nerd*axe variant). It uses the official releases and is always up to date.
<br> The screen displays key values and parameters, such as the current hashrate, session runtime, fan speed, and more.
<br><br> <img src="https://github.com/Patsch91/NerdHEX-Gamma/blob/main/Images/Display Haxe.png" width="350px">
<br> Via your browser, you can monitor all important aspects, such as the hashrate graph, adjust settings like core voltage and fan speed, define a fallback stratum pool, or simply check the logs.
<br><br> <img src="https://github.com/Patsch91/NerdHEX-Gamma/blob/main/Images/OS Screen dark.png" width="900px">

# Components
- **Asics:** 6 x BM1370
- **T-Display S3:** ESP32S3 microcontroller with WiFi and integrated display
- **PCB:** I ordered the prototype PCB as specified in the KiCad files above, with a copper thickness of 1/1 oz, and it has been running well so far.
- **BOM:** The board components needed for the build can be found in the BOM.
- **Heatsink:** The PCB has slotted holes that accommodate mounting patterns from 75x75mm to 80x80mm. The mounting patterns fit some LGA15xx or 2011 coolers, but be mindful of the thermal contact area of the coolers you want to use. Most standard coolers have a contact area of around 40x40mm, which is not sufficient. Therefore, I used server heatsinks such as the Supermicro SNK-P0048P(W) with a completely flat contact surface.
- **Fans:** Currently, I am using 2x Noctua A9x25 PWM chromax fans in a push-pull configuration, and at 75-85% PWM, the sound level is quite ok. I will soon test the Arctic P9 Max model, which is more powerful than the Noctuas, but of course, at a higher noise level.
- **PSU:** The NerdHaxe-Gamma operates at around 12V and 10A with default settings. Therefore, I recommend using a PSU that provides 12V and at least 15A. I used the Meanwell UHP-200-12. <br>


# Misc 
**DISCLAIMER:** This device is an *advanced* build and partly WIP. To get 6 Asics soldered properly *can* be very hard and frustrating if you are not used to soldering Asics or soldering in general. Using that amount of power, this device is not a toy, and you should know what you are doing. Follow the regulations and precautions – **stay safe!** <br>

If you like this project and want to support future work, feel free to donate to: **`bc1q0ctaxeha3lpsaaz7kpjulflw2d9p66fhkp48dk`**

or related projects without which this project would not have been possible for me:

[NerdQAxe+](https://github.com/shufps/qaxe)

[OSMU](https://osmu.wiki/)

