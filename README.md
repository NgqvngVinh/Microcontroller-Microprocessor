<h1 align="center">Microprocessors & Microcontrollers — HK241</h1>

<p align="center">
  <i>HCMUT · Semester 241 (3rd year) · STM32F1 family with STM32CubeIDE + Proteus simulation</i>
</p>

This is an **index repository** for the course *Microprocessors & Microcontrollers* at Ho Chi Minh City University of Technology (HCMUT). Each lab and the final project lives in its own dedicated GitHub repository — clone whichever one you need.

## Labs & Final project

| # | Topic | Repository | Local folder |
|---|---|---|---|
| Lab 1 | GPIO, LED blink, 7-segment display (STM32F100C6Tx) | [STM32_LAB_1](https://github.com/NgqvngVinh/STM32_LAB_1) | [`lab1/`](lab1/) |
| Lab 2 | Hardware & software timer, 7-segment clock | [STM32_LAB_2](https://github.com/NgqvngVinh/STM32_LAB_2) | [`lab2/`](lab2/) |
| Lab 3 | Traffic light FSM with debounced buttons (F103C6) | [STM32_LAB_3](https://github.com/NgqvngVinh/STM32_LAB_3) | [`lab3/`](lab3/) |
| Lab 4 | RTOS-style scheduler on STM32 | [STM32_LAB_4](https://github.com/NgqvngVinh/STM32_LAB_4) | [`lab4/`](lab4/) |
| Lab 5 | UART communication protocol with timeout & retransmit | [Microcontroller-Microprocessor_Lab5](https://github.com/NgqvngVinh/Microcontroller-Microprocessor_Lab5) | [`lab5/`](lab5/) |
| Assignment | Final project: traffic-light system on STM32F103RB with LCD16x2 | [TrafficLight_LCD_STM32rb](https://github.com/NgqvngVinh/TrafficLight_LCD_STM32rb) | [`btl/`](btl/) |

Each sub-folder is its own independent git repository. See the README inside each folder for full hardware, build, and run instructions.

## Common toolchain

| Item | Version / spec |
|---|---|
| MCU (labs 1-2) | STM32F100C6Tx (Cortex-M3, 24 MHz) |
| MCU (lab 3, 5, BTL) | STM32F103C6 / STM32F103RB (Cortex-M3) |
| IDE | STM32CubeIDE 1.13+ (bundled `arm-none-eabi-gcc`) |
| HAL | STM32Cube F1 |
| Simulator | Proteus 8 Professional |
| Tested OS | Windows 10 / 11 |

## Cloning everything

To check out all six repositories side-by-side under this folder layout:

```bash
git clone https://github.com/NgqvngVinh/STM32_LAB_1.git lab1
git clone https://github.com/NgqvngVinh/STM32_LAB_2.git lab2
git clone https://github.com/NgqvngVinh/STM32_LAB_3.git lab3
git clone https://github.com/NgqvngVinh/STM32_LAB_4.git lab4
git clone https://github.com/NgqvngVinh/Microcontroller-Microprocessor_Lab5.git lab5
git clone https://github.com/NgqvngVinh/TrafficLight_LCD_STM32rb.git btl
```

## License

Each child repository carries its own license file. By default, coursework here is released under the MIT License unless stated otherwise inside a given lab.
