# INTEGRATION
## Model Overview
The INTEGRATION 2.40 model is a trip-based microscopic traffic assignment, simulation, and optimization model that is capable of modeling networks of up to 10,000 links and 500,000 vehicle departures. The model is designed to trace individual vehicle movements from a vehicle's origin to its final destination at a level of resolution of one deci-second. The model simulates the departures of vehicles from a time-varying origin-destination (O-D) table. Vehicles are assigned to the network using a time-varying multi-class traffic assignment. Vehicles are then tracked at a deci-second level of resolution by modeling vehicle car-following, lane-changing, and gap acceptance behavior. Specifically, vehicle's select their speed based on link-specific steady-state car-following relationships that are calibrated using field loop detector data. A vehicle's movement from one steady-state to another is constrained its dynamics.

The model computes a number of measures of performance including vehicle delay, stops, fuel consumption, hydrocarbon, carbon monoxide, carbon dioxide, and nitrous oxides emissions, and the crash risk for 14 crash types.

## Domain of Application
The current domain of application of the commercial version of INTEGRATION includes pre-trip and en-route driver decisions, starting from the time a driver has elected to depart from a particular origin with the objective of reaching a particular destination, at a particular time, and by means of a specific vehicle class. This implies that, at present, the commercial version of INTEGRATION does not directly model the impact of drivers electing to depart at a different time, by means of a different mode, or to an alternate destination.

## Historical Background of INTEGRATION
The model was initially developed in 1983 by the late Michel Van Aerde who continued its development until 1999. Dr. Hesham Rakha continues directing development of the model since 1999. The name of the model stems from the fact that the model was developed to integrate the modeling of freeway/arterial corridors and to integrate traffic assignment with traffic simulation.

INTEGRATION was initially developed as a mesoscopic model and then evolved into a microscopic model in 1995. Further enhancements to the model included the incorporation of a multi-modal dynamic traffic assignment, the modeling of adaptive signal control, the modeling of transit vehicles and transit priority, the inclusion of microscopic energy and emission models, the incorporation of a crash risk model, and the inclusion of tolls and High Occupancy Lanes (HOVs).

The model is commercially sold worldwide through M. Van Aerde and Assoc., Ltd. The model is also being distributed by McTrans in the US.

## Model Features and Capabilities
The INTEGRATION model is unique in a number of aspects. First, the model combines traffic assignment with microscopic simulation. Second, the model captures vehicle dynamics in terms of its acceleration behavior. Third, the model includes detailed microscopic energy, emission, and safety models. Finally, the INTEGRATION software provides flexibility in modeling numerous Intelligent Transportation System (ITS) applications.

### Microscopic Traffic Assignment and Simulation

A unique feature of the INTEGRATION software is its integration of time-dependent traffic assignment capabilities with microscopic simulation. The INTEGRATION simulation model provides ten basic user equilibrium traffic assignment/routing options:

- Option 1: Time-Dependent Method of Successive Averages
- Option 2: Time-Dependent Sub-Population Feedback Assignment
- Option 3: Time-Dependent Individual Feedback Assignment
- Option 4: Time-Dependent Dynamic Traffic Assignment
- Option 5: Time-Dependent Frank-Wolf Algorithm
- Option 6: Time-Dependent External Routing 1
- Option 7: Time-Dependent External Routing 2
- Option 8: Distance Based Routing
- Option 9: Time-Dependent Sub-population Feedback Eco-Assignment (ECO-SFA
- Option 10: Time-Dependent Individual Feedback Eco-Assignment (ECO-IFA)
  
### Car-Following
A vehicle within the simulation model computes its desired speed on the basis of the distance headway and speed differential between a vehicle and the vehicle immediately downstream of it within the same lane. The car-following model is calibrated macroscopically using loop detector data. The vehicle's ability to achieve its desired speed is constrained by its power to weight ratio, the aerodynamic resistance, the rolling resistance, and the grade resistance. A total of 25 vehicle types are incorporated in the model to capture different vehicle dynamics capabilities. The explicit modeling of car-following behavior means that the model captures the spatial and temporal formation of queues upstream of bottlenecks and the formation of shockwaves. The explicit modeling of lane changing behavior means that the model can capture the dynamic change in the capacity of a merge, diverge, or weaving section.

## Energy and Emission Models
The model computes a vehicle's fuel consumption and HC, CO, CO2, and NOx emissions every second as it travels within the network. In addition, the model can disperse the vehicle emissions based on a user input wind speed and direction. The software can model 5 normal light duty vehicle categories, 2 normal light duty truck categories, 4 high emitter types, and 1 heavy duty truck. This unique feature of the model allows the model to accurately access the environmental impacts of operational-level transportation projects.

## Crash Risk Models
The INTEGRATION model also computes 14 different crash risks and the level of vehicle damage and passenger injury severity. The crash risk model was developed using the General Estimates System (GES) crash database.

## Intelligent Transportation Systems

With its unique capabilities, the INTEGRATION software is capable of evaluating the efficiency, throughput, energy, environmental, and safety impacts of Intelligent Transportation Systems. The model is capable of modeling numerous ITS applications, including:

- Adaptive traffic signal optimization of cycle length, phase split, and offset.
- Traffic signal actuation by vehicle class and transit priority.
- Time dependent fixed-time ramp metering.
- Advanced Traveler Information Systems and Variable Message Signs.
- Toll roads and High Occupancy Vehicle (HOV) lanes.

## Model Validation
Numerous features of the model have been validated against standard traffic flow theory and field data. The features of the model that have been validated include:

- Traffic assignment for static and dynamic demands.
- Lane changing behavior at merge, diverge, and weaving sections.
- Gap acceptance logic as a function of the type of movement, the distribution of gap sizes, and the non-homogeneity of the driving population.
- Car-following behavior, delay, stops, and queue length estimation.
- Energy and emission models.

## Model Applications
The model has been and continues to be used extensively in Canada, the US, and the Netherlands. The model is also being used in Brazil, Korea, Singapore, Italy, and France. The model has been used by researchers, transportation planners, and traffic engineers from both the private and public sector. Some of the model applications include:

- Modeling of eco-lanes applications
- Modeling of speed harmonization and dynamic speed limits
- Modeling of merge, diverge, and weaving sections.
- Modeling of time-varying fixed-time ramp metering.
- Modeling of differential speed limits by vehicle type.
- Modeling of two-way and four-way stop controlled intersections, yield approaches, and roundabouts.
- Modeling of right turn on red, permissive and protected left turns at signalized intersections.
- The impacts of different lane striping configurations on the performance of signalized intersections.
- Modeling of fixed-time traffic signal control, time-dependent fixed-time traffic signal control, and adaptive optimization of cycle length, phase split and offsets.
- Modeling of passenger cars, High Occupancy Vehicles, buses and trucks.
- Modeling of incident and construction management, toll roads, and HOV lanes.
- Modeling of Variable Message Signs, Advanced Traveler Information Systems (ATIS), and Advanced Traffic Management Systems (ATMS).
- Modeling of loop detectors and Automatic Vehicle Identification (AVI) tags.
- Modeling of downtown Houston, TX; Columbus, OH; Salt Lake City, UT; Seattle, WA; and Arlington, VA. Other studies include the modeling of sections of I-81 in Virginia.

## Manuals
- Rakha, H. (2014), INTEGRATION Rel. 2.40 for Windows - User's Guide, Volume I: Fundamental Model Features,  M. Aerde and Associates, Ltd., Blacksburg, Virginia. < PDF Draft >
- Rakha H. (20140), INTEGRATION Rel. 2.40 for Windows - User's Guide, Volume II: Advanced Model Features,  M. Aerde and Associates, Ltd., Blacksburg, Virginia. < PDF Draft >

## Refereed Literature
- Rakha H., Ahn K., and Moran K., (2012), INTEGRATION Framework for Modeling Eco-routing Strategies: Logic and Preliminary Results, International Journal of Transportation Science and Technology, Vol. 1, no. 3, pp. 259-274. <PDF Draft>
- Ahn K. and Rakha H. (2013), “Network-wide Impacts of Eco-routing Strategies: A Large-scale Case Study,” Transportation Research Part D: Transport and Environment. Vol. 25, December, pp. 119-130. DOI: 10.1016/j.trd.2013.09.006. <PDF Draft>
- Rakha H., Ahn K., and Trani A. (2004), The VT-Micro Framework for Modeling of Hot Stabilized Light Duty Vehicle and Truck Emissions. Transportation Research, Part D: Transport & Environment , Vol. 9(1), January, pp. 49-74. < PDF Draft >
- Rakha H. and Ahn K. (2004), INTEGRATION Modeling Framework for Estimating Mobile Source Emissions. Journal of Transportation Engineering , Vol. 130(2), March/April, pp. 183-193. < PDF Draft >
- Ahn K., Rakha H., and Trani A. (2004), Microframework for Modeling of High-Emitting Vehicles, Transportation Research Record: Journal of the Transportation Research Board , No. 1880, pp. 39-49. < PDF Draft >
- Rakha H. and Zhang Y. (2004), The INTEGRATION 2.30 Framework for Modeling Lane-Changing Behavior in Weaving Sections, Transportation Research Record: Journal of the Transportation Research Board , No. 1883, pp. 140-149. < PDF Draft >
- Rakha H., Snare M., and Dion F. (2004), Vehicle Dynamics Model for Estimating Maximum Light Duty Vehicle Acceleration Levels, Transportation Research Record: Journal of the Transportation Research Board , No. 1883, pp. 40-49. < PDF Draft >
- Avgoustis A., Rakha H., and Van Aerde M. (2004), Framework for Estimating Network-wide Safety Impacts of Intelligent Transportation Systems, Intelligent Transportation Systems Safety and Security Conference, Miami, 24-25 March. < PDF Draft >
- Rakha H., Ahn K. , and Trani A. ( 2003), Microscopic Modeling of Vehicle Start Emissions. Transportation Research Record , No. 1842, pp. 29-38. <PDF Draft>
- Rakha H. and Crowther B. (2003), Comparison and Calibration of FRESIM and INTEGRATION Steady-state Car-following Behavior, Transportation Research, 37A, pp. 1-27. < PDF Draft >
- Rakha H. and Lucic I. (2002), Variable Power Vehicle Dynamics Model for Estimating Maximum Truck Acceleration Levels, Journal of Transportation Engineering , Vol. 128(5), Sept./Oct., pp. 412-419.< PDF Draft >
- Rakha H. and Crowther B. (2002), Comparison of Greenshields, Pipes, and Van Aerde Car-following and Traffic Stream Models, Transportation Research Record , No. 1802, pp. 248-262. < PDF Draft >
- Rakha H., Kang Y., and Dion F. (2001), Estimating Vehicle Stops at Under-Saturated and Over-Saturated Fixed-Time Signalized Intersections, Transportation Research Record , No. 1776, pp. 128-137. < PDF Draft >
- Rakha H., Lucic I., Demarchi S., Setti J., and Van Aerde M. (2001), Vehicle Dynamics Model for Predicting Maximum Truck Accelerations, Journal of Transportation Engineering , Vol. 127(5), Oct., pp. 418-425. < PDF Draft >
- Rakha H., Van Aerde M., Bloomberg L., and Huang X. (1998), Construction and Calibration of a Large-Scale Micro-Simulation Model of the Salt Lake Area, Transportation Research Record , No. 1644, pp. 93-102. < PDF Draft >
- Rakha H.A . and M. Van Aerde (1996), A Comparison of the Simulation Modules of the TRANSYT and INTEGRATION Models, Transportation Research Record , No. 1566, pp. 1-7. < PDF Draft >
- Rakha H., Hellinga M., and Van Aerde M. (1996), "Systematic Verification, Validation and Calibration of Traffic Simulation Models," Transportation Research Board 75th Annual Meeting, Washington DC, January, CD-ROM [Paper # 961153].< PDF Draft >
- Van Aerde M., Hellinga B., Baker M., and Rakha H. (1996), "INTEGRATION: An Overview of Current Simulation Features," Transportation Research Board 75th Annual Meeting, Washington DC, January.
- Rakha, H., M. Van Aerde, E. R. Case, and A. Ugge (1989), "Evaluating the Benefits and Interactions of Route Guidance and Traffic Control Strategies Using Simulation," First Vehicle Navigation and Information Systems Conference (VNIS). IEEE, Piscataway NJ, USA n89CH2789-6, pp.296-303.
- Van Aerde, M. and Rakha H. (1989), "Development and Potential of System Optimized Route Guidance Strategies," First Vehicle Navigation and Information Systems Conference (VNIS). IEEE, Piscataway NJ, USA n89CH2789-6, pp. 304-309. 
