#Discovery L053C8

Below are the pins usable for the peripherals. Pins in **bold** are the default.

## SPI

Instance |MOSI|MISO|SCK|
-|-|-|-|
SPI1|PA7, PA12, **PB5**|PA6, PA11, **PB4**|PA5, **PB3**|
SPI2|**PB15**|**PB14**|**PB10**, PB13|

## I2C

Instance |SDA|SCL|
-|-|-|
I2C1|PB7, **PB9**|PB6, **PB8**|
I2C2|**PB11**, PB14|**PB10**, PB13|

## USART

Instance |RX|TX|
-|-|-|
USART1|**PA10**, PB7|**PA9**, PB6|
USART2|**PA3**, PA15|**PA2**, PA14|

## I2S

Instance |CK|SD|WS|MCK|
-|-|-|-|-|
I2S2|**PB13**|**PB15**|**PB9**, PB12|**PB14**|

## TIM

Instance |CH1|CH2|CH3|CH4|
-|-|-|-|-|
TIM2|**PA0**, PA5, PA15|**PA1**, PB3|**PA2**, PB10|**PA3**, PB11|
TIM21|**PA2**, PB13|**PA3**, PB14|||
TIM22|**PA6**, PB4|**PA7**, PB5|||

## ADC 

Instance | Channel | Pin
-|-|-
ADC|IN0|PA0|
ADC|IN1|PA1|
ADC|IN2|PA2|
ADC|IN3|PA3|
ADC|IN4|PA4|
ADC|IN5|PA5|
ADC|IN6|PA6|
ADC|IN7|PA7|
ADC|IN8|PB0|
ADC|IN9|PB1|

## GPIO 

Pin | Peripheral signal available on the pin | Board macro
-|-|-
PA0 |ADC_IN0, COMP1_INM, COMP1_OUT, RTC_TAMP2, SYS_WKUP1, TIM2_CH1, TIM2_ETR, TSC_G1_IO1, USART2_CTS||
PA1 |ADC_IN1, COMP1_INP, LCD_SEG0, TIM2_CH2, TIM21_ETR, TSC_G1_IO2, USART2_DE, USART2_RTS||
PA2 |ADC_IN2, COMP2_INM, COMP2_OUT, LCD_SEG1, TIM2_CH3, TIM21_CH1, TSC_G1_IO3, USART2_TX||
PA3 |ADC_IN3, COMP2_INP, LCD_SEG2, TIM2_CH4, TIM21_CH2, TSC_G1_IO4, USART2_RX||
PA4 |ADC_IN4, DAC_OUT1, SPI1_NSS, TIM22_ETR, TSC_G2_IO1, USART2_CK|**SS**|
PA5 |ADC_IN5, SPI1_SCK, TIM2_CH1, TIM2_ETR, TSC_G2_IO2|**LED_BUILTIN**|
PA6 |ADC_IN6, COMP1_OUT, LCD_SEG3, LPUART1_CTS, SPI1_MISO, TIM22_CH1, TSC_G2_IO3||
PA7 |ADC_IN7, COMP2_OUT, LCD_SEG4, SPI1_MOSI, TIM22_CH2, TSC_G2_IO4||
PA8 |CRS_SYNC, LCD_COM0, RCC_MCO, USART1_CK||
PA9 |DAC_EXTI9, LCD_COM1, RCC_MCO, TSC_G4_IO1, USART1_TX||
PA10 |LCD_COM2, TSC_G4_IO2, USART1_RX||
PA11 |COMP1_OUT, SPI1_MISO, TSC_G4_IO3, USART1_CTS, USB_DM||
PA12 |COMP2_OUT, SPI1_MOSI, TSC_G4_IO4, USART1_DE, USART1_RTS, USB_DP||
PA13 |SYS_SWDIO, USB_NOE||
PA14 |SYS_SWCLK, USART2_TX||
PA15 |LCD_SEG17, SPI1_NSS, TIM2_CH1, TIM2_ETR, USART2_RX||
PB0 |ADC_IN8, LCD_SEG5, LCD_VLCD3, SYS_VREF_OUT_PB0, TSC_G3_IO2||
PB1 |ADC_IN9, LCD_SEG6, LPUART1_DE, LPUART1_RTS, SYS_VREF_OUT_PB1, TSC_G3_IO3||
PB2 |LCD_VLCD1, LPTIM1_OUT, TSC_G3_IO4||
PB3 |LCD_SEG7, SPI1_SCK, TIM2_CH2, TSC_G5_IO1|**SCK**|
PB4 |LCD_SEG8, SPI1_MISO, TIM22_CH1, TSC_G5_IO2|**MISO**|
PB5 |I2C1_SMBA, LCD_SEG9, LPTIM1_IN1, SPI1_MOSI, TIM22_CH2|**MOSI**|
PB6 |I2C1_SCL, LPTIM1_ETR, TSC_G5_IO3, USART1_TX||
PB7 |I2C1_SDA, LPTIM1_IN2, SYS_PVD_IN, TSC_G5_IO4, USART1_RX||
PB8 |I2C1_SCL, LCD_SEG16, TSC_SYNC|**SCL**|
PB9 |I2C1_SDA, I2S2_WS, LCD_COM3, SPI2_NSS|**SDA**|
PB10 |I2C2_SCL, LCD_SEG10, LPUART1_TX, SPI2_SCK, TIM2_CH3, TSC_SYNC||
PB11 |ADC_EXTI11, I2C2_SDA, LCD_SEG11, LPUART1_RX, TIM2_CH4, TSC_G6_IO1||
PB12 |I2S2_WS, LCD_SEG12, LCD_VLCD2, LPUART1_DE, LPUART1_RTS, SPI2_NSS, TSC_G6_IO2||
PB13 |I2C2_SCL, I2S2_CK, LCD_SEG13, LPUART1_CTS, SPI2_SCK, TIM21_CH1, TSC_G6_IO3||
PB14 |I2C2_SDA, I2S2_MCK, LCD_SEG14, LPUART1_DE, LPUART1_RTS, RTC_OUT_ALARM, RTC_OUT_CALIB, SPI2_MISO, TIM21_CH2, TSC_G6_IO4||
PB15 |I2S2_SD, LCD_SEG15, RTC_REFIN, SPI2_MOSI||
PC13 |RTC_TAMP1, RTC_TS, SYS_WKUP2||
PC14 |RCC_OSC32_IN||
PC15 |RCC_OSC32_OUT||
PH0 |RCC_OSC_IN||
PH1 |RCC_OSC_OUT||