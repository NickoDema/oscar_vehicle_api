#### Пример slp пакетов:

```
# |-------------SLP-HEADER-----|  |---------------------------SLP-DATA--------------------------| |-CRC-|
# Sof SA  DA  CMD STAT |-LEN| CRC |-BUS-| |CANID|             LEN CNC TP |OSCAR-CAN-DATA| ST  CRC
# AA  01  ff  10  00   10 00  1c  01  01  fc  07  00  00  00  08  ff  02  00  01  00  00  01  00  0c  3d  -  LED ON OSCAR CMD

# CAR
# AA  FF  01  10  00   10 00  C1  02  01  60  02  00  00  00  08  08  00  00  00  00  FF  FF  70  07  2D  -  EPS TORQUE STATUS
# AA  FF  01  10  00   10 00  C1  02  02  B4  00  00  00  00  08  00  00  00  00  C8  00  00  84  CD  58  -  CAR SPEED STATUS
# AA  FF  01  10  00   10 00  C1  02  02  24  00  00  00  00  08  02  01  01  FB  F2  09  80  A6  E1  AD  -  YAW_RATE, Y_ACC, SW_TORQUE | WTF???
# AA  FF  01  10  00   10 00  C1  02  02  C4  01  00  00  00  08  05  DF  00  00  00  00  00  B1  81  BE  -  MOTOR RPM STATUS

# AA  FF  01  10  00   10 00  C1  02  02  60  02  00  00  00  08  08  00  00  00  00  FF  F7  68  B2  C4  -  EPS TORQUE STATUS
# AA  FF  01  10  00   10 00  C1  02  02  B4  00  00  00  00  08  00  00  00  00  C8  00  00  84  CD  58  -  CAR SPEED STATUS
# AA  FF  01  10  00   10 00  C1  02  01  43  03  00  00  00  08  00  00  41  00  00  00  00  F8  0E  8B  -  ACC/DEC CMD!??
# AA  FF  01  10  00   10 00  C1  02  01  25  00  00  00  00  08  00  00  00  02  A0  00  00  CF  3D  30  -  STEERING WHEEL POSE, (VELOCITY?) STATUS
# AA  FF  01  10  00   10 00  C1  02  01  24  00  00  00  00  08  02  01  01  FC  F2  09  80  A7  31  39  -  YAW_RATE, Y_ACC, SW_TORQUE | WTF???
# AA  FF  01  10  00   10 00  C1  02  01  AA  00  00  00  00  08  1A  6F  1A  6F  1A  6F  1A  6F  47  BA  -  WHEELS SPEED STATUS
# AA  FF                                  28  02                                                          -  ACC/DEC STATUS
```
