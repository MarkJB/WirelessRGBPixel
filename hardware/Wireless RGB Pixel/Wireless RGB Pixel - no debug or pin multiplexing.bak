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
LIBS:custom
LIBS:Wireless RGB Pixel_minimise_connections-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "Wireless RGB Pixel"
Date "2016-07-09"
Rev "1"
Comp ""
Comment1 "Copyright Mark Benson 2016"
Comment2 "License Creative Commons Atribution 4.0 (CC-BY 4.0)"
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L ATTINY85-P U1
U 1 1 577FF051
P 5600 2900
F 0 "U1" H 4450 3300 50  0000 C CNN
F 1 "ATTINY85-P" H 6600 2500 50  0000 C CNN
F 2 "SMD_Packages:SOIC-8-N" H 6600 2900 50  0000 C CIN
F 3 "" H 5600 2900 50  0000 C CNN
	1    5600 2900
	1    0    0    -1  
$EndComp
$Comp
L CP C1
U 1 1 577FF120
P 7400 2900
F 0 "C1" H 7425 3000 50  0000 L CNN
F 1 "100u" H 7425 2800 50  0000 L CNN
F 2 "Capacitors_Tantalum_SMD:TantalC_SizeB_EIA-3528_Reflow" H 7438 2750 50  0001 C CNN
F 3 "" H 7400 2900 50  0000 C CNN
	1    7400 2900
	1    0    0    -1  
$EndComp
$Comp
L CONN_01X07 P1
U 1 1 57D6DA44
P 2750 5000
F 0 "P1" H 2750 5400 50  0000 C CNN
F 1 "CONN_01X07" V 2850 5000 50  0000 C CNN
F 2 "Custom:CONN7" H 2750 5000 50  0001 C CNN
F 3 "" H 2750 5000 50  0000 C CNN
	1    2750 5000
	0    1    1    0   
$EndComp
Wire Wire Line
	2850 4300 5050 4300
Wire Wire Line
	3950 4300 3950 2850
Wire Wire Line
	3950 2850 4250 2850
Wire Wire Line
	4250 2750 3850 2750
Wire Wire Line
	3850 2750 3850 4200
Wire Wire Line
	2750 4200 5050 4200
Wire Wire Line
	4250 2650 3750 2650
Wire Wire Line
	3750 2650 3750 4100
Wire Wire Line
	3050 4100 5050 4100
Wire Wire Line
	7100 5050 5950 5050
Wire Wire Line
	5000 4850 5050 4850
Wire Wire Line
	4250 3050 4150 3050
Wire Wire Line
	6150 4850 5950 4850
Wire Wire Line
	7200 4650 7200 3150
Wire Wire Line
	7100 2650 7100 5050
Wire Wire Line
	7400 2650 7400 2750
Connection ~ 7100 2650
Connection ~ 7200 3150
Connection ~ 3750 4100
Wire Wire Line
	2950 4500 7100 4500
Connection ~ 3950 4300
Connection ~ 3850 4200
Wire Wire Line
	6950 2650 7400 2650
Wire Wire Line
	7400 3150 6950 3150
Wire Wire Line
	7400 3050 7400 3150
Wire Wire Line
	2950 4800 2950 4500
Wire Wire Line
	2750 4200 2750 4800
Wire Wire Line
	2650 3150 2650 4800
Wire Wire Line
	2550 4800 2550 4650
Wire Wire Line
	2550 4650 7200 4650
Connection ~ 5000 4650
Wire Wire Line
	5000 4650 5000 4850
Wire Wire Line
	2650 3150 4250 3150
Wire Wire Line
	3050 4800 3050 4100
Wire Wire Line
	2850 4300 2850 4800
Wire Wire Line
	2450 4400 2450 4800
Wire Wire Line
	4250 2950 4050 2950
Wire Wire Line
	4050 2950 4050 3650
Wire Wire Line
	4050 3650 6100 3650
Wire Wire Line
	6100 3650 6100 4000
Wire Wire Line
	6100 4000 5950 4000
Wire Wire Line
	5950 4100 7100 4100
Connection ~ 7100 4100
Wire Wire Line
	3350 4400 3350 5300
Wire Wire Line
	3350 4400 2450 4400
Connection ~ 7100 4500
$Comp
L NRF24L01+ U3
U 1 1 5839C750
P 5950 4300
F 0 "U3" H 6380 4450 60  0000 C CNN
F 1 "NRF24L01+" H 6390 3850 60  0000 C CNN
F 2 "Custom:NRF24L01+_SMT" H 5950 4310 60  0001 C CNN
F 3 "" H 5950 4310 60  0000 C CNN
	1    5950 4300
	-1   0    0    1   
$EndComp
Wire Wire Line
	5950 4200 7200 4200
Connection ~ 7200 4200
Wire Wire Line
	5950 4300 7100 4300
Connection ~ 7100 4300
$Comp
L WS2812B U2
U 1 1 5839C986
P 5950 5050
F 0 "U2" H 6390 5170 60  0000 C CNN
F 1 "WS2812B" H 6390 4720 60  0000 C CNN
F 2 "Custom:WS2812B_SMT" H 6270 4980 60  0001 C CNN
F 3 "" H 6270 4980 60  0000 C CNN
	1    5950 5050
	-1   0    0    1   
$EndComp
Wire Wire Line
	5050 5050 4150 5050
Wire Wire Line
	4150 5050 4150 3050
Wire Wire Line
	6150 4850 6150 5300
Wire Wire Line
	6150 5300 3350 5300
$EndSCHEMATC
