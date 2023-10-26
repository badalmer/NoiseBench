![plotting machine.jpg](https://github.com/badalmer/NoiseBench/blob/master/plotting%20machine.jpg)

# Painting-Plotter
A plotting machine designed to replicate vector paths using [LightBurn](https://lightburnsoftware.com/). A CNC system loosely based on the [ACRO system](https://openbuilds.com/builds/openbuilds-acro-system.5416/) from OpenBuilds. The machine is 
powered by an Arduino with a GRBL Shield.

# GRBL Settings
- $$
- $0=10
- $1=255
- $2=0
- $3=6
- $4=0
- $5=0
- $6=0
- $10=3
- $11=0.020
- $12=0.020
- $13=0
- $20=0
- $21=0
- $22=1
- $23=7
- $24=100.000
- $25=3000.000
- $26=5
- $27=2.000
- $30=1000
- $31=0
- $32=0
- $100=160.000
- $101=160.000
- $102=160.000
- $110=10000.000
- $111=10000.000
- $112=3000.000
- $120=500.000
- $121=500.000
- $122=500.000
- $130=845.000
- $131=1100.000
- $132=25.000

# Parts List

### FRAME
|	No.	|	Component	|	BRAND	|	ASIN	|	Sourced	|	Source Location	|	Manufactured	|	Price	|	TOTAL	|	Notes	|
|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	---:	|	---:	|	:---	|
|	3	|	2040 Aluminium Rail [40"]	|	NULL	|	NULL	|	FazTek	|	Montreal, QC	|	Newnan, GA	|	$11.27	|	$33.81	|		|
|	2	|	2040 Aluminium Rail [50"]	|	NULL	|	NULL	|	FazTek	|	Montreal, QC	|	Newnan, GA	|	$13.43	|	$26.86	|		|
|	6	|	Black Acrylic Gantry Cart & Plates	|	Plaskolite South LLC	|	NULL	|	Plastic World	|	Toronto, ON	|	Olive Branch, MS	|	$11.00	|	$11.00	|	Designed and Lasercut by me	|
|	8	|	T Nut Drop in Nut for Aluminum Extrusion [M5]	|	Boeray	|	BR-TN-0015	|	Amazon	|	Ningbo, Zhejiang	|	Ningbo, Zhejiang	|	$13.52	|	$13.52	|	50 Pack	|
|	16	|	M3 10 mm Plain Metric Socket Cap Screw	|	Everbuilt	|	NULL	|	Home Depot	|	Toronto, ON	|	Austin, TX	|	$0.82	|	$4.10	|	3 Pack	|
|	24	|	M5 Screws [12mm]	|	RELIABLE	|	PPMZM512MR	|	RONA	|	Montreal, ON	|	Longueil, QC	|	$3.29	|	$13.16	|	7 Pack	|
|	1	|	2GT-6 Open Ended PU Timing Belt [6mm]	|	Walfront	|	B0748CNTFR	|	Amazon	|	Lewes, DE	|	Lewes, DE	|	$20.79	|	$20.79	|		|
|	1	|	Multi-Purpose Ties 7.5"	|	DURAMAX	|	NULL	|	Dollerama	|	Montreal, ON	|	Shenzhen	|	$1.25	|		|	40 Pack	|
|	1	|	Upgraded Piston Airbrush Compressor 	|	‎TIMBERTECH	|	‎ABPST08	|	Amazon	|	Shenzhen	|	Shenzhen	|	$166.94	|	$166.94	|		|
|	1	|	Cube 3 3D Printer	|	3D SYSTEMS	|	391100	|	E-Waste	|	NULL	|	Rock Hill, SC	|		|		|		|
|	1	|	1.75mm PLA 3D Printer Filament [black]	|	AMZ3D	|	B01BZ5ND8O	|	Amazon	|	Shenzhen	|	Shenzhen	|	$29.99	|	$29.99	|		|
|		|	Laser-Cutting [service]	|	NULL	|	NULL	|	NULL	|	NULL	|	NULL	|		|		|	Cut by Concordia FABLAB	|

### MOTORS
|	No.	|	Component	|	BRAND	|	ASIN	|	Sourced	|	Source Location	|	Manufactured	|	Price	|	TOTAL	|	Notes	|
|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	---:	|	---:	|	:---	|
|	3	|	Stepper Motor - NEMA-17	|	ETC	|	XY42STH34-0354A	|	Adafruit	|	New York, NY	|	Foshan, Guangdong	|	$14.00	|	$42.00	|		|
|	1	|	Stepper Motor - NEMA-17	|	STEPPERONLINE	|	17HS08-1004S	|	Stepper Online	|	Jiangning, Nanjing City	|	Jiangning, Nanjing City	|	$8.36	|	$8.36	|		|
|	4	|	GT2 Timing Pulley [20 Teeth Bore 5mm]	|	Walfront	|	TE407	|	Amazon	|	Mascouche, QC	|	Lewes, DE	|	$1.75	|	$7.00	|		|
|	4	|	2GT Aluminum Timing Belt Idler Pulley	|	Saiper	|	B07P9M6BRC	|	Amazon	|	Asia	|	Navi Mumbai, Maharashtra	|	$11.46	|	$11.46	|	5 Pack	|

### GANTRY CART
|	No.	|	Component	|	BRAND	|	ASIN	|	Sourced	|	Source Location	|	Manufactured	|	Price	|	TOTAL	|	Notes	|
|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	---:	|	---:	|	:---	|
|	12	|	Delrin Mini Wheels	|	‎Richer-R	|	Ryox42zicbr-02	|	OpenBuilds	|	Zephyrhills, Florida	|	Unknown	|	$14.99		$29.98	|	10 Pack	|
|	8	|	Eccentric Spacer V Wheel [5mm]	|	ZTSHBK	|	B091TVR1PS	|	Amazon	|	Shanghang	|	Shanghang	|	16.68		16.68	|	10 Pack	|
|	8	|	Acrylic Spacers	|	NylonSpacer	|	819368020717	|	OpenBuilds	|	Zephyrhills, Florida	|	Unknown	|	$2.09		$2.09	|	10 Pack	|
|	16	|	M5 Screw (30mm)	|	RELIABLE	|	PPMZM530MR	|	RONA	|	Montreal, QC	|	Longueuil, QC	|	$3.29		$9.87	|	5 Pack	|
|	16	|	Nylon Insert Hex Stop Nut	|	PRECISION	|	700-005	|	RONA	|	Montreal, QC	|	Longueuil, QC	|	$21.59		$21.59	|	100 Pack	|
|	16	|	Washers	|	PAULIN	|	730-005	|	Home Depot	|	Montreal, QC	|	Milton, ON	|	$0.11		$1.76	|		|

### CONTROLLER
|	No.	|	Component	|	BRAND	|	ASIN	|	Sourced	|	Source Location	|	Manufactured	|	Price	|	TOTAL	|	Notes	|
|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	---:	|	---:	|	:---	|
|	1	|	Arduino Uno R3 Microcontroller	|	‎Arduino	|	‎B00PUOVSYS	|	Adafruit	|	New York, NY	|	Scarmagno, Italy	|	$22.50		$22.50	|		|
|	1	|	GRBL CNC Shield Expansion Board	|	Longruner	|	LK75	|	Amazon	|	Shenzhen	|	Shenzhen	|	$29.29		$29.29	|		|
|	1	|	4 Pin RGB LED Strip Extension Cable	|	VIPMOON	|	B06Y47R8W2	|	Amazon	|	Shanghai, Shanghai	|	Shenzhen	|	$13.99		$13.99	|	10 Feet	|
|	1	|	12v Computer fan	|	NULL	|	NULL	|	E-Waste	|	NULL	|	NULL	|				|	Recycled	|
|	1	|	1 Channel Relay	|	Walfront	|	t4bm61nz5p-02	|	Amazon	|	Mascouche, QC	|	Lewes, DE	|	$8.89		$8.89	|		|

### PLOTTER HEAD
|	No.	|	Component	|	BRAND	|	ASIN	|	Sourced	|	Source Location	|	Manufactured	|	Price	|	TOTAL	|	Notes	|
|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	---:	|	---:	|	:---	|
|	1	|	3D printed mount	|	NULL	|	NULL	|	NULL	|	NULL	|	NULL	|				|	3D Printed by Me	|
|	2	|	Springs	|	NULL	|	NULL	|	E-Waste	|	NULL	|	NULL	|				|	Recycled	|

### AIRBRUSH HEAD
|	No.	|	Component	|	BRAND	|	ASIN	|	Sourced	|	Source Location	|	Manufactured	|	Price	|	TOTAL	|	Notes	|
|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	:---	|	---:	|	---:	|	:---	|
|	1	|	3D printed mount	|	NULL	|	NULL	|	NULL	|	NULL	|	NULL	|				|	3D Printed by Me	|
|	2	|	Pneumatic Air Straight Fitting Push [5mm]	|	JIUWU	|	YT024	|	Amazon	|	Shenzhen	|	Shenzhen	|	$7.99		$7.99	|	5 Pack	|
|	1	|	plastic tubbing	|	SIQUK	|	SK-18-152	|	Amazon	|	Shenzhen	|	Shenzhen	|	$15.99		$15.99	|	5 Feet	|
