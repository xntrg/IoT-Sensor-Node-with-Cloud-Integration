# IoT-Sensor-Node-with-Cloud-Integration

**Author:** Xuan Truong Nguyen

This is my first personal project, in terms of getting ideas and implementing. The project goal is to gather environmental data such as temperature, air pressure, ... and send those later onto a cloud platform.

## Objective

The reason why i chose to implement this project is mainly to learn the STM32F4 Nucleo board and also learn how to create an IoT system. Since its purpose is to learn mainly, there would be a few components or features, which do not necessarily have to be used or implemented, for example, I use the NodeMCU Lolin V3 as a "Wi-Fi Bridge" only; if it's not about learning the STM32F4 then it would make more sense to use the NodeMCU as the main MCU.

## Materials 

| Component    |   Description     |
|--------------|-------------------|
|[STM32 NUCLEO F446-RE](https://www.conrad.de/de/p/stmicroelectronics-nucleo-f446re-entwicklungsboard-nucleo-f446re-stm32-f4-series-1416934.html)| Main MCU for this project|
|[NodeMCU Lolin V3](https://www.amazon.de/dp/B0DHY2KGBK?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)| Would be used as a "Wi-Fi Bridge" to send data onto a cloud platform|
|[GY-BMP280](https://www.amazon.de/dp/B07D8TPVVY?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)| Air Pressure Sensor|
|[DHT22 AM2302](https://www.amazon.de/dp/B078SVZB1X?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)| Temperature and Humidity Sensor|
|[BH1750FVI GY-302](https://www.amazon.de/dp/B07WJSB5BB?ref=ppx_yo2ov_dt_b_fed_asin_title)| Brightness Metering Sensor|
|[Cables, Breadboard, LEDs, ...](https://www.amazon.de/Elegoo-%C3%9CBERARBEITETES-Stromversorgungsmodul-Jumperkabel-Potentiometer/dp/B01M7N4WB6/ref=sr_1_8_sspa?crid=33X5UHOXJYHC0&dib=eyJ2IjoiMSJ9.YwDncf2c4nFOWnJGMPA-_pLOjsL95B-SQHuNcIhcOJfttQFAgGsgL5u8t5OtURHzCtG0uCeSJ6W9izB3o6YjMi-XJNT8nMYV5f6hQH5-XvJ7JcyfXrG3SlyBIC_dO_xZ140GCjahZwFR6wZ7PvovVrP8KoXII-b4p1ukGa84SAiy8QSBPm3Eo7-FhbPNRT2yiuYnDMi9BLIepeUw-ALv5h7_vlbjTofyXGAObYOPVfA.xJrc7ISkzvCtusZUl1zO3ficjaMePAWJVNBWvUNwXc0&dib_tag=se&keywords=iot+starter+kit&qid=1752164868&sprefix=iot+sta%2Caps%2C111&sr=8-8-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1)| Other small components| 
