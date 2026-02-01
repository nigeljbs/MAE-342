# Phase 1 – System Understanding and Conceptual Design

## Executive Summary
  This report examines how a Unicam stlye overhead cam valve train system works, its key componenets and its potential failure points. The valevtrain is a critcal component in a four-stroke engine assembly, as it controls the timing and motion of the intake and exhaust valves, which regulates the the air-fule mixture entering the combustion chamber and the exhaust gases leaving. The Unicam® system is registered trademark of Honda Motor Co. Ltd. and combines the best characteristice of single overhead cam (SOHC) and double overhead cam (DOHC). 

## System Function and Decomposition
  Overall function: Convert crankshaft rotation into precisely phased valve motion (lift, dwell, and seating) to control cylinder air exchange (intake and exhaust) during the four-stroke combustion cycle. 13,000RPPM

<p align="center"> 
  <img src="figures/Assembled_Arrows.png" width="400"> 
</p>

<p align="center">
  <img src="figures/Exploded_Valves_Arrows.png" width="600">
</p>

<p align="center">
  <img src="figures/Valve_Assembled_Arrows.png" width="500">
</p>


## Componenet Breakdown
| Component | Image |
|----------|--------|
| **Cylinder Head**  
This component provides the structural support and alignment for the camshaft bearings, valve guides, and rocker arm pivots. | <img src="figures/Cylinder_Head.png" width="160"> |
| **Camshaft**  
The camshaft controls valve timing and lift. Intake valves are directly actuated via cam–follower contact, while exhaust valves are actuated through cam–rocker contact. | <img src="figures/Camshaft.png" width="160"> |
| **Rocker Arm**  
Located on the exhaust side, the rocker arm transfers cam motion to the exhaust valves, allowing for a more compact system layout. | <img src="figures/Rocker.png" width="160"> |
| **Valves**  
Intake valves allow the air–fuel mixture into the cylinder while exhaust valves release combustion gases. The valves are subjected to repeated impact loading, bending, and high-cycle fatigue. | <img src="figures/Valves.png" width="160"> |
| **Valve Springs**  
The valve spring closes the valve after cam actuation and maintains follower contact. It must be stiff yet durable, typically made from chrome-silicon steel due to its fatigue resistance at high RPM. | <img src="figures/Valve_Springs.png" width="160"> |
| **Valve Guides**  
Valve guides maintain valve alignment during motion and facilitate heat transfer from the valve to the cylinder head. Excessive wear can lead to oil consumption and poor sealing. | <img src="figures/Valve_Guide.png" width="160"> |
| **Valve Bucket (Follower)**  
The valve bucket sits between the cam lobe and valve stem, transmitting cam motion while reducing friction and wear. It also maintains proper lift and alignment within the valvetrain. | <img src="figures/Valve_Bucket.png" width="160"> |
| **Timing Chain**  
The timing chain synchronizes camshaft and crankshaft motion, using guides and a tensioner to maintain proper chain tension and reduce vibration. | <img src="figures/Cam_Chain.png" width="160"> |
| **Camshaft Bearings**  
Camshaft bearings support the camshaft and transfer loads to the cylinder head, reducing friction and ensuring smooth rotation at high engine speeds. | <img src="figures/Cam_Bearing.png" width="160"> |

## Kinematics
Kinematics describes how rotational input at the crankshaft produces cam motion and valve lift. For a four-stroke engine, each cylinder completes one intake and one exhaust event every two crank revolutions.

## Preliminary Failure Mode Review
Spring Fatigue - Over long periods, cyclic loading of the valve springs can lead to fatigue and eventual failure, reducing their ability to properly control the valves. In some cases, this spring failure leads to gear wear and may cause the timing system to jump a tooth, misaligning the camshaft relative to the pistons’ motion. Spring fatigue can be avoided by using springs with improved cyclic loading properties or by repairing or replacing springs more routinely.

## Critical Design Parameters
Geometry that controls motion:
Cam lobe geometry (intake and exhaust lobes): base circle, max lift, duration, ramp shape
