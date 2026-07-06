# MODule
Designed as a drop-in, competition ready coaxial Swerve Module for FIRST Tech Challenge.

<img width="1394" height="920" alt="image" src="https://github.com/user-attachments/assets/298ae1ad-0cd4-4f45-9204-d623306cf457" />



# DISCLAIMER: MOST OF THIS SWERVE MODULE IS STILL UNDER DEVELOPMENT. THIS STILL NEEDS TO BE TESTED AND ITERATED UPON, SO IF YOU BUILD IT BUILD IT AT YOUR OWN RISK


if your interested, you should check out my **[Build Journal](JOURNAL.md)** and **[Onshape Link :)](https://cad.onshape.com/documents/c73424119075b04fe773cc9a/w/dba58bb3bda5d97556e64109/e/f671ee2d5444472f512f4386?renderMode=0&uiState=6a493abc58e420f9881091d0)**


# Context:
- This is FTC Alpine Robotics' third (and most likely final) yeear in First Tech Challenge. As an improvement, we decided to work on omni-directional "swerve drive" for our 2026-2027 year, meaning it is able to move in more directions than just forward or back. we chose this as it allows for higher movability and traction, making us a more competitive robot on the field.

# What Does this Do?
Unlike omni-directional mecanum wheels (which rely on passive rollers and vectoring to be able to move in multiple directions), which is what most FTC teams use due to simplicity. Due to mecanum wheels rely on rollers instead of true steering, they lose efficiency when moving sideways or while rotating, especially under load, and we wanted to change that. We built a swerve module, where each wheel is independently driven and steered. this allows for smoother movement, more traction (since no passive rollers), and an overall faster robot.

# The Encoder
Unlike many other FTC Swerve modules, this features an absolute encder, meaning it provides an immediate absolute wheel angle at startup, eliminating the need for homing or zeroing and will prevent excess drift, making sure sure wheel headings are accurate.

# Technical Specs at a Glance:
- Modern Robotics 5000 series Drive motor (5800 rpm) off a 6.74:1 reduction for a final wheel speed of ~860 RPM

- Free Speed of 8.1 Feet/sec

- SWYFT Robotics Torque servo steering off a 2.818:1 reduction

- usage of printed PA-CF helical and herringbone gears for low backlash and higher strength than straignt-cut printed gears (force spread across multiple teeth vs one, increases strength as force is dispersed)

- easy to repair and maintain (wheel off in 2 screws, pod off in 8 screws)

# BOM: Parts
**This is for all the parts one would need to make a SINGLE Swerve Module**
|Part                                                 |Description                                                                   |Link                                                                                           |Quantity|Cost Per Unit (USD)|# Units Ordered|Total Cost|
|-----------------------------------------------------|------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|--------|-------------------|---------------|----------|
|M4 * 14mm Countersunk Screw                          |                                                                              |https://www.mcmaster.com/91294A193/                                                            |4       |7.27               |1              |7.27      |
|M4& 8mm Socket Head Cap Screw                        |                                                                              |https://www.mcmaster.com/91290A140/                                                            |6       |13.24              |1              |13.24     |
|M4 * 12mm Socket Head Cap Screw                      |                                                                              |https://www.mcmaster.com/91290A148/                                                            |6       |12.3               |1              |12.3      |
|M4 * 35mm Socket Head Cap Screw                      |                                                                              |https://www.mcmaster.com/91290A173/                                                            |4       |3.1                |1              |3.1       |
|M4 * 25mm Socket Head Cap Screw                      |                                                                              |https://www.mcmaster.com/91290A176/                                                            |6       |10.41              |1              |10.41     |
|M4 * 5mm Socket Head Cap Screw                       |                                                                              |https://www.mcmaster.com/91290A138/                                                            |2       |19.63              |1              |19.63     |
|M4 * 20mm Socket Head Cap Screw                      |                                                                              |https://www.mcmaster.com/91290A168/                                                            |2       |14.47              |1              |14.47     |
|M4 * 8mm Countersunk Screw                           |                                                                              |https://www.mcmaster.com/91294A188/                                                            |4       |6.25               |1              |6.25      |
|M4 * 8mm Socket Head Button Screw                    |                                                                              |https://www.mcmaster.com/91239A140/                                                            |4       |14.07              |1              |14.07     |
|M4 * 5mm Socket Head Button Screw                    |                                                                              |https://www.mcmaster.com/91239A136/                                                            |1       |4.81               |1              |4.81      |
|GoBilda 1516 Series REX standoff, 40mm               |                                                                              |https://www.gobilda.com/1516-series-8mm-rex-standoff-m4-x-0-7mm-threads-40mm-length-4-pack/    |1       |5.29               |1              |5.29      |
|GoBilda 2106 Series REX Shaft, 24mm L                |                                                                              |https://www.gobilda.com/8mm-rex-shaft-with-e-clip-stainless-steel-24mm-length/                 |1       |3.69               |1              |3.69      |
|GoBilda 1500 Series Plastic Spacer (8mm ID, 1mm L)   |                                                                              |https://www.gobilda.com/1500-series-plastic-spacer-8mm-id-x-10mm-od-1mm-thickness-12-pack/     |2       |2.69               |1              |2.69      |
|GoBilda 5000 Series 12V DC Motor, 1/8" D Shaft       |                                                                              |https://www.gobilda.com/5000-series-12vdc-motor/                                               |1       |19.99              |1              |19.99     |
|GoBilda 1106 Series Square Beam (2 Hole, 16mm L)     |                                                                              |https://www.gobilda.com/1106-series-square-beam-2-hole-16mm-length/                            |4       |2.59               |1              |2.59      |
|GoBilda 1502 Series 4mm ID Spacer (6mm OD, 16mm L)   |                                                                              |https://www.gobilda.com/1502-series-4mm-id-spacer-6mm-od-16mm-length-4-pack/                   |6       |2.69               |2              |5.38      |
|Gobilda 1611 Series Flanged Bearing (8mm ID, 14mm OD)|                                                                              |https://www.gobilda.com/1611-series-flanged-ball-bearing-8mm-id-x-14mm-od-5mm-thickness-2-pack/|3       |3.99               |2              |7.98      |
|Gobilda 2mm Pitch GT2 Pinion Timing Pulley           |                                                                              |https://www.gobilda.com/2mm-pitch-gt2-pinion-timing-pulley-1-8-bore-20-tooth/                  |1       |7.99               |1              |7.99      |
|Rev 8mm ID * 12mm OD *3.5mm WD Flanged Bearing       |                                                                              |https://www.revrobotics.com/rev-49-1559-pk10/                                                  |4       |18.5               |1              |18.5      |
|SensOrange Encoder                                   |                                                                              |https://sensorangerobotics.com/product/encoder/                                                |1       |27.67              |1              |27.67     |
|SWYFT Robotics Speed Servo (Continous Rotation)      |                                                                              |https://swyftrobotics.com/products/swyft-servos?variant=51735705321766                         |1       |49.99              |1              |49.99     |
|122T GT2 2mm Timing Belt, 6mm WD                     |                                                                              |https://shop.sdp-si.com/a-6r51m122060.html                                                     |1       |8.5                |1              |8.5       |
|WCP-1870 X Contact Bearing (1.75"ID, 2.125" OD)      |                                                                              |https://wcproducts.com/collections/cnc-hardware/products/specialty-bearings                    |1       |55                 |1              |55        |
|6" * 6" Aluminum Sheet, T6-6061, 1/8" Thick          |For Top Plates and Encoder Plates                                             |https://www.mcmaster.com/89015K235/                                                            |1       |10.96              |1              |10.96     |
|8" * 8" Aluminum Sheet, T6-6061, 1/4" Thick          |For Bottom Plate                                                              |https://www.mcmaster.com/9246K11/                                                              |1       |31.3               |1              |31.3      |
|Fiberon PA6-CF20                                     |3D Print used for almost all pulleys and gears, swerve forks, and some spacers|https://shop.polymaker.com/products/fiberon-pa6-cf20                                           |1       |36                 |1              |36        |
|Bambu Lab TPU 95A                                    |TPU for swerve tread                                                          |https://us.store.bambulab.com/products/tpu-95a-hf                                              |1       |33.59              |1              |33.59     |
|TOTAL COST                                           |                                                                              |                                                                                               |        |                   |               |**432.66**|
|                                                     |                                                                              |                                                                                               |        |                   |               |          |
|                                                     |                                                                              |                                                                                               |        |                   |               |          |
|                                                     |                                                                              |                                                                                               |        |                   |               |          |
|                                                     |                                                                              |                                                                                               |        |                   |               |          |

# BOM: Custom Manufactured Parts
**This is for all the custom parts that would need to be 3D-Printed or Milled using items bought in the Parts BOM**
|Part                       |Description                                   |Material        |Qty|CAD name                   |
|---------------------------|----------------------------------------------|----------------|---|---------------------------|
|Hub Bevel Gear             |Hub Gear for Wheel                            |PA6 CF20        |1  |Spiral Bevel 0.8M 52T 75deg|
|Pinion Bevel gear          |Bevel gear that meshes with Hub Gear          |PA6 CF20        |1  |Spiral Bevel 0.8M 18T 15deg|
|Main Pod Steering Gear     |Hub gear for steering                         |PA6 CF20        |1  |Steering Gear              |
|Small Coaxial Gear         |smaller coaxial reciever gear                 |PA6 CF20        |1  |Coaxial Reciever Gear      |
|Large Coaxial Gear w/Pulley|pulley connection and coaxial transmitter gear|PA6 CF20        |1  |Coaxial Transmit Gear      |
|Motor Spacer               |Spacer for Motor                              |PA6 CF20        |1  |Motor Spacer               |
|Fork A                     |Fork with hole for Bevel Gear                 |PA6 CF20        |1  |ForkA                      |
|Fork B                     |Blank Fork                                    |PA6 CF20        |1  |ForkB                      |
|Tread                      |Wheel Tread                                   |95A TPU         |1  |Tread                      |
|Encoder Standoff           |Standoff for encoder Plate                    |PA6 CF20        |2  |PStandoff                  |
|Encoder Plate              |                                              |6061-T6 Aluminum|1  |EncoderL/R (Both are Same) |
|Top Plate                  |                                              |6061-T6 Aluminum|1  |Top_L/R (Both are Same)    |
|Base Plate                 |                                              |6061-T6 Aluminum|1  |Base_L/R (Both are Same)   |

# BOM: Procurement
**This is for funding, basically what all I need funding for. this is taken off the Parts BOM, and whatever parts I am supplying are removed.**
|Part                                              |Description|Link                                                                                       |Quantity|Cost Per Unit (USD)|# Units Ordered|Total Cost|
|--------------------------------------------------|-----------|-------------------------------------------------------------------------------------------|--------|-------------------|---------------|----------|
|M4 * 14mm Countersunk Screw                       |           |https://www.mcmaster.com/91294A193/                                                        |4       |7.27               |1              |7.27      |
|M4 * 12mm Socket Head Cap Screw                   |           |https://www.mcmaster.com/91290A148/                                                        |6       |12.3               |1              |12.3      |
|M4 * 35mm Socket Head Cap Screw                   |           |https://www.mcmaster.com/91290A173/                                                        |4       |3.1                |1              |3.1       |
|M4 * 25mm Socket Head Cap Screw                   |           |https://www.mcmaster.com/91290A176/                                                        |6       |10.41              |1              |10.41     |
|M4 * 5mm Socket Head Cap Screw                    |           |https://www.mcmaster.com/91290A138/                                                        |2       |19.63              |1              |19.63     |
|M4 * 8mm Countersunk Screw                        |           |https://www.mcmaster.com/91294A188/                                                        |4       |6.25               |1              |6.25      |
|M4 * 8mm Socket Head Button Screw                 |           |https://www.mcmaster.com/91239A140/                                                        |4       |14.07              |1              |14.07     |
|M4 * 5mm Socket Head Button Screw                 |           |https://www.mcmaster.com/91239A136/                                                        |1       |4.81               |1              |4.81      |
|GoBilda 1516 Series REX standoff, 40mm            |           |https://www.gobilda.com/1516-series-8mm-rex-standoff-m4-x-0-7mm-threads-40mm-length-4-pack/|1       |5.29               |1              |5.29      |
|GoBilda 2106 Series REX Shaft, 24mm L             |           |https://www.gobilda.com/8mm-rex-shaft-with-e-clip-stainless-steel-24mm-length/             |1       |3.69               |1              |3.69      |
|GoBilda 1500 Series Plastic Spacer (8mm ID, 1mm L)|           |https://www.gobilda.com/1500-series-plastic-spacer-8mm-id-x-10mm-od-1mm-thickness-12-pack/ |2       |2.69               |1              |2.69      |
|GoBilda 1502 Series 4mm ID Spacer (6mm OD, 16mm L)|           |https://www.gobilda.com/1502-series-4mm-id-spacer-6mm-od-16mm-length-4-pack/               |6       |2.69               |2              |5.38      |
|Gobilda 2mm Pitch GT2 Pinion Timing Pulley        |           |https://www.gobilda.com/2mm-pitch-gt2-pinion-timing-pulley-1-8-bore-20-tooth/              |1       |7.99               |1              |7.99      |
|Rev 8mm ID * 12mm OD *3.5mm WD Flanged Bearing    |           |https://www.revrobotics.com/rev-49-1559-pk10/                                              |4       |18.5               |1              |18.5      |
|122T GT2 2mm Timing Belt, 6mm WD                  |           |https://shop.sdp-si.com/a-6r51m122060.html                                                 |1       |8.5                |1              |8.5       |
|WCP-1870 X Contact Bearing (1.75"ID, 2.125" OD)   |           |https://wcproducts.com/collections/cnc-hardware/products/specialty-bearings                |1       |55                 |1              |55        |
|TOTAL COST                                        |           |                                                                                           |        |                   |               |**184.88**|

