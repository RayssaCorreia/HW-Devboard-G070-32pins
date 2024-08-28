# Devboard-G070-32pins
Jornada de desenvolvimento 

### Comparação entre os pinos do Arduino Uno e o micro stm32g070

- **[Arduino](https://docs.arduino.cc/hardware/uno-rev3/)**
  | **Pin Number** | **Pin Name**   | **Specification**                            |
  |----------------|----------------|---------------------------------------------|
  | 1              | Reset          | Resets the Arduino board                    |
  | 2              | Digital I/O 0  | Digital input/output, RX (Receive)          |
  | 3              | Digital I/O 1  | Digital input/output, TX (Transmit)         |
  | 4              | Digital I/O 2  | Digital input/output                        |
  | 5              | Digital I/O 3  | Digital input/output, PWM output            |
  | 6              | Digital I/O 4  | Digital input/output                        |
  | 7              | Digital I/O 5  | Digital input/output, PWM output            |
  | 8              | Digital I/O 6  | Digital input/output, PWM output            |
  | 9              | Digital I/O 7  | Digital input/output                        |
  | 10             | Digital I/O 8  | Digital input/output, PWM output            |
  | 11             | Digital I/O 9  | Digital input/output, PWM output            |
  | 12             | Digital I/O 10 | Digital input/output                        |
  | 13             | Digital I/O 11 | Digital input/output, PWM output, built-in LED |
  | 14             | Analog Input 0 | Analog input                                |
  | 15             | Analog Input 1 | Analog input                                |
  | 16             | Analog Input 2 | Analog input                                |
  | 17             | Analog Input 3 | Analog input                                |
  | 18             | Analog Input 4 | Analog input                                |
  | 19             | Analog Input 5 | Analog input                                |
  | 20             | AREF           | Analog reference voltage                    |
  | 21             | GND            | Ground                                      |
  | 22             | GND            | Ground                                      |
  | 23             | 5V             | 5V power supply                             |
  | 24             | 3.3V           | 3.3V power supply                           |
  | 25             | VIN            | Voltage input (7-12V)                       |
  | 26             | SCL            | I2C Clock line                              |
  | 27             | SDA            | I2C Data line                               |

- **[STMG070KBT6](https://www.st.com/resource/en/datasheet/stm32g070rb.pdf)**
  | **Pin Number** | **Pin Name** | **Specification**                              |
  |----------------|--------------|------------------------------------------------|
  | 1              | VDD           | Power supply (3.3V)                            |
  | 2              | VSS           | Ground                                         |
  | 3              | PA0           | GPIO, Analog Input, TIM2_CH1                   |
  | 4              | PA1           | GPIO, Analog Input, TIM2_CH2                   |
  | 5              | PA2           | GPIO, Analog Input, TIM2_CH3, USART2_TX        |
  | 6              | PA3           | GPIO, Analog Input, TIM2_CH4, USART2_RX        |
  | 7              | PA4           | GPIO, Analog Input, SPI1_NSS, TIM2_ETR         |
  | 8              | PA5           | GPIO, Analog Input, SPI1_SCK, TIM2_CH1         |
  | 9              | PA6           | GPIO, Analog Input, SPI1_MISO, TIM2_CH2        |
  | 10             | PA7           | GPIO, Analog Input, SPI1_MOSI, TIM2_CH3        |
  | 11             | PB0           | GPIO, Analog Input, TIM3_CH3, I2C1_SCL         |
  | 12             | PB1           | GPIO, Analog Input, TIM3_CH4, I2C1_SDA         |
  | 13             | PB2           | GPIO, Analog Input, TIM3_ETR, I2C1_SCL         |
  | 14             | PB3           | GPIO, Analog Input, TIM3_CH1, I2C1_SDA         |
  | 15             | PB4           | GPIO, Analog Input, TIM3_CH2, USART1_TX        |
  | 16             | PB5           | GPIO, Analog Input, TIM3_CH3, USART1_RX        |
  | 17             | PB6           | GPIO, Analog Input, TIM4_CH1, USART1_RTS       |
  | 18             | PB7           | GPIO, Analog Input, TIM4_CH2, USART1_CTS       |
  | 19             | PC0           | GPIO, Analog Input, TIM8_CH1, I2C2_SCL         |
  | 20             | PC1           | GPIO, Analog Input, TIM8_CH2, I2C2_SDA         |
  | 21             | PC2           | GPIO, Analog Input, TIM8_CH3, ADC1_IN10        |
  | 22             | PC3           | GPIO, Analog Input, TIM8_CH4, ADC1_IN11        |
  | 23             | PC4           | GPIO, Analog Input, TIM8_BKIN, ADC1_IN12       |
  | 24             | PC5           | GPIO, Analog Input, TIM8_BKIN2, ADC1_IN13      |
  | 25             | PC6           | GPIO, Analog Input, TIM8_CH1N, USART3_TX       |
  | 26             | PC7           | GPIO, Analog Input, TIM8_CH2N, USART3_RX       |
  | 27             | PC8           | GPIO, Analog Input, TIM8_CH3N, I2C3_SCL        |
  | 28             | PC9           | GPIO, Analog Input, TIM8_CH4N, I2C3_SDA        |
  | 29             | PD0           | GPIO, Analog Input, TIM16_CH1, USART3_TX       |
  | 30             | PD1           | GPIO, Analog Input, TIM16_CH2, USART3_RX       |
  | 31             | PD2           | GPIO, Analog Input, TIM16_BKIN, SPI2_NSS       |
  | 32             | PD3           | GPIO, Analog Input, TIM17_CH1, SPI2_SCK        |
