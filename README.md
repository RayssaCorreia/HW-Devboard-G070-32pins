# Devboard-G070-32pins
Jornada de desenvolvimento  

### Softwares, ferramentas e tecnologias utilizadas para o projeto

- [Git](https://git-scm.com/) - Controlamento de versionamento 
- [Github](https://github.com/) - Compartilhamento do Projeto 
- [Kicad](https://docs.kicad.org/) - Software de desenvolvimento da PCB 
- [STM32 Cube IDE](https://www.st.com/en/development-tools/stm32cubeide.html) - Software de programação
- [Arduino](https://docs.arduino.cc/hardware/uno-rev3/) - Exemplos e talves gravação via a sua IDE
- [Flatcom](http://flatcam.org/manual/installation.html#linux)
- [CNC Router 3018 Pro 200W](https://router66.com.br/produto/cnc-router-3018-pro-200w/) - maquina para prototipagem da placa
### Comparação entre os pinos do Arduino Uno e o micro stm32g070

### Arduino
- Analog pins 

  | Pin | Function    | Type           | Description                 |
  |-----|-------------|----------------|-----------------------------|
  | 1   | NC          | NC             | Not connected               |
  | 2   | IOREF       | IOREF          | Reference for digital logic V - connected to 5V |
  | 3   | Reset       | Reset          | Reset                       |
  | 4   | +3V3        | Power          | +3V3 Power Rail             |
  | 5   | +5V         | Power          | +5V Power Rail              |
  | 6   | GND         | Power          | Ground                      |
  | 7   | GND         | Power          | Ground                      |
  | 8   | VIN         | Power          | Voltage Input               |
  | 9   | A0          | Analog/GPIO    | Analog input 0 / GPIO       |
  | 10  | A1          | Analog/GPIO    | Analog input 1 / GPIO       |
  | 11  | A2          | Analog/GPIO    | Analog input 2 / GPIO       |
  | 12  | A3          | Analog/GPIO    | Analog input 3 / GPIO       |
  | 13  | A4/SDA      | Analog input/I2C | Analog input 4 / I2C Data line |
  | 14  | A5/SCL      | Analog input/I2C | Analog input 5 / I2C Clock line |

- Digital pins 

  | Pin | Function        | Type             | Description                                  |
  |-----|-----------------|------------------|----------------------------------------------|
  | 1   | D0              | Digital/GPIO     | Digital pin 0 / GPIO                         |
  | 2   | D1              | Digital/GPIO     | Digital pin 1 / GPIO                         |
  | 3   | D2              | Digital/GPIO     | Digital pin 2 / GPIO                         |
  | 4   | D3              | Digital/GPIO     | Digital pin 3 / GPIO                         |
  | 5   | D4              | Digital/GPIO     | Digital pin 4 / GPIO                         |
  | 6   | D5              | Digital/GPIO     | Digital pin 5 / GPIO                         |
  | 7   | D6              | Digital/GPIO     | Digital pin 6 / GPIO                         |
  | 8   | D7              | Digital/GPIO     | Digital pin 7 / GPIO                         |
  | 9   | D8              | Digital/GPIO     | Digital pin 8 / GPIO                         |
  | 10  | D9              | Digital/GPIO     | Digital pin 9 / GPIO                         |
  | 11  | SS              | Digital SPI      | Chip Select                                  |
  | 12  | MOSI            | Digital SPI1     | Main Out Secondary In                        |
  | 13  | MISO            | Digital SPI      | Main In Secondary Out                        |
  | 14  | SCK             | Digital SPI      | Serial clock output                          |
  | 15  | GND             | Power            | Ground                                       |
  | 16  | AREF            | Digital          | Analog reference voltage                     |
  | 17  | A4/SD4          | Digital          | Analog input 4 / I2C Data line (duplicated)  |
  | 18  | A5/SD5          | Digital          | Analog input 5 / I2C Clock line (duplicated) |

### [STMG070KBT6](https://www.st.com/resource/en/datasheet/stm32g070rb.pdf)

| Pin Number | Pin Name (function upon reset)       | Alternate Functions                                |
|------------|--------------------------------------|----------------------------------------------------|
| 1          | PB9                                  | IR_OUT, TIM17_CH1, USART3_RX, SPI2_NSS, I2C1_SDA, EVENTOUT |
| 2          | PC14- OSC32_IN (PC14)                | TIM1_BKIN2                                         |
| 3          | PC15- OSC32_OUT (PC15)               | OSC32_EN, OSC_EN, TIM15_BKIN                       |
| 4          | VDD/VDDA                             | -                                                  |
| 5          | VSS/VSSA                             | -                                                  |
| 6          | NRST                                 | -                                                  |
| 7          | PA0                                  | SPI2_SCK, USART2_CTS, USART4_TX                    |
| 8          | PA1                                  | SPI1_SCK/I2S1_CK, USART2_RTS_DE_CK, USART4_RX      |
| 9          | PA2                                  | SPI1_MOSI/I2S1_SD, USART2_TX, TIM15_CH1            |
| 10         | PA3                                  | SPI2_MISO, USART2_RX, TIM15_CH2, EVENTOUT          |
| 11         | PA4                                  | SPI1_NSS/I2S1_WS, SPI2_MOSI, TIM14_CH1, EVENTOUT   |
| 12         | PA5                                  | SPI1_SCK/I2S1_CK, USART3_TX, EVENTOUT              |
| 13         | PA6                                  | SPI1_MISO/I2S1_MCK, TIM3_CH1, TIM1_BKIN, USART3_CTS, TIM16_CH1 |
| 14         | PA7                                  | SPI1_MOSI/I2S1_SD, TIM3_CH2, TIM1_CH1N, TIM14_CH1, TIM17_CH1 |
| 15         | PB0                                  | SPI1_NSS/I2S1_WS, TIM3_CH3, TIM1_CH2N, USART3_RX   |
| 16         | PB1                                  | TIM14_CH1, TIM3_CH4, TIM1_CH3N, USART3_RTS_DE_CK, EVENTOUT |
| 17         | PB2                                  | SPI2_MISO, USART3_TX, EVENTOUT                     |
| 18         | PA8                                  | MCO, SPI2_NSS, TIM1_CH1, EVENTOUT                  |
| 19         | PA9                                  | MCO, USART1_TX, TIM1_CH2, SPI2_MISO, TIM15_BKIN, I2C1_SCL, EVENTOUT |
| 20         | PC6                                  | TIM3_CH1                                           |
| 21         | PA10                                 | SPI2_MOSI, USART1_RX, TIM1_CH3, TIM17_BKIN, I2C1_SDA, EVENTOUT |
| 22         | PA11                                 | SPI1_MISO/I2S1_MCK, USART1_CTS, TIM1_CH4, TIM1_BKIN2, I2C2_SCL |
| 23         | PA12                                 | SPI1_MOSI/I2S1_SD, USART1_RTS_DE_CK, TIM1_ETR, I2S_CKIN, I2C2_SDA |
| 24         | PA13                                 | SWDIO, IR_OUT, EVENTOUT                            |
| 25         | PA14-BOOT0                           | SWCLK, USART2_TX, EVENTOUT                         |
| 26         | PA15                                 | SPI1_NSS/I2S1_WS, USART2_RX, USART4_RTS_DE_CK, USART3_RTS_DE_CK, EVENTOUT |
| 27         | PB3                                  | SPI1_SCK/I2S1_CK, TIM1_CH2, USART1_RTS_DE_CK, EVENTOUT |
| 28         | PB4                                  | SPI1_MISO/I2S1_MCK, TIM3_CH1, USART1_CTS, TIM17_BKIN, EVENTOUT |
| 29         | PB5                                  | SPI1_MOSI/I2S1_SD, TIM3_CH2, TIM16_BKIN, I2C1_SMBA |
| 30         | PB6                                  | USART1_TX, TIM1_CH3, TIM16_CH1N, SPI2_MISO, I2C1_SCL, EVENTOUT |
| 31         | PB7                                  | USART1_RX, SPI2_MOSI, TIM17_CH1N, USART4_CTS, I2C1_SDA, EVENTOUT |
| 32         | PB8                                  | SPI2_SCK, TIM16_CH1, USART3_TX, TIM15_BKIN, I2C1_SCL, EVENTOUT |


# 

<table>
<thead>
  <tr>
    <th colspan="2">Arduino</th>
    <th colspan="2">Stm32G070</th>
  </tr>
  <tr>
    <td>Bit 0</td>
    <td>Bit 1</td>
    <td>Bit 2</td>
    <td>Bit 3</td>
    <td>Bit 4</td>
    <td>Bit 5</td>
    <td>Bit 6</td>
    <td>Bit 7</td>
    <td>Bit 8</td>
    <td>Bit 9</td>
    <td>Bit 10</td>
    <td>Bit 11</td>
    <td>Bit 12</td>
    <td>Bit 13</td>
    <td>Bit 14</td>
    <td>Bit 15</td>
  </tr>
</thead>
<tbody>
  <tr>
    <th colspan="8">ff</th>
    <th colspan="8">01</th>
  </tr>
  <tr>
    <td colspan="9">        Heading GPS</td>
    <td> Acc</td>
    <td> Jammer</td>
    <td> GPS Status</td>
    <td> Power Supply Status</td>
    <td> Critical Battery</td>
    <td> Ignition</td>
    <td> Speed Value</td>
  </tr>
</tbody>
</table>

