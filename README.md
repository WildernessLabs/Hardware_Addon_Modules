# Hardware Addon Modules

These open source SMT addon modules provide discrete hardware functionality needed to support common design patterns when building IoT applications. We have created them to help shorten your time to market by providing composable, drop-in modules that allow you to quickly put together custom hardware for your solutions.

We use these modules in our own designs to reduce manufacturing complexity; by using composable modules, we don't need to integrate each design individual into larger designs, instead just using the SMT modules. For example, the Core-Compute dev kit is composed largely of these modules:

![Image of the Core-Compute developer board which includes a the USB-C, Dual-Ethernet, and SD-Card addon modules](/Docs/Core-Compute_Dev_Module.jpg)

## Modules

* **[USB-C, Power, Reset](/Docs/USB-C_Power_Boot_Reset/)** - USB-C connectivity for Core-Compute modules. Also includes Boot and Reset buttons, as well as up to `2A` of `3.3V` power, as well as a pass through `5V` USB power.
* **Solar Power/Battery Charging** - Accepts 6V solar panel power input, handles battery charging, and provides a continuous output voltage for operation.
* **Dual Ethernet** - Provides a dual-port switching ethernet interface for the Core-Compute module.
* **SD Card** - Micro SD-Card addon.
* **F7 Debug Headers** - Adds JTAG/SWO for the STM32F7 and ESP32 and UART debug output for the ESP32.

## Purchasing

These module will be available shortly in the Wilderness Labs store.
