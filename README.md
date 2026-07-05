# MODule
Drop-in, competition ready coaxial Swerve Module for FIRST Tech Challenge.

<img width="1394" height="920" alt="image" src="https://github.com/user-attachments/assets/298ae1ad-0cd4-4f45-9204-d623306cf457" />



# DISCLAIMER: MOST OF THIS SWERVE MODULE IS STILL UNDER DEVELOPMENT. THIS STILL NEEDS TO BE TESTED AND ITERATED UPON, SO IF YOU BUILD IT BUILD IT AT YOUR OWN RISK

if your interested, you should check out my **[Build Journal :)](JOURNAL.md)**


# Context:
- This is FTC Alpine Robotics' third (and most likely final) yeear in First Tech Challenge. As an improvement, we decided to work on omni-directional "swerve drive" for our 2026-2027 year, meaning it is able to move in more directions than just forward or back. we chose this as it allows for higher movability and traction, making us a more competitive robot on the field.

# What Does this Do?
Unlike omni-directional mecanum wheels (which rely on passive rollers and vectoring to be able to move in multiple directions), which is what most FTC teams use due to simplicity. Due to having rollers instead of proper steering, the robot ends up slower when turning or not foing perfectly forwards and backwards, and we wanted to change that. We built a swerve module, where each wheel is independently driven and steered. this allows for smoother movement, more traction (since no passive rollers), and an overall faster robot.


# Technical Specs at a Glance:
- Modern Robotics 5000 series Drive motor (5800 rpm) off a 6.7:1 (yes im not joking) reduction for a final wheel RPM of 860 RPM

- Free Speed of 8.1 Feet/sec

- SWYFT Robotics Torque servo steering off a 2.818:1 reduction

- usage of printed PA-CF helical and herringbone gears for low backlash and higher strength than straignt-cut printed gears

- easy to repair and maintain (wheel off in 2 screws, pod off in 8 screws)

# BOM
**LEFT MODULE**
Item,Quantity,Part number,Description,Name
1,1,,,Spiral Bevel 0.8M 52T 75deg
2,4,,"Hex socket countersunk head screw M4x0.7 x 15 Stainless Steel ",Hex socket countersunk head screw M4x0.7 x 15
3,1,,,WheelR
4,1,,,WheelL
5,1,,,Tread
6,1,,,Coaxial Reciever Gear
7,1,,,Coaxial Transmit Gear
8,1,1516-4008-XXXX,https://www.gobilda.com/m4-standoffs/#rex_8mm,1516 Series 8mm REX Standoff (Configurable)
9,6,,"Hex socket head cap screw M4x0.70 x 12 Stainless Steel ",Hex socket head cap screw M4x0.70 x 12
10,1,,,Spiral Bevel 0.8M 18T 15deg
11,1,1516-4008-XXXX,https://www.gobilda.com/m4-standoffs/#rex_8mm,1516 Series 8mm REX Standoff (Configurable)
12,1,,,BevelUp
13,1,,,BevelDn
14,7,,"Socket button head screw M4x0.7 x 6 Stainless Steel ",Socket button head screw M4x0.7 x 6
15,1,,,Steering Gear
16,1,,,Pod Base
17,1,,,ForkA
18,1,,,ForkB
19,6,,"Hex socket head cap screw M4x0.70 x 8 Stainless Steel ",Hex socket head cap screw M4x0.70 x 8
20,4,,"Hex socket head cap screw M4x0.70 x 35 x 20 Stainless Steel ",Hex socket head cap screw M4x0.70 x 35 x 20
21,1,2106-4008-0240,https://www.gobilda.com/2106-series-stainless-steel-rex-shaft-8mm-diameter-24mm-length/,"2106 Series Stainless Steel REX Shaft (8mm Diameter, 24mm Length)"
22,2,1500-0010-0008,https://www.gobilda.com/1500-series-plastic-spacer-8mm-id-x-10mm-od-1mm-thickness-12-pack/,"1500 Series Plastic Spacer (8mm ID x 10mm OD, 1mm Thickness) 1500-0010-0008"
23,1,,,WheelSpacer
24,2,,,TransferSpacer
25,1,,,Base_L
26,1,,,Encoder_L
27,1,,,Top_L
28,1,,,PStandoff
29,1,,,PStandoff
30,1,,,Bare Motor (without axle)
31,1,,,Motor Axle
32,1,,,"2mm Pitch GT2 Pinion Timing Pulley (1/8"" Bore, 20 Tooth) 3422-0125-0020"
33,1,,,"6mm GT2 belt, 122T"
34,1,N/A,SWYFT Servo (Speed),SWYFT Servo (Speed)
35,1,1908-0025-0032,https://www.gobilda.com/1908-series-servo-hub-25-tooth-spline-32mm-diameter/,Servo Pinion
36,1,,,JHA CATALOG SEAL_JHA 017.step
37,1,,,JHA CATALOG SEAL_JHA 017.step_1
38,1,,,JHA INNER CATALOG_JHA17003.step
39,1,,,JHA OUTER CATALOG_JHA17002.step
40,1,,,JHA SEPARATOR SAMPLE_JHA17 (25004004).step
41,1,,,JHA SIZE CATALOG BALL_JHA17.step
42,1,,,JHA SIZE CATALOG BALL_JHA17.step_1
43,1,,,JHA SIZE CATALOG BALL_JHA17.step_10
44,1,,,JHA SIZE CATALOG BALL_JHA17.step_11
45,1,,,JHA SIZE CATALOG BALL_JHA17.step_12
46,1,,,JHA SIZE CATALOG BALL_JHA17.step_13
47,1,,,JHA SIZE CATALOG BALL_JHA17.step_14
48,1,,,JHA SIZE CATALOG BALL_JHA17.step_15
49,1,,,JHA SIZE CATALOG BALL_JHA17.step_16
50,1,,,JHA SIZE CATALOG BALL_JHA17.step_17
51,1,,,JHA SIZE CATALOG BALL_JHA17.step_18
52,1,,,JHA SIZE CATALOG BALL_JHA17.step_19
53,1,,,JHA SIZE CATALOG BALL_JHA17.step_2
54,1,,,JHA SIZE CATALOG BALL_JHA17.step_20
55,1,,,JHA SIZE CATALOG BALL_JHA17.step_21
56,1,,,JHA SIZE CATALOG BALL_JHA17.step_22
57,1,,,JHA SIZE CATALOG BALL_JHA17.step_23
58,1,,,JHA SIZE CATALOG BALL_JHA17.step_24
59,1,,,JHA SIZE CATALOG BALL_JHA17.step_25
60,1,,,JHA SIZE CATALOG BALL_JHA17.step_26
61,1,,,JHA SIZE CATALOG BALL_JHA17.step_27
62,1,,,JHA SIZE CATALOG BALL_JHA17.step_28
63,1,,,JHA SIZE CATALOG BALL_JHA17.step_29
64,1,,,JHA SIZE CATALOG BALL_JHA17.step_3
65,1,,,JHA SIZE CATALOG BALL_JHA17.step_30
66,1,,,JHA SIZE CATALOG BALL_JHA17.step_31
67,1,,,JHA SIZE CATALOG BALL_JHA17.step_32
68,1,,,JHA SIZE CATALOG BALL_JHA17.step_4
69,1,,,JHA SIZE CATALOG BALL_JHA17.step_5
70,1,,,JHA SIZE CATALOG BALL_JHA17.step_6
71,1,,,JHA SIZE CATALOG BALL_JHA17.step_7
72,1,,,JHA SIZE CATALOG BALL_JHA17.step_8
73,1,,,JHA SIZE CATALOG BALL_JHA17.step_9
74,1,,,Bottom Piece
75,1,,,Middle
76,1,,,Top Cover
77,1,,,Composite part 1
78,1,,,Holder
79,1,,,Magnet
80,4,,,screw
81,4,1106-0002-0016,https://www.gobilda.com/1106-series-square-beam-2-hole-16mm-length/,"1106 Series Square Beam (2 Hole, 16mm Length) 1106-0002-0016"
82,1,,,Motor Spacer
83,6,1502-0006-0160,https://www.gobilda.com/1502-series-4mm-id-spacer-6mm-od-16mm-length-4-pack/,"1502 Series 4mm ID Spacer (6mm OD, 16mm Length) - 4 Pack 1502-0006-0160"
84,6,,"Hex socket head cap screw M4x0.70 x 25 Stainless Steel ",Hex socket head cap screw M4x0.70 x 25
85,2,,"Hex socket head cap screw M4x0.70 x 5 Stainless Steel ",Hex socket head cap screw M4x0.70 x 5
86,2,,"Hex socket head cap screw M4x0.70 x 20 Stainless Steel ",Hex socket head cap screw M4x0.70 x 20
87,4,,"Hex socket countersunk head screw M4x0.7 x 8 Stainless Steel ",Hex socket countersunk head screw M4x0.7 x 8
88,4,,"Socket button head screw M4x0.7 x 8 Stainless Steel ",Socket button head screw M4x0.7 x 8
89,1,,"Socket button head screw M4x0.7 x 5 Stainless Steel ",Socket button head screw M4x0.7 x 5
 
# Links:
If You're Interested in this, you should check out my

**Onshape Link:**
https://cad.onshape.com/documents/c73424119075b04fe773cc9a/w/dba58bb3bda5d97556e64109/e/f671ee2d5444472f512f4386?renderMode=0&uiState=6a493abc58e420f9881091d0


