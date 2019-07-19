# stm32f407-atk-explorer
RT-Thread RTOS 工程

功能：适配ESP8266

![screenShot.png](https://i.loli.net/2019/07/19/5d31b23ecdd9180342.png)

连接方式，直接与板子的ATK MODULE接口连接即可。另外要注意，需要用跳线帽短接P10的USART3_RX和GBC_TX以及USART3_TX和 GBC_RX  。

![screenShot.png](https://i.loli.net/2019/07/19/5d31b4e2eb18177850.png)

Hardware Drivers Config → Onboard Peripheral Drivers →选择[*] Enable COM3 (UART3)

![screenShot.png](https://i.loli.net/2019/07/19/5d31b3f7dd25519764.png)

RT-Thread online packages → IoT - internet of things→AT Device

![screenShot.png](https://i.loli.net/2019/07/19/5d31b43fdf6d272793.png)