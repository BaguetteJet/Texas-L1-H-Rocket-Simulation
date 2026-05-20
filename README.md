# Texas L1 - My First High Power Rocket
See full flight RocketPy simulation in [TexasL1.ipynb](TexasL1.ipynb)

~~*Expected Launch: 22 Nov 2025*~~      
~~*Expected Launch: 25 April 2026*~~    
*Expected Launch: 30 May 2026*   

## Overview

Texas L1 is my first high-power rocket build, created with the purpose of earning Level 1 High Power Rocketry Certification. Designed though OpenRocket with the guidance of [ULAS HiPR](https://www.ulas-hipr.ie/). The mission prioritizes simplicity, survivability and recoverability.

<img width="2000" height="520" alt="image" src="https://github.com/user-attachments/assets/51911fea-cb7d-4783-91ca-beb0507f5a47" />

## Mission Brief 
The Tripoli Level 1 (L1) Certification is the first level of internationally recognised high-power rocketry certification offered by the [Tripoli Rocketry Association (TRA)](https://www.tripoli.org/Level1). It allows certified individuals to purchase and fly H to I class motors. To earn it, the candidate must build and safely fly a high-power rocket using an H or I motor under supervision, ensuring a stable flight and safe recovery. 

Successful completion demonstrates competence in high-power rocketry, granting permission to participate in higher-powered launches.

## Schedule & Progress
Aug 2025 - mission debrief, budget and planning

Oct 2025
- Week 1 - Initial rocket design
- Week 2 - Finalise rocket design and parts required
- Week 3 - Export parts for production and laser cutting
- Week 4 - Begin construction of inner tube and fin assembly
- Week 5 - 3D print nose cone

Nov 2025
- Week 1 - Purchase motor and launch fees
- Week 2 - Finish inner tube assembly and prepare body tube
- Week 3 - Finish build
- Week 4 - Test and prepare for launch day

~~22 Nov 2025 - LAUNCH DAY~~ (delayed)

April 2026 - Motor changes due to shipment issues

30 May 2026 - LAUNCH DAY

## Table of Values

| Name | Format | Value |
| :--- | :--- | :--- |
| Stability | Cal at M=0.300 | 1.7 cal / 9.88 % |
| CG | mm (from nose) | 643 mm |
| CP | mm (from nose) | 756 mm |
| Length | mm | 1145 mm |
| Max Diameter | mm | 66.5 mm |
| Fin thickness | mm | 3 mm |
| Mass (no motor) | g | 638 g |
| Mass (motor) | g | 825 g |
| Motor | Manufacturer’s code | Cesaroni 166-H163 |
| Delay | seconds | 14 s |
| Time to Apogee | seconds | 10.6 s |
| Expected Apogee | m | 711 m |
| Max Velocity | m/s | 183 m/s |
| Max Acceleration | m/s² | 241 m/s² |
| Ground hit velocity | m/s | 14.5 m/s |

<img width="3684" height="996" alt="image" src="https://github.com/user-attachments/assets/e002c8b0-4903-4744-a35f-8284ae8a623f" />


## Build

### Nosecone
3D printed out of ABS 100% infill. Ogive 1.0 shape, 230 mm length, 66.5 mm base diameter, 5 mm wall thickness, 50 mm shoulder length, 260 g total mass. Nosecone modified in Solidworks to add strength. Base OpenRocket 200 g nose cone plus additional 60 g mass component inside the nose cone to account for the extra infill in the tip of the cone.

<img width="2553" height="1038" alt="image" src="https://github.com/user-attachments/assets/1838e72c-d511-4165-a744-ca04cbb7dea7" />

Capped off the nose cone with a snug fit plywood bulkhead glued in using super glue. Covered nose cone shoulder in high-vis tape to make it more visible and to ensure the shoulder fits the body tube snuggly. Added a simple JHE42B drone buzzer to aid rocket recovery by emitting noise. QR code to help identify owner.

<img width="2328" height="800" alt="image" src="https://github.com/user-attachments/assets/5d237b7e-a884-4db9-a995-4d9be76989d7" />

### Body tube
Cardboard 915 mm length, 66.5 mm outer diameter, 1.5 mm wall thickness. Assembly glued using wood glue. Body tube wrapped with custom vinyl livery after build completion.

<img width="2000" height="704" alt="image" src="https://github.com/user-attachments/assets/92782082-3617-4fec-ac2e-a0e81db05544" />

### Fin Can
Cardboard inner tube 448 mm length, 41 mm outer diameter, 1.5mm thickness. Three sets of centering rings 6 mm thickness (3 mm plywood doubled up), 63.5 mm outer diameter, 41 mm inner diameter. Ring on each end of the tube and a third ring 166 mm from the base. 

Three plywood freeform fins 3 mm thickness, attached firmly between centering rings. Spaced evenly using 3D printed spacer. Assembly glued using wood glue.

<img width="1867" height="714" alt="image" src="https://github.com/user-attachments/assets/dfcb5df1-7b9b-40b2-b3ea-1a6ff01a879d" />

### Recovery System
Single deployment parachute deployed through motor ejection charge. Shockcord anchored to the inner tube of the rocket links the main body, parachute and nose cone together. All mounting points reinforced with super glue.

<img width="2724" height="1078" alt="image" src="https://github.com/user-attachments/assets/0e45799a-79f2-49c9-a592-9fca38d75619" />

Simple JHE42B drone buzzer to emit noise. Secured firmly to nose cone bulkhead with adhesive and zip ties in case the adhesive fails.

## Mission Concept of Operations

Rocket is placed on the launch rail. 

The motor ignites and the rocket takes off at 20 m/s velocity off launch rail. The Cesaroni 166-H163 motor burns for 1 s of powered flight.

Rocket continues unpowered ascent until 10.6 s.

Rocket reaches 771 m apogee and begins decent.

After 14 s delay, the parachute is deployed. Nose cone splits from the main body but remains attached with the shockcord.

After 59.9 s total flight time, rocket touches down at 14.5 m/s ground hit velocity.

## Simulation
Flight simulation completed using OpenRocket software. 

<img width="2019" height="1070" alt="image" src="https://github.com/user-attachments/assets/dc74ad09-7e27-4660-90d2-5fb70b849711" />

Additional detailed simulation of flight path and predicted landing zone though python, uisng the RocektPy library.
