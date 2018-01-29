EESchema Schematic File Version 2
LIBS:power
LIBS:device
LIBS:transistors
LIBS:conn
LIBS:linear
LIBS:regul
LIBS:74xx
LIBS:cmos4000
LIBS:adc-dac
LIBS:memory
LIBS:xilinx
LIBS:microcontrollers
LIBS:dsp
LIBS:microchip
LIBS:analog_switches
LIBS:motorola
LIBS:texas
LIBS:intel
LIBS:audio
LIBS:interface
LIBS:digital-audio
LIBS:philips
LIBS:display
LIBS:cypress
LIBS:siliconi
LIBS:opto
LIBS:atmel
LIBS:contrib
LIBS:valves
LIBS:nodemcu
LIBS:oled096
LIBS:hc-sr04
LIBS:battery_management
LIBS:ESP-Sonar-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L NodeMCU_0.9 ESP8266
U 1 1 58A194F7
P 2450 2550
F 0 "ESP8266" H 2450 3350 50  0000 C CNN
F 1 "ESP8266" H 2450 1700 50  0000 C CNN
F 2 "nodemcu:NodeMCU_Amica_R2" H 2700 2550 50  0001 C CNN
F 3 "" H 2700 2550 50  0000 C CNN
	1    2450 2550
	1    0    0    -1  
$EndComp
Text GLabel 1550 3250 0    60   Input ~ 0
5volts
Wire Wire Line
	2000 3250 1550 3250
$Comp
L R R1
U 1 1 58A195D8
P 1950 3900
F 0 "R1" V 2030 3900 50  0000 C CNN
F 1 "2.2k" V 1950 3900 50  0000 C CNN
F 2 "Resistors_SMD:R_1206_HandSoldering" V 1880 3900 50  0001 C CNN
F 3 "" H 1950 3900 50  0000 C CNN
	1    1950 3900
	1    0    0    -1  
$EndComp
$Comp
L R R2
U 1 1 58A19620
P 1950 4350
F 0 "R2" V 2030 4350 50  0000 C CNN
F 1 "4.7k" V 1950 4350 50  0000 C CNN
F 2 "Resistors_SMD:R_1206_HandSoldering" H 1880 4350 50  0001 C CNN
F 3 "" H 1950 4350 50  0000 C CNN
	1    1950 4350
	1    0    0    -1  
$EndComp
Wire Wire Line
	1550 3700 1950 3700
Wire Wire Line
	1950 3700 1950 3750
Wire Wire Line
	1950 4050 1950 4200
Wire Wire Line
	1950 4500 1950 4850
Text GLabel 1950 4850 0    60   Input ~ 0
GND
Text GLabel 900  3150 0    60   Input ~ 0
GND
Text GLabel 3300 2750 2    60   Input ~ 0
D7
Wire Wire Line
	2900 2750 3300 2750
Text GLabel 2400 4100 2    60   Input ~ 0
D7
Wire Wire Line
	2400 4100 1950 4100
Connection ~ 1950 4100
Text GLabel 1500 2650 0    60   Input ~ 0
3.3v
Wire Wire Line
	2000 2650 1500 2650
Text GLabel 3600 5950 2    60   Input ~ 0
GND
Text Notes 3150 5150 0    60   ~ 0
HC-SR04
Text GLabel 3550 5500 2    60   Input ~ 0
5volts
Text GLabel 3600 5650 2    60   Input ~ 0
Trig
Text GLabel 1550 3700 0    60   Input ~ 0
ECHO
Text GLabel 3350 2600 2    60   Input ~ 0
Trig
Wire Wire Line
	3350 2600 3200 2600
Wire Wire Line
	3200 2600 3200 2650
Wire Wire Line
	3200 2650 2900 2650
$Comp
L Oled96 OLED0.96_1
U 1 1 58A1AE19
P 4450 4250
F 0 "OLED0.96_1" H 4750 4150 60  0000 C CNN
F 1 "Oled96" H 4850 4600 60  0000 C CNN
F 2 "nodemcu:Oled96" H 4450 4200 60  0001 C CNN
F 3 "" H 4450 4200 60  0001 C CNN
	1    4450 4250
	1    0    0    -1  
$EndComp
Wire Wire Line
	2900 2050 5050 2050
Wire Wire Line
	5050 2050 5050 3250
Wire Wire Line
	4950 3250 4950 1950
Wire Wire Line
	4950 1950 2900 1950
Wire Wire Line
	4850 3250 4850 2350
Wire Wire Line
	4850 2350 2900 2350
Wire Wire Line
	4750 3250 4750 2450
Wire Wire Line
	4750 2450 2900 2450
$Comp
L HEADER-1x04 GPIO1
U 1 1 58A1B320
P 1650 6600
F 0 "GPIO1" H 1600 6850 60  0000 L BNB
F 1 "GPIO-Ports" V 1800 6600 40  0000 C CNN
F 2 "Socket_Strips:Socket_Strip_Straight_1x04_Pitch2.54mm" H 1650 6600 60  0001 C CNN
F 3 "" H 1650 6600 60  0001 C CNN
F 4 "-" H 1600 6950 40  0001 L BNN "Part"
F 5 "Connector" H 1600 7050 40  0001 L BNN "Family"
	1    1650 6600
	1    0    0    -1  
$EndComp
Text GLabel 3450 2150 2    60   Input ~ 0
D3
Wire Wire Line
	2900 2150 3450 2150
Text GLabel 6300 2050 0    60   Input ~ 0
3.3v
$Comp
L R R3
U 1 1 58A1B6DD
P 6850 2250
F 0 "R3" V 6930 2250 50  0000 C CNN
F 1 "4.7k" V 6850 2250 50  0000 C CNN
F 2 "Resistors_SMD:R_1206_HandSoldering" H 6780 2250 50  0001 C CNN
F 3 "" H 6850 2250 50  0000 C CNN
	1    6850 2250
	1    0    0    -1  
$EndComp
Wire Wire Line
	6300 2050 6850 2050
Wire Wire Line
	6850 2050 6850 2100
Text GLabel 6300 2500 0    60   Input ~ 0
D3
$Comp
L SW_PUSH_SMALL_H SW1
U 1 1 58A1B843
P 6850 3050
F 0 "SW1" H 6930 3160 50  0000 C CNN
F 1 "SW_PUSH_SMALL_H" H 7210 2990 50  0001 C CNN
F 2 "Buttons_Switches_SMD:SW_SPST_B3S-1000" H 6850 3250 50  0001 C CNN
F 3 "" H 6850 3250 50  0000 C CNN
	1    6850 3050
	0    1    1    0   
$EndComp
Text GLabel 6300 3500 0    60   Input ~ 0
GND
Wire Wire Line
	6850 2400 6850 2900
Wire Wire Line
	6300 2500 6850 2500
Connection ~ 6850 2500
Wire Wire Line
	6850 3200 6850 3500
Wire Wire Line
	6850 3500 6300 3500
Text Notes 6400 1950 0    60   ~ 0
Bouton 1
Text GLabel 3800 2250 2    60   Input ~ 0
D4
Wire Wire Line
	2900 2250 3800 2250
Text GLabel 7050 4000 0    60   Input ~ 0
3.3v
$Comp
L R R4
U 1 1 58A1BB72
P 7600 4200
F 0 "R4" V 7680 4200 50  0000 C CNN
F 1 "4.7k" V 7600 4200 50  0000 C CNN
F 2 "Resistors_SMD:R_1206_HandSoldering" H 7530 4200 50  0001 C CNN
F 3 "" H 7600 4200 50  0000 C CNN
	1    7600 4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	7050 4000 7600 4000
Wire Wire Line
	7600 4000 7600 4050
$Comp
L SW_PUSH_SMALL_H SW2
U 1 1 58A1BB7B
P 7600 5000
F 0 "SW2" H 7680 5110 50  0000 C CNN
F 1 "SW_PUSH_SMALL_H" H 7960 4940 50  0001 C CNN
F 2 "Buttons_Switches_SMD:SW_SPST_B3S-1000" H 7600 5200 50  0001 C CNN
F 3 "" H 7600 5200 50  0000 C CNN
	1    7600 5000
	0    1    1    0   
$EndComp
Text GLabel 7050 5450 0    60   Input ~ 0
GND
Wire Wire Line
	7600 4350 7600 4850
Wire Wire Line
	7050 4450 7600 4450
Connection ~ 7600 4450
Wire Wire Line
	7600 5150 7600 5450
Wire Wire Line
	7600 5450 7050 5450
Text Notes 7150 3900 0    60   ~ 0
Bouton 2\n
Text GLabel 7050 4450 0    60   Input ~ 0
D4
Text GLabel 3950 2550 2    60   Input ~ 0
D5
Wire Wire Line
	2900 2550 3250 2550
Wire Wire Line
	3250 2550 3250 2500
Wire Wire Line
	3250 2500 3750 2500
Wire Wire Line
	3750 2500 3750 2550
Wire Wire Line
	3750 2550 3950 2550
Text GLabel 7700 2100 0    60   Input ~ 0
3.3v
$Comp
L R R5
U 1 1 58A1C2D5
P 8250 2300
F 0 "R5" V 8330 2300 50  0000 C CNN
F 1 "4.7k" V 8250 2300 50  0000 C CNN
F 2 "Resistors_SMD:R_1206_HandSoldering" H 8180 2300 50  0001 C CNN
F 3 "" H 8250 2300 50  0000 C CNN
	1    8250 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	7700 2100 8250 2100
Wire Wire Line
	8250 2100 8250 2150
$Comp
L SW_PUSH_SMALL_H SW3
U 1 1 58A1C2DE
P 8250 3100
F 0 "SW3" H 8330 3210 50  0000 C CNN
F 1 "SW_PUSH_SMALL_H" H 8610 3040 50  0001 C CNN
F 2 "Buttons_Switches_SMD:SW_SPST_B3S-1000" H 8250 3300 50  0001 C CNN
F 3 "" H 8250 3300 50  0000 C CNN
	1    8250 3100
	0    1    1    0   
$EndComp
Text GLabel 7700 3550 0    60   Input ~ 0
GND
Wire Wire Line
	8250 2450 8250 2950
Wire Wire Line
	7700 2550 8250 2550
Connection ~ 8250 2550
Wire Wire Line
	8250 3250 8250 3550
Wire Wire Line
	8250 3550 7700 3550
Text Notes 7800 2000 0    60   ~ 0
Bouton 3
Text GLabel 7700 2550 0    60   Input ~ 0
D5
$Comp
L HC-SR04 HC-SR04
U 1 1 58A1D05A
P 3150 5650
F 0 "HC-SR04" H 2900 5350 60  0000 C CNN
F 1 "HC-SR04" H 3050 5950 60  0000 C CNN
F 2 "Socket_Strips:Socket_Strip_Straight_1x04_Pitch2.54mm" H 3150 5650 60  0001 C CNN
F 3 "" H 3150 5650 60  0000 C CNN
	1    3150 5650
	1    0    0    -1  
$EndComp
Wire Wire Line
	3350 5500 3550 5500
Wire Wire Line
	3350 5600 3500 5600
Wire Wire Line
	3500 5600 3500 5650
Wire Wire Line
	3500 5650 3600 5650
Wire Wire Line
	3350 5800 3450 5800
Wire Wire Line
	3450 5800 3450 5950
Wire Wire Line
	3450 5950 3600 5950
Text GLabel 3600 5800 2    60   Input ~ 0
ECHO
Wire Wire Line
	3350 5700 3500 5700
Wire Wire Line
	3500 5700 3500 5800
Wire Wire Line
	3500 5800 3600 5800
Text GLabel 3450 1850 2    60   Input ~ 0
GPIO16
Wire Wire Line
	2900 1850 3450 1850
Text GLabel 1050 6450 0    60   Input ~ 0
GPIO16
Wire Wire Line
	1050 6450 1500 6450
Text GLabel 3600 2850 2    60   Input ~ 0
GPIO15
Wire Wire Line
	2900 2850 3600 2850
Text GLabel 1050 6550 0    60   Input ~ 0
GPIO15
Wire Wire Line
	1050 6550 1500 6550
Text GLabel 1500 1850 0    60   Input ~ 0
Analog
Wire Wire Line
	2000 1850 1500 1850
Text GLabel 1000 6700 0    60   Input ~ 0
Analog
Wire Wire Line
	1500 6650 1100 6650
Wire Wire Line
	1100 6650 1100 6700
Wire Wire Line
	1100 6700 1000 6700
Text GLabel 1350 3050 0    60   Input ~ 0
Reset
Wire Wire Line
	2000 3050 1350 3050
Text GLabel 1000 6850 0    60   Input ~ 0
Reset
Wire Wire Line
	1500 6750 1100 6750
Wire Wire Line
	1100 6750 1100 6850
Wire Wire Line
	1100 6850 1000 6850
NoConn ~ 2900 2950
NoConn ~ 2900 3050
NoConn ~ 2000 2950
$Comp
L HEADER-1x04 PWR_SRC1
U 1 1 58A1F43C
P 3100 6850
F 0 "PWR_SRC1" H 3050 7100 60  0000 L BNB
F 1 "Power SRC" V 3250 6850 40  0000 C CNN
F 2 "Socket_Strips:Socket_Strip_Straight_1x04_Pitch2.54mm" H 3100 6850 60  0001 C CNN
F 3 "" H 3100 6850 60  0001 C CNN
F 4 "-" H 3050 7200 40  0001 L BNN "Part"
F 5 "Connector" H 3050 7300 40  0001 L BNN "Family"
	1    3100 6850
	1    0    0    -1  
$EndComp
Text Notes 800  6050 0    60   ~ 0
GPIO PORT Connectors
Text GLabel 1150 2750 0    60   Input ~ 0
GND_P
Wire Wire Line
	2000 2750 1150 2750
Text GLabel 2800 6700 0    60   Input ~ 0
GND_P
Wire Wire Line
	2950 6700 2800 6700
Text GLabel 3350 3250 2    60   Input ~ 0
3.3v_P
Wire Wire Line
	2900 3250 3350 3250
Text GLabel 2400 6800 0    60   Input ~ 0
3.3v_P
Wire Wire Line
	2950 6800 2400 6800
Text GLabel 2750 6900 0    60   Input ~ 0
5volts
Wire Wire Line
	2750 6900 2950 6900
NoConn ~ 2000 2850
NoConn ~ 2000 2550
NoConn ~ 2900 3150
NoConn ~ 1100 8050
Text Notes 6950 1600 0    60   ~ 0
Clavier de base
Text GLabel 2400 7000 0    60   Input ~ 0
3.3v_P
Wire Wire Line
	2950 7000 2400 7000
$Comp
L PWR_FLAG #FLG01
U 1 1 58A2103D
P 3150 3350
F 0 "#FLG01" H 3150 3445 50  0001 C CNN
F 1 "PWR_FLAG" H 3150 3530 50  0000 C CNN
F 2 "" H 3150 3350 50  0000 C CNN
F 3 "" H 3150 3350 50  0000 C CNN
	1    3150 3350
	-1   0    0    1   
$EndComp
Wire Wire Line
	3150 3250 3150 3350
Connection ~ 3150 3250
$Comp
L PWR_FLAG #FLG02
U 1 1 58A21135
P 1750 3400
F 0 "#FLG02" H 1750 3495 50  0001 C CNN
F 1 "PWR_FLAG" H 1750 3580 50  0000 C CNN
F 2 "" H 1750 3400 50  0000 C CNN
F 3 "" H 1750 3400 50  0000 C CNN
	1    1750 3400
	-1   0    0    1   
$EndComp
Wire Wire Line
	1750 3250 1750 3400
Connection ~ 1750 3250
$Comp
L PWR_FLAG #FLG03
U 1 1 58A211F8
P 1750 2550
F 0 "#FLG03" H 1750 2645 50  0001 C CNN
F 1 "PWR_FLAG" H 1750 2730 50  0000 C CNN
F 2 "" H 1750 2550 50  0000 C CNN
F 3 "" H 1750 2550 50  0000 C CNN
	1    1750 2550
	1    0    0    -1  
$EndComp
Wire Wire Line
	1750 2550 1750 2650
Connection ~ 1750 2650
$Comp
L PWR_FLAG #FLG04
U 1 1 58A21675
P 2850 6450
F 0 "#FLG04" H 2850 6545 50  0001 C CNN
F 1 "PWR_FLAG" H 2850 6630 50  0000 C CNN
F 2 "" H 2850 6450 50  0000 C CNN
F 3 "" H 2850 6450 50  0000 C CNN
	1    2850 6450
	1    0    0    -1  
$EndComp
Wire Wire Line
	2850 6450 2850 6700
Wire Wire Line
	2850 6700 2900 6700
Connection ~ 2900 6700
Wire Wire Line
	2000 3150 900  3150
$Comp
L PWR_FLAG #FLG05
U 1 1 58A2200C
P 1000 3250
F 0 "#FLG05" H 1000 3345 50  0001 C CNN
F 1 "PWR_FLAG" H 1000 3430 50  0000 C CNN
F 2 "" H 1000 3250 50  0000 C CNN
F 3 "" H 1000 3250 50  0000 C CNN
	1    1000 3250
	-1   0    0    1   
$EndComp
Wire Wire Line
	1000 3250 1000 3150
Connection ~ 1000 3150
$Comp
L PWR_FLAG #FLG06
U 1 1 58A22159
P 4600 2300
F 0 "#FLG06" H 4600 2395 50  0001 C CNN
F 1 "PWR_FLAG" H 4600 2480 50  0000 C CNN
F 2 "" H 4600 2300 50  0000 C CNN
F 3 "" H 4600 2300 50  0000 C CNN
	1    4600 2300
	1    0    0    -1  
$EndComp
Wire Wire Line
	4600 2300 4600 2350
Connection ~ 4600 2350
$Comp
L PWR_FLAG #FLG07
U 1 1 58A221F3
P 4400 2550
F 0 "#FLG07" H 4400 2645 50  0001 C CNN
F 1 "PWR_FLAG" H 4400 2730 50  0000 C CNN
F 2 "" H 4400 2550 50  0000 C CNN
F 3 "" H 4400 2550 50  0000 C CNN
	1    4400 2550
	-1   0    0    1   
$EndComp
Wire Wire Line
	4400 2550 4400 2450
Connection ~ 4400 2450
$EndSCHEMATC
