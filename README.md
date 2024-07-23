# DIY-Oscilloscope

## Особенности
* Плата - ESP-WROOM-32
* Версия TFT_eSPI - 2.50.0
* Версия версия менеджера плат ESP32 - 1.0.6 https://github.com/espressif/arduino-esp32/releases/download/1.0.5-rc6/package_esp32_dev_index.json
* Дисплей - ILI9341

Подключения:
* TFT_BL   22, он же LED
* TFT_MISO 19
* TFT_MOSI 23
* TFT_SCLK 18
* TFT_CS   15  // Chip select control pin
* TFT_DC    2  // Data Command control pin
* TFT_RST  -1  // На платке значится как EN
* VCC //TFT подключил к 5В VCC на плате

Тач:
* XPT2046_IRQ 27
* XPT2046_MOSI 32
* XPT2046_MISO 26
* XPT2046_CLK 25
* XPT2046_CS 33

Оба переключателя установил в положение 2 и проверил на звуковом генераторе с телефона - вроде работает.
<br>

