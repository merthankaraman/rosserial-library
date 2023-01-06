# rosserial-library

## Note
This is a part of [rosserial](https://github.com/ros-drivers/rosserial) repository to communicate with ROS system through a USART for STM32 embedded system.

And fork of [yoneken's rosserial](https://github.com/yoneken/rosserial_stm32) repository.

# Before use
To use library you must change your code format to C++. Setup DMA settings of UART you choose to use.
On DMA Settings:
* Add TX and RX request
* Choose circular mode for RX.
* Leave TX mode as Normal.
On NVIC Settings:
* Enable global interrupt.


## Optional
You can set GPIO's of UART to pull-up mode to get stable data.
