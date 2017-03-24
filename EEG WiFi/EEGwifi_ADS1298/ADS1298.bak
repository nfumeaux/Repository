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
LIBS:nnclib
LIBS:EEGwifi_ADS1298-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 2 2
Title "ADC_ADS1298_Main"
Date "18 jan 2017"
Rev "0.01"
Comp "NCP"
Comment1 "Marcio Moraes"
Comment2 "NNC"
Comment3 ""
Comment4 ""
$EndDescr
Text Notes 3100 750  0    60   ~ 0
Surface mount DRL Could work but 1 inch solution is more modular
Text Notes 6900 750  0    60   ~ 0
clksel selected on main board - Just in case chips are cascaded
Text Label 8350 2600 2    60   ~ 0
GPIO4
Text Label 8350 2800 2    60   ~ 0
GPIO3
Text Label 8350 3000 2    60   ~ 0
GPIO2
Text Notes 1700 1050 0    60   ~ 0
Most of the resistor and capacitor values;\n are from the ads1298 datasheet.
Text Notes 8950 2850 0    60   ~ 0
GPIO pins must be  "driven"; if not used.\n
Text Notes 6400 600  0    60   ~ 0
Clock signals for coppies are generated inside master chip
$Comp
L ads1298 U1
U 1 1 587FA281
P 5850 3600
F 0 "U1" H 5850 3500 50  0000 C CNN
F 1 "ADS1298" H 5850 3700 50  0000 C CNN
F 2 "Housings_QFP:TQFP-64_10x10mm_Pitch0.5mm" H 5850 3600 60  0001 C CNN
F 3 "" H 5850 3600 60  0001 C CNN
	1    5850 3600
	1    0    0    -1  
$EndComp
Text Notes 2950 2400 2    60   ~ 0
Patent Protection Resistors\n
NoConn ~ 6850 5800
NoConn ~ 6450 5800
Text HLabel 8050 2200 2    60   Input ~ 0
DVDD
Text HLabel 8050 2400 2    60   Input ~ 0
~DRDY
Text HLabel 8850 2600 2    60   Input ~ 0
DGND
Text HLabel 8050 3200 2    60   Output ~ 0
SPI_MISO
Text HLabel 8050 3800 2    60   Input ~ 0
SPI_SCLK
Text HLabel 8050 4000 2    60   Input ~ 0
~SPI_~CS
Text HLabel 8050 4200 2    60   Input ~ 0
START
Text HLabel 8050 4400 2    60   Input ~ 0
CLK
Text HLabel 8050 5000 2    60   Input ~ 0
SPI_MOSI
Text HLabel 1150 6600 0    60   Input ~ 0
AGND
Text HLabel 3850 2200 0    60   Input ~ 0
IN8N
Text HLabel 3850 2400 0    60   Input ~ 0
IN8P
Text HLabel 3850 2600 0    60   Input ~ 0
IN7N
Text HLabel 3850 2800 0    60   Input ~ 0
IN7P
Text HLabel 3850 3000 0    60   Input ~ 0
IN6N
Text HLabel 3850 3200 0    60   Input ~ 0
IN6P
Text HLabel 3850 3400 0    60   Input ~ 0
IN5N
Text HLabel 3850 3600 0    60   Input ~ 0
IN5P
Text HLabel 3850 3800 0    60   Input ~ 0
IN4N
Text HLabel 3850 4000 0    60   Input ~ 0
IN4P
Text HLabel 3850 4400 0    60   Input ~ 0
IN3P
Text HLabel 3850 4200 0    60   Input ~ 0
IN3N
Text HLabel 3850 4800 0    60   Input ~ 0
IN2P
Text HLabel 3850 4600 0    60   Input ~ 0
IN2N
Text HLabel 3850 5200 0    60   Input ~ 0
IN1P
Text HLabel 3850 5000 0    60   Input ~ 0
IN1N
Text HLabel 4650 1600 1    60   Output ~ 0
RLDOUT
Text HLabel 5050 1600 1    60   Input ~ 0
RLDINV
Text HLabel 5250 1600 1    60   Input ~ 0
RLDREF
Text HLabel 7950 1200 2    60   Input ~ 0
CLKSEL
Text HLabel 7950 1500 2    60   Input ~ 0
DGND
Text HLabel 8050 3600 2    60   Input ~ 0
DGND
Text HLabel 8400 4700 2    60   Input ~ 0
DVDD
Text HLabel 8600 5200 2    60   Input ~ 0
DGND
Text HLabel 1150 5900 0    60   Input ~ 0
AVDD
Text HLabel 5300 900  0    60   Input ~ 0
AVDD
Text Label 8350 3400 2    60   ~ 0
GPIO1
Text Notes 9000 2950 0    60   ~ 0
GPIO If not used short to DGND p30.
Text HLabel 4850 1550 1    60   Input ~ 0
RLDIN
Text Notes 3100 3350 2    60   ~ 0
LOOK AT THE AVSS1 and AVSS issue \n.... not grounded to AGND ... \nhave to make that decision before continuing\n\nVOTE TO TAKE AVSS out of the picture ... simplify
Text HLabel 2500 4450 2    60   Output ~ 0
RLDOUT
Text HLabel 2500 4150 2    60   Input ~ 0
RLDINV
Text HLabel 2150 4700 0    60   Input ~ 0
RLDREF
Text HLabel 2150 4850 0    60   Input ~ 0
RLDIN
$Comp
L R R1
U 1 1 58D2CAD1
P 1700 4300
F 0 "R1" V 1780 4300 50  0000 C CNN
F 1 "1M" V 1700 4300 50  0000 C CNN
F 2 "" V 1630 4300 50  0000 C CNN
F 3 "" H 1700 4300 50  0000 C CNN
	1    1700 4300
	1    0    0    -1  
$EndComp
$Comp
L C C1
U 1 1 58D2CCDB
P 1350 4300
F 0 "C1" H 1375 4400 50  0000 L CNN
F 1 "1nf" H 1375 4200 50  0000 L CNN
F 2 "" H 1388 4150 50  0000 C CNN
F 3 "" H 1350 4300 50  0000 C CNN
	1    1350 4300
	1    0    0    -1  
$EndComp
Text HLabel 4750 6400 0    60   Input ~ 0
AVSS
Text HLabel 10100 1300 2    60   Input ~ 0
CLKSEL
Text Notes 9250 1800 0    60   ~ 0
This pin should be set to 1 in \norder to use internal CLK. If set \nto zero, external CLK must be provided.
Text HLabel 9900 1300 0    60   Input ~ 0
DVDD
Text Notes 8350 4500 0    60   ~ 0
Mater CLK input (not used if CLKSEL is set to 1)\nIn that case it is an output for daisy conections
$Comp
L C C18
U 1 1 58D484F1
P 6400 7100
F 0 "C18" H 6425 7200 50  0000 L CNN
F 1 "C" H 6425 7000 50  0000 L CNN
F 2 "" H 6438 6950 50  0000 C CNN
F 3 "" H 6400 7100 50  0000 C CNN
	1    6400 7100
	1    0    0    -1  
$EndComp
$Comp
L C C14
U 1 1 58D485DE
P 6100 7550
F 0 "C14" H 6125 7650 50  0000 L CNN
F 1 "C" H 6125 7450 50  0000 L CNN
F 2 "" H 6138 7400 50  0000 C CNN
F 3 "" H 6100 7550 50  0000 C CNN
	1    6100 7550
	1    0    0    -1  
$EndComp
$Comp
L R R2
U 1 1 58D4865B
P 5850 7550
F 0 "R2" V 5930 7550 50  0000 C CNN
F 1 "1M" V 5850 7550 50  0000 C CNN
F 2 "" V 5780 7550 50  0000 C CNN
F 3 "" H 5850 7550 50  0000 C CNN
	1    5850 7550
	1    0    0    -1  
$EndComp
$Comp
L C C13
U 1 1 58D4872F
P 6100 7100
F 0 "C13" H 6125 7200 50  0000 L CNN
F 1 "C" H 6125 7000 50  0000 L CNN
F 2 "" H 6138 6950 50  0000 C CNN
F 3 "" H 6100 7100 50  0000 C CNN
	1    6100 7100
	1    0    0    -1  
$EndComp
$Comp
L C C11
U 1 1 58D48763
P 5850 7100
F 0 "C11" H 5875 7200 50  0000 L CNN
F 1 "C" H 5875 7000 50  0000 L CNN
F 2 "" H 5888 6950 50  0000 C CNN
F 3 "" H 5850 7100 50  0000 C CNN
	1    5850 7100
	1    0    0    -1  
$EndComp
$Comp
L C C9
U 1 1 58D48769
P 5550 7100
F 0 "C9" H 5575 7200 50  0000 L CNN
F 1 "C" H 5575 7000 50  0000 L CNN
F 2 "" H 5588 6950 50  0000 C CNN
F 3 "" H 5550 7100 50  0000 C CNN
	1    5550 7100
	1    0    0    -1  
$EndComp
$Comp
L C C19
U 1 1 58D487D9
P 6650 6100
F 0 "C19" H 6675 6200 50  0000 L CNN
F 1 "22uF" H 6675 6000 50  0000 L CNN
F 2 "" H 6688 5950 50  0000 C CNN
F 3 "" H 6650 6100 50  0000 C CNN
	1    6650 6100
	1    0    0    -1  
$EndComp
$Comp
L C C20
U 1 1 58D487DF
P 7050 6100
F 0 "C20" H 7075 6200 50  0000 L CNN
F 1 "1uF" H 7075 6000 50  0000 L CNN
F 2 "" H 7088 5950 50  0000 C CNN
F 3 "" H 7050 6100 50  0000 C CNN
	1    7050 6100
	1    0    0    -1  
$EndComp
$Comp
L C C12
U 1 1 58D487E5
P 5950 6100
F 0 "C12" H 5975 6200 50  0000 L CNN
F 1 "10uF" H 6000 6000 50  0000 L CNN
F 2 "" H 5988 5950 50  0000 C CNN
F 3 "" H 5950 6100 50  0000 C CNN
	1    5950 6100
	1    0    0    -1  
$EndComp
$Comp
L C C10
U 1 1 58D487EB
P 5750 6100
F 0 "C10" H 5775 6200 50  0000 L CNN
F 1 "0.1uF" H 5500 6000 50  0000 L CNN
F 2 "" H 5788 5950 50  0000 C CNN
F 3 "" H 5750 6100 50  0000 C CNN
	1    5750 6100
	1    0    0    -1  
$EndComp
$Comp
L C C16
U 1 1 58D49117
P 6250 6100
F 0 "C16" H 6275 6200 50  0000 L CNN
F 1 "1uF" H 6275 6000 50  0000 L CNN
F 2 "" H 6288 5950 50  0000 C CNN
F 3 "" H 6250 6100 50  0000 C CNN
	1    6250 6100
	1    0    0    -1  
$EndComp
Text HLabel 3700 5850 0    60   Input ~ 0
AVDD
$Comp
L C C4
U 1 1 58D4A1CC
P 1550 6250
F 0 "C4" H 1575 6350 50  0000 L CNN
F 1 "0.1uF" H 1575 6150 50  0000 L CNN
F 2 "" H 1588 6100 50  0000 C CNN
F 3 "" H 1550 6250 50  0000 C CNN
	1    1550 6250
	1    0    0    -1  
$EndComp
$Comp
L C C2
U 1 1 58D4A1D2
P 1350 6250
F 0 "C2" H 1375 6350 50  0000 L CNN
F 1 "1uF" H 1375 6150 50  0000 L CNN
F 2 "" H 1388 6100 50  0000 C CNN
F 3 "" H 1350 6250 50  0000 C CNN
	1    1350 6250
	1    0    0    -1  
$EndComp
$Comp
L C C5
U 1 1 58D4A504
P 1550 6950
F 0 "C5" H 1575 7050 50  0000 L CNN
F 1 "0.1uF" H 1575 6850 50  0000 L CNN
F 2 "" H 1588 6800 50  0000 C CNN
F 3 "" H 1550 6950 50  0000 C CNN
	1    1550 6950
	1    0    0    -1  
$EndComp
$Comp
L C C3
U 1 1 58D4A50A
P 1350 6950
F 0 "C3" H 1375 7050 50  0000 L CNN
F 1 "1uF" H 1375 6850 50  0000 L CNN
F 2 "" H 1388 6800 50  0000 C CNN
F 3 "" H 1350 6950 50  0000 C CNN
	1    1350 6950
	1    0    0    -1  
$EndComp
Text HLabel 1150 7300 0    60   Input ~ 0
AVSS
Wire Wire Line
	8050 2600 8850 2600
Connection ~ 8750 2800
Wire Wire Line
	8050 2800 8750 2800
Wire Wire Line
	6050 900  6050 1600
Connection ~ 8200 5200
Wire Wire Line
	8200 5200 8200 6000
Wire Wire Line
	8200 6000 7250 6000
Wire Wire Line
	7250 6000 7250 5800
Wire Wire Line
	7450 1500 7450 1600
Wire Wire Line
	7050 1500 7050 1600
Connection ~ 6650 6400
Connection ~ 7050 6400
Connection ~ 6250 6400
Connection ~ 6050 6400
Wire Wire Line
	8050 4600 8250 4600
Wire Wire Line
	8250 4600 8250 4800
Wire Wire Line
	8250 4800 8050 4800
Wire Wire Line
	6050 6400 6050 5800
Wire Wire Line
	5650 6400 5650 5800
Connection ~ 5650 6400
Wire Wire Line
	5450 900  5450 1600
Wire Wire Line
	8400 4700 8250 4700
Connection ~ 8250 4700
Wire Wire Line
	7050 1500 7950 1500
Connection ~ 7450 1500
Connection ~ 8750 2600
Wire Wire Line
	8050 5200 8600 5200
Wire Wire Line
	8750 3400 8050 3400
Wire Wire Line
	8750 2600 8750 3400
Wire Wire Line
	8050 3000 8750 3000
Connection ~ 8750 3000
Connection ~ 7450 6400
Wire Wire Line
	7450 6400 7450 5800
Connection ~ 7050 1500
Connection ~ 5450 900 
Connection ~ 6050 900 
Wire Wire Line
	6450 900  6450 1600
Connection ~ 6450 900 
Wire Wire Line
	4850 1550 4850 1600
Wire Wire Line
	5650 800  5650 1600
Wire Wire Line
	1350 4150 2500 4150
Connection ~ 1700 4150
Wire Wire Line
	1350 4450 2500 4450
Connection ~ 1700 4450
Connection ~ 1350 4450
Wire Wire Line
	6650 5800 6650 5950
Wire Wire Line
	6650 6400 6650 6250
Wire Wire Line
	7050 5800 7050 5950
Wire Wire Line
	7050 6400 7050 6250
Wire Wire Line
	6250 5800 6250 5950
Wire Wire Line
	6250 6400 6250 6250
Wire Wire Line
	5750 5950 5950 5950
Wire Wire Line
	5850 5950 5850 5800
Connection ~ 5850 5950
Wire Wire Line
	5750 6250 5950 6250
Wire Wire Line
	5850 6400 5850 6250
Connection ~ 5850 6400
Connection ~ 5850 6250
Wire Wire Line
	5050 5800 5050 6400
Connection ~ 5050 6400
Wire Wire Line
	4750 6400 7450 6400
Wire Wire Line
	1150 5900 1450 5900
Wire Wire Line
	1450 5900 1450 6000
Wire Wire Line
	1350 6000 1550 6000
Wire Wire Line
	1350 6000 1350 6100
Wire Wire Line
	1550 6000 1550 6100
Connection ~ 1450 6000
Wire Wire Line
	1350 6400 1350 6500
Wire Wire Line
	1350 6500 1550 6500
Wire Wire Line
	1550 6500 1550 6400
Wire Wire Line
	1450 6500 1450 6700
Wire Wire Line
	1450 6600 1150 6600
Connection ~ 1450 6500
Wire Wire Line
	1350 6700 1550 6700
Wire Wire Line
	1350 6700 1350 6800
Connection ~ 1450 6600
Wire Wire Line
	1550 6700 1550 6800
Connection ~ 1450 6700
Wire Wire Line
	1350 7100 1350 7200
Wire Wire Line
	1350 7200 1550 7200
Wire Wire Line
	1550 7200 1550 7100
Wire Wire Line
	1450 7200 1450 7300
Wire Wire Line
	1450 7300 1150 7300
Connection ~ 1450 7200
Text HLabel 2200 6600 0    60   Input ~ 0
DGND
Text HLabel 2200 5900 0    60   Input ~ 0
DVDD
$Comp
L C C7
U 1 1 58D4ACFA
P 2500 6250
F 0 "C7" H 2525 6350 50  0000 L CNN
F 1 "0.1uF" H 2525 6150 50  0000 L CNN
F 2 "" H 2538 6100 50  0000 C CNN
F 3 "" H 2500 6250 50  0000 C CNN
	1    2500 6250
	1    0    0    -1  
$EndComp
$Comp
L C C6
U 1 1 58D4AD00
P 2300 6250
F 0 "C6" H 2325 6350 50  0000 L CNN
F 1 "1uF" H 2325 6150 50  0000 L CNN
F 2 "" H 2338 6100 50  0000 C CNN
F 3 "" H 2300 6250 50  0000 C CNN
	1    2300 6250
	1    0    0    -1  
$EndComp
Wire Wire Line
	2300 6000 2500 6000
Wire Wire Line
	2300 6000 2300 6100
Wire Wire Line
	2500 6000 2500 6100
Connection ~ 2400 6000
Wire Wire Line
	2300 6400 2300 6500
Wire Wire Line
	2300 6500 2500 6500
Wire Wire Line
	2500 6500 2500 6400
Wire Wire Line
	2400 6500 2400 6600
Connection ~ 2400 6500
Wire Wire Line
	2200 5900 2400 5900
Wire Wire Line
	2400 5900 2400 6000
Wire Wire Line
	2400 6600 2200 6600
$Comp
L C C17
U 1 1 58D4B477
P 6350 1350
F 0 "C17" H 6375 1450 50  0000 L CNN
F 1 "0.1uF" H 6375 1250 50  0000 L CNN
F 2 "" H 6388 1200 50  0000 C CNN
F 3 "" H 6350 1350 50  0000 C CNN
	1    6350 1350
	1    0    0    -1  
$EndComp
$Comp
L C C15
U 1 1 58D4B47D
P 6150 1350
F 0 "C15" H 6175 1450 50  0000 L CNN
F 1 "1uF" H 6175 1250 50  0000 L CNN
F 2 "" H 6188 1200 50  0000 C CNN
F 3 "" H 6150 1350 50  0000 C CNN
	1    6150 1350
	1    0    0    -1  
$EndComp
Text HLabel 4300 800  0    60   Input ~ 0
AVSS
$Comp
L C C8
U 1 1 58D4B904
P 4450 1050
F 0 "C8" H 4475 1150 50  0000 L CNN
F 1 "100pf" H 4475 950 50  0000 L CNN
F 2 "" H 4488 900 50  0000 C CNN
F 3 "" H 4450 1050 50  0000 C CNN
	1    4450 1050
	1    0    0    -1  
$EndComp
Wire Wire Line
	4450 1600 4450 1200
Wire Wire Line
	4300 800  7250 800 
Wire Wire Line
	4450 800  4450 900 
Connection ~ 4450 800 
Wire Wire Line
	5850 800  5850 1600
Connection ~ 5650 800 
Wire Wire Line
	6250 800  6250 1150
Wire Wire Line
	6150 1150 6350 1150
Wire Wire Line
	6150 1150 6150 1200
Connection ~ 5850 800 
Wire Wire Line
	6350 1150 6350 1200
Connection ~ 6250 1150
Wire Wire Line
	6150 1500 6150 1550
Wire Wire Line
	6150 1550 6350 1550
Wire Wire Line
	6350 1550 6350 1500
Wire Wire Line
	6250 1550 6250 1600
Connection ~ 6250 1550
Wire Wire Line
	5300 900  6450 900 
Wire Wire Line
	6650 800  6650 1600
Connection ~ 6250 800 
Wire Wire Line
	7250 800  7250 1600
Connection ~ 6650 800 
Wire Wire Line
	6850 1600 6850 1200
Wire Wire Line
	6850 1200 7950 1200
Wire Notes Line
	9100 1200 9100 1900
Wire Notes Line
	9100 1900 11100 1900
Wire Notes Line
	11100 1900 11100 1200
Wire Notes Line
	11100 1200 9100 1200
Text Notes 1250 5800 0    60   ~ 0
POWER CAPACITORS
Wire Notes Line
	800  5700 800  7400
Wire Notes Line
	800  7400 2800 7400
Wire Notes Line
	2800 7400 2800 5700
Wire Notes Line
	2800 5700 800  5700
Text Notes 1350 4000 0    60   ~ 0
RLD circuit to feedback patient
Wire Notes Line
	1200 3900 2950 3900
Wire Notes Line
	2950 3900 2950 4950
Wire Notes Line
	2950 4950 1200 4950
Wire Notes Line
	1200 4950 1200 3900
Text HLabel 2300 7000 0    60   Input ~ 0
AGND
Text HLabel 2400 7000 2    60   Input ~ 0
DGND
Text Notes 1850 7350 0    60   ~ 0
At some point\nAGND and DGND\nshould be the same
Text Notes 8400 2450 0    60   ~ 0
Data ready (active low)
Text Notes 1300 4900 0    60   ~ 0
Rare use ?
Text HLabel 2600 4850 2    60   Input ~ 0
AGND
Text HLabel 4150 5950 0    60   Input ~ 0
VREFP
Wire Wire Line
	4150 5950 5850 5950
Text HLabel 2600 4700 2    60   Input ~ 0
VREFP
Wire Wire Line
	2150 4700 2600 4700
Text HLabel 4250 6200 0    60   Input ~ 0
TESTP_PACE_OUT1
Text HLabel 4250 6300 0    60   Input ~ 0
TESTN_PACE_OUT2
Wire Wire Line
	4250 6200 4450 6200
Wire Wire Line
	4250 6300 4650 6300
Wire Wire Line
	4450 6200 4450 5800
Wire Wire Line
	4650 6300 4650 5800
Wire Wire Line
	3700 5850 5450 5850
Wire Wire Line
	5450 5850 5450 5800
Wire Wire Line
	5250 5800 5250 5850
Connection ~ 5250 5850
Wire Wire Line
	4850 5800 4850 5850
Connection ~ 4850 5850
Text Notes 8400 3700 0    60   ~ 0
If Daisy chained, this pin is connected \nto Dout of the chained ads
$EndSCHEMATC
