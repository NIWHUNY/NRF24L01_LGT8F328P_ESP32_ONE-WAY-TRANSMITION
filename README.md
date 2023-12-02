# NRF24L01_LGT8F328P_ESP32_ONE-WAY-TRANSMITION
This code is my end semester code, it transmit data from lgt8f328p(arduino nano like board) to a ESP32 and sends it to either blynk or thingsboard or both at the same time  

TELEMETRI TS is a transmittion code for lgt8f328p (make sure SPI interface is correct)

TELEMETRI RV is a receiver code for esp32 with oled display, you may want to check I2C address

TELEMETRIWITHBLYNK is a further development of telemetri RV and send the data to blynk

telemetriwiththingsboard is also further development of telemetrirv and send data to thingsboard

telemetriblynkthingsboard is a combination of both blynk and thingsboard to run simultaniously (warning maybe a bit buggy)
