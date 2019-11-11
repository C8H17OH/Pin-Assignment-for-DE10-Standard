# Pin Assignment for DE10-Standard

FPGA实验用DE10-Standard开发板引脚表

适用于：南京大学《数字逻辑电路》课程

数据来源：DE10-Standard User Manual

更新：Excel版本已上线，可直接复制到Quartus中。

更新：七段数码管数值对应表已上线，内含Verilog代码。

更新：PS/2键盘接口已在Markdown和Excel文件中上线。

## 输入
### 开关 Slide Switches (SW)
| Signal Name | FPGA Pin No. |  Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| SW[0] | PIN_AB30 | Slide Switch[0] | Depend on JP3 |
| SW[1] | PIN_Y27 | Slide Switch[1] | Depend on JP3 |
| SW[2] | PIN_AB28 | Slide Switch[2] | Depend on JP3 |
| SW[3] | PIN_AC30 | Slide Switch[3] | Depend on JP3 |
| SW[4] | PIN_W25 | Slide Switch[4] | Depend on JP3 |
| SW[5] | PIN_V25 | Slide Switch[5] | Depend on JP3 |
| SW[6] | PIN_AC28 | Slide Switch[6] | Depend on JP3 |
| SW[7] | PIN_AD30 | Slide Switch[7] | Depend on JP3 |
| SW[8] | PIN_AC29 | Slide Switch[8] | Depend on JP3 |
| SW[9] | PIN_AA30 | Slide Switch[9] | Depend on JP3 |

### 按钮 Push-buttons (KEY)
| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| KEY[0] | PIN_AJ4 | Push-button[0] | 3.3V |
| KEY[1] | PIN_AK4 | Push-button[1] | 3.3V |
| KEY[2] | PIN_AA14 | Push-button[2] | 3.3V |
| KEY[3] | PIN_AA15 | Push-button[3] | 3.3V |

### 时钟 Clock Inputs (CLOCK)
| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| CLOCK_50 | PIN_AF14 | 50 MHz clock input | 3.3V |
| CLOCK2_50 | PIN_AA16 | 50 MHz clock input | 3.3V |
| CLOCK3_50 | PIN_Y26 | 50 MHz clock input | 3.3V |
| CLOCK4_50 | PIN_K14 | 50 MHz clock input | 3.3V |
| HPS_CLOCK1_25 | PIN_D25 | 25 MHz clock input | 3.3V |
| HPS_CLOCK2_25 | PIN_F25 | 25 MHz clock input | 3.3V |

### 键盘 PS/2 Serial Port (PS2)
| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| PS2_CLK | PIN_AB25 | PS/2 Clock | 3.3V |
| PS2_DAT | PIN_AA25 | PS/2 Data | 3.3V |
| PS2_CLK2 | PIN_AC25 | PS/2 Clock (reserved for second PS/2 device) | 3.3V |
| PS2_DAT2 | PIN_AB26 | PS/2 Data (reserved for second PS/2 device)	| 3.3V |

## 输出
### 灯泡 LEDs (LEDR)
| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| LEDR[0] | PIN_AA24 | LED [0] | 3.3V |
| LEDR[1] | PIN_AB23 | LED [1] | 3.3V |
| LEDR[2] | PIN_AC23 | LED [2] | 3.3V |
| LEDR[3] | PIN_AD24 | LED [3] | 3.3V |
| LEDR[4] | PIN_AG25 | LED [4] | 3.3V |
| LEDR[5] | PIN_AF25 | LED [5] | 3.3V |
| LEDR[6] | PIN_AE24 | LED [6] | 3.3V |
| LEDR[7] | PIN_AF24 | LED [7] | 3.3V |
| LEDR[8] | PIN_AB22 | LED [8] | 3.3V |
| LEDR[9] | PIN_AC22 | LED [9] | 3.3V |

### 七段数码管 Seven Segment Digits (HEX)
| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| HEX0[0] | PIN_W17 | Seven Segment Digit 0[0] | 3.3V |
| HEX0[1] | PIN_V18 | Seven Segment Digit 0[1] | 3.3V |
| HEX0[2] | PIN_AG17 | Seven Segment Digit 0[2] | 3.3V |
| HEX0[3] | PIN_AG16 | Seven Segment Digit 0[3] | 3.3V |
| HEX0[4] | PIN_AH17 | Seven Segment Digit 0[4] | 3.3V |
| HEX0[5] | PIN_AG18 | Seven Segment Digit 0[5] | 3.3V |
| HEX0[6] | PIN_AH18 | Seven Segment Digit 0[6] | 3.3V |

| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| HEX1[0] | PIN_AF16 | Seven Segment Digit 1[0] | 3.3V |
| HEX1[1] | PIN_V16 | Seven Segment Digit 1[1] | 3.3V |
| HEX1[2] | PIN_AE16 | Seven Segment Digit 1[2] | 3.3V |
| HEX1[3] | PIN_AD17 | Seven Segment Digit 1[3] | 3.3V |
| HEX1[4] | PIN_AE18 | Seven Segment Digit 1[4] | 3.3V |
| HEX1[5] | PIN_AE17 | Seven Segment Digit 1[5] | 3.3V |
| HEX1[6] | PIN_V17 | Seven Segment Digit 1[6] | 3.3V |

| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| HEX2[0] | PIN_AA21 | Seven Segment Digit 2[0] | 3.3V |
| HEX2[1] | PIN_AB17 | Seven Segment Digit 2[1] | 3.3V |
| HEX2[2] | PIN_AA18 | Seven Segment Digit 2[2] | 3.3V |
| HEX2[3] | PIN_Y17 | Seven Segment Digit 2[3] | 3.3V |
| HEX2[4] | PIN_Y18 | Seven Segment Digit 2[4] | 3.3V |
| HEX2[5] | PIN_AF18 | Seven Segment Digit 2[5] | 3.3V |
| HEX2[6] | PIN_W16 | Seven Segment Digit 2[6] | 3.3V |

| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| HEX3[0] | PIN_Y19 | Seven Segment Digit 3[0] | 3.3V |
| HEX3[1] | PIN_W19 | Seven Segment Digit 3[1] | 3.3V |
| HEX3[2] | PIN_AD19 | Seven Segment Digit 3[2] | 3.3V |
| HEX3[3] | PIN_AA20 | Seven Segment Digit 3[3] | 3.3V |
| HEX3[4] | PIN_AC20 | Seven Segment Digit 3[4] | 3.3V |
| HEX3[5] | PIN_AA19 | Seven Segment Digit 3[5] | 3.3V |
| HEX3[6] | PIN_AD20 | Seven Segment Digit 3[6] | 3.3V |

| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| HEX4[0] | PIN_AD21 | Seven Segment Digit 4[0] | 3.3V |
| HEX4[1] | PIN_AG22 | Seven Segment Digit 4[1] | 3.3V |
| HEX4[2] | PIN_AE22 | Seven Segment Digit 4[2] | 3.3V |
| HEX4[3] | PIN_AE23 | Seven Segment Digit 4[3] | 3.3V |
| HEX4[4] | PIN_AG23 | Seven Segment Digit 4[4] | 3.3V |
| HEX4[5] | PIN_AF23 | Seven Segment Digit 4[5] | 3.3V |
| HEX4[6] | PIN_AH22 | Seven Segment Digit 4[6] | 3.3V |

| Signal Name | FPGA Pin No. | Description | I/O Standard |
| -------- | -------- | -------- | -------- |
| HEX5[0] | PIN_AF21 | Seven Segment Digit 5[0] | 3.3V |
| HEX5[1] | PIN_AG21 | Seven Segment Digit 5[1] | 3.3V |
| HEX5[2] | PIN_AF20 | Seven Segment Digit 5[2] | 3.3V |
| HEX5[3] | PIN_AG20 | Seven Segment Digit 5[3] | 3.3V |
| HEX5[4] | PIN_AE19 | Seven Segment Digit 5[4] | 3.3V |
| HEX5[5] | PIN_AF19 | Seven Segment Digit 5[5] | 3.3V |
| HEX5[6] | PIN_AB21 | Seven Segment Digit 5[6] | 3.3V |

当课堂实验使用新引脚时将持续整理

欢迎Watch/Star/Fork，欢迎纠错/提议/帮助完善。
