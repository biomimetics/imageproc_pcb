| Pin number | dsPIC ports               | ImageProc port(s) | Net name         | Function description   |
| ---------- | ------------------------- | ----------------- | ---------------- | ---------------------- |
| 1          | PWM3H/RE5                 | PWM3H/RE5         | MOTOR_C_IN1      | Motor C IN1            |
| 2          | PWM4L/RE6                 | PWM4L/RE6         | MOTOR_D_IN2      | Motor D IN2            |
| 3          | PWM4H/RE7                 | PWM4H/RE7         | MOTOR_D_IN1      | Motor D IN1            |
| 4          | SCK2/CN8/RG6              | SCK2              | SCK2             | SPI2 flash and MPU     |
| 5          | SDI2/CN9/RG7              | SDI2              | SDI2             | SPI2 flash and MPU     |
| 6          | SDO2/CN10/RG8             | SDO2              | SDO2             | SPI2 flash and MPU     |
| 7          | nMCLR                     | nMCLR             | !RESET           | JP1.5 (ICD)            |
| 8          | nSS2/CN11/RG9             | nSS2              | !SS2_1           | SPI2 flash (nSS2_1)    |
| 9          | VSS                       | VSS               | GND              | GND                    |
| 10         | VDD                       | VDD               | 3.3V             | 3.3V                   |
| 11         | AN5/QEB/IC8/CN7/RB5       | -                 | AN5/QEB/IC8/RB5  | PAD4                   |
| 12         | AN4/QEA/IC7/CN6/RB4       | -                 | AN4/QEA/IC7/RB4  | PAD3                   |
| 13         | AN3/INDX/CN5/RB3          | -                 | AN3/INDX/RB3     | PAD2                   |
| 14         | AN2/nSS1/CN4/RB2          | nSS1              | nSS1             | SPI1 radio             |
| 15         | PGEC3/AN1/VREF-/CN3/RB1   | -                 | AN1/RB1          | PAD1                   |
| 16         | PGED3/AN0/VREF+/CN2/RB0   | AN0               | BATT_LEVEL       | Battery level sense    |
| 17         | PGEC1/AN6/OCFA/RB6        | PGEC1             | PGC              | JP1.1 (ICD)            |
| 18         | PGED1/AN7/RB7             | PGED1             | PGD              | JP1.2 (ICD)            |
| 19         | AVDD                      | AVDD              | 3.3V             | 3.3V                   |
| 20         | AVSS                      | AVSS              | GND              | GND                    |
| 21         | nU2CTS/AN8/RB8            | AN8               | MOTOR_A_BEMF     | Motor A BEMF           |
| 22         | AN9/RB9                   | AN9               | MOTOR_B_BEMF     | Motor B BEMF           |
| 23         | TMS/AN10/RB10             | AN10              | MOTOR_C_BEMF     | Motor C BEMF           |
| 24         | TDO/AN11/RB11             | AN11              | MOTOR_D_BEMF     | Motor D BEMF           |
| 25         | VSS                       | VSS               | GND              | GND                    |
| 26         | VDD                       | VDD               | 3.3V             | 3.3V                   |
| 27         | TCK/AN1/RB12              | RB12              | RD_LED           | Red LED                |
| 28         | TDO/AN13/RB13             | RB13              | GN_LED           | Green LED              |
| 29         | nU2RTS/AN14/RB14          | RB14              | YW_LED           | Yellow LED             |
| 30         | AN15/OCFB/CN12/RB15       | RB15              | RADIO_SLP_TR     | Radio SLP_TR           |
| 31         | U2RX/SDA2/CN17/RF4        | U2RX              | U2RX             | JP2.6 U2RX             |
| 32         | U2TX/SCL2/CN18/RF5        | U2TX              | U2TX             | JP2.4 U2TX             |
| 33         | U1TX/SDO1/RF3             | SDO1              | SDO1             | SPI1 radio             |
| 34         | U1RX/SDI1/RF2             | SDI1              | SDI1             | SPI1 radio             |
| 35         | nU2RTS/SCK1/INT0/RF6      | SCK1              | SCK1             | SPI1 radio             |
| 36         | SDA1/RG3                  | SDA1              | SDA1             | I2C1 camera, JP3.5     |
| 37         | SCL1/RG2                  | SCL1              | SCL1             | I2C1 camera, JP3.3     |
| 38         | VDD                       | VDD               | 3.3V             | 3.3V                   |
| 39         | OSC1/CLKIN/RC12           | OSC1              | 40MHZ            | 40 MHz oscillator      |
| 40         | OSC2/CLKO/RC15            | RC15              | !SS2_2           | MPU SS2                |
| 41         | VSS                       | VSS               | GND              | GND                    |
| 42         | IC1/nFLTA/INT1/RD8        | INT1              | IMU_IRQ          | MPU interrupt          |
| 43         | IC2/nU1CTS/nFLTB/INT2/RD9 | INT2              | LOWBATT_IRQ      | Low voltage detect     |
| 44         | IC3/INT3/RD10             | -                 | IC3/INT3/RD10    | PAD5                   |
| 45         | IC4/INT4/RD11             | INT4              | RADIO_IRQ        | Radio IRQ              |
| 46         | OC1/RD0                   | RD0               | CAM_D0           | Camera D0              |
| 47         | PGED2/SOSCI/T4CK/CN1/RC13 | RC13              | CAM_VSYNC        | Camera VSYNC           |
| 48         | PGEC2/SOSCO/T1CK/CN0/RC14 | RC14              | CAM_PWDM         | Camera PWDN            |
| 49         | OC2/RD1                   | RD1               | CAM_D1           | Camera D1              |
| 50         | OC3/RD2                   | RD2               | CAM_D2           | Camera D2              |
| 51         | OC4/RD3                   | RD3               | CAM_D3           | Camera D3              |
| 52         | OC5/IC5/CN13/RD4          | RD4               | CAM_D4           | Camera D4              |
| 53         | OC6/IC6/CN14/RD5          | RD5               | CAM_D5           | Camera D5              |
| 54         | OC7/CN15/RD6              | RD6               | CAM_D6           | Camera D6              |
| 55         | OC8/UPDN/CN16/RD7         | RD7               | CAM_D7           | Camera D7              |
| 56         | VCAP                      | VCAP              | N$28             | Charge pump capacitor  | 
| 57         | VDD                       | VDD               | 3.3V             | 3.3V                   |
| 58         | C1RX/RF0                  | RF0               | CAM_HREF         | Camera HREF            |
| 59         | C1TX/RF1                  | RF1               | CAM_PCLK         | Camera PCLK            |
| 60         | PWM1L/RE0                 | PWM1L/RE0         | MOTOR_A_IN2      | Motor A IN2            |
| 61         | PWM1H/RE1                 | PWM1H/RE1         | MOTOR_A_IN1      | Motor A IN1            |
| 62         | PWM2L/RE2                 | PWM2L/RE2         | MOTOR_B_IN2      | Motor B IN2            |
| 63         | PWM2H/RE3                 | PWM2H/RE3         | MOTOR_B_IN1      | Motor B IN1            |
| 64         | PWM3L/RE4                 | PWM3L/RE4         | MOTOR_C_IN2      | Motor C IN2            |
