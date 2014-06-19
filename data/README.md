# all_crashes_2008_to_2012  

### Data Dictionary

| Field | Description  | Key
| ----- | ----------  | ---
| CRN |  Crash Record Number |
| POLICE_AGC |  Code of the reporting Police Agency | 67301 - Philadelphia City, 67501 - Delaware River Port Authority, 67503 - Philadelphia Naval Base, 67504 - University Of Pennsylvania, 67505 - Temple University,  67601 - Philadelphia County Sheriffs Dept, 68000 - Pa State Police, 68K01 - Philadelphia State Police
| CRASH_YEAR |  Year when the crash occurred |
| CRASH_MONT |  Month when the crash occurred |
| DATE_OF_MO |  Day of the Month when crash occurred |
| DAY_OF_WEE |  Day of the Week code when crash occurred |
| TIME_OF_DA |  Time of day when crash occurred |
| HOUR_OF_DA |  Hour of day when crash occurred |
| ILLUMINATI |  Code that defines lighting at the crash scene | 1 – Daylight, 2 – Dark – no street lights, 3 – Dark – street lights, 4 – Dusk, 5 – Dawn, 6 – Dark – unknown roadway lighting, 8 – Other, 9 – Unknown (expired)
| WEATHER |  Code for the weather at time of crash | 1 – No adverse conditions, 2 – Rain, 3 – Sleet (hail), 4 – Snow, 5 – Fog, 6 – Rain and fog, 7 – Sleet and fog, 8 – Other, 9 – Unknown
| ROAD_CONDI |  Roadway Surface Condition Code | 0 – Dry, 1 – Wet, 2 – Sand/ mud/ dirt/ oil/ or gravel, 3 – Snow covered, 4 – Slush, 5 – Ice, 6 – Ice Patches, 7 – Water – standing or moving, 8 – Other, 9 – Unknown (expired)
| COLLISION_ |  Collision category that defines the crash | 0 – Non collision, 1 – Rear-end, 2 – Head-on, 3 – Rear-to-rear (Backing), 4 – Angle, 5 – Sideswipe (same dir.), 6 – Sideswipe (Opposite dir.), 7 – Hit fixed object, 8 – Hit pedestrian, 9 – Other or Unknown
| RELATION_T |  Code for the crash's relativity to the road | 1 – On roadway, 2 – Shoulder, 3 – Median, 4 – Roadside (off trafficway; on vehicle area), 5 – Outside trafficway (in area not meant for vehicles), 6 – In parking lane, 7 – Gore (intersection of ramp and highway), 9 – Unknown
| WORK_ZONE_ |  The Work Zone Location Code | 1 – Before the 1st work zone warning sign, 2 – Advance warning area, 3 – Transition area, 4 – Activity area, 5 – Termination area, 8 – Other
| WORK_ZONE1 |  Code to define the type of Work Zone | 1 – Construction, 2 – Maintenance, 3 – Utility company
| INTERSECT_ |  Code that defines the Intersection Type | 00 – Mid-block, 01 – Four way intersection, 02 – “T” intersection, 03 – “Y” intersection, 04 – Traffic circle or Round About, 05 – Multi-leg intersection, 06 – On ramp, 07 – Off ramp, 08 – Crossover, 09 – Railroad crossing, 10 – Other, 99 – Unknown (expired)
| TCD_TYPE |  Code that defines the Traffic Control Device | 0 – Not applicable, 1 – Flashing traffic signal, 2 – Traffic signal, 3 – Stop sign, 4 – Yield sign, 5 – Active RR crossing controls, 6 – Passive RR crossing controls, 7 – Police officer or flagman, 8 – Other Type TCD, 9 – Unknown
| LOCATION_T |  Code that defines the crash location | 0 – Not applicable, 1 – Underpass, 2 – Ramp, 3 – Bridge, 4 – Tunnel, 5 – Toll Booth, 6 – Cross over related, 7 – Driveway or Parking Lot, 8 – Ramp and bridge, 9 – Unknown
| SCH_BUS_IN |  Did the crash involve a School Bus? |  (Y/N)
| SCH_ZONE_I |  Did the crash occur in a School Zone? |  (Y/N)
| PERSON_COU |  Total amount of people involved | 
| VEHICLE_CO |  Total amount of all vehicles involved |
| AUTOMOBILE |  Total amount of automobiles involved |
| MOTORCYCLE |  Total amount of motorcycles involved |
| BUS_COUNT |  Total amount of buses involved |
| SMALL_TRUC |  Total amount of small trucks involved |
| HEAVY_TRUC |  Total amount of heavy trucks involved |
| SUV_COUNT |  Total amount of Sport Utility Vehicles involved |
| VAN_COUNT |  Total amount of vans involved |
| BICYCLE_CO |  Total amount of bicylces involved |
| FATAL_COUN |  Total amount of fatalities involved |
| MAJ_INJ_CO |  Total amount of Major Injuries involved |
| MOD_INJ_CO |  Total amount of Moderate Injuries involved |
| MIN_INJ_CO |  Total amount of Minor Injuries involved |
| TOT_INJ_CO |  Total amount of injuries involved |
| UNK_INJ_DE |  Number of injuries with unknown severity |
| UNK_INJ_PE |  Number of people that are unknown if injured |
| DRIVER_COU |  Total amount of 16 year old drivers |
| DRIVER_C_1 |  Total amount of 17 year old drivers |
| DRIVER_C_2 |  Total amount of 65 to 74 year old drivers |
| DRIVER_C_3 |  Total amount of drivers ages 75 and up |
| UNBELTED_O |  Total count of all unbelted occupants |
| UNB_DEATH_ |  Number of people killed not wearing a seatbelt |
| UNB_MAJ_IN |  Total number of unbelted sustaining Major Injuries |
| BELTED_DEA |  Total deaths of belted occupants |
| BELTED_MAJ |  Total major injuries of belted occupants |
| MCYCLE_DEA |  Total amount of Motorcyclist fatalities |
| MCYCLE_MAJ |  Total amount of Motorcyclist Major Injuries |
| BICYCLE_DE |  Total amount of Bicyclist fatalities |
| BICYCLE_MA |  Total amount of Bicyclist Major Injuries |
| PED_COUNT |  Total amount of Pedestrians involved |
| PED_DEATH_ |  Total amount of Pedestrian fatalities |
| PED_MAJ_IN |  Total amount of Pedestrian Major Injuries |
| MAX_SEVERI |  Injury severity level of the crash |
| COMM_VEH_C |  Total Commercial vehicles involved |
| LATITUDE |  GPS Coordinates in Degrees, Minutes, Seconds |
| LONGITUDE |  GPS Coordinates in Degrees, Minutes, Seconds |
| CRASH_DATE |  Date of crash |
| ARRIVAL_TM |  Time police arrived at the scene |
| CONS_ZONE_ |  Speed limit for the construction zone |
| CRS_INVEST |  Date the investigation was opened |
| DISPATCH_T |  Time police were dispatched to the scene |
| lat_final |  GPS Coordinate in decimal degrees |
| long_final |  GPS Coordinate in decimal degrees |
| INTERSTATE |  Non-turnpike Interstate Indicator |  0 = No, 1 = Yes
| STATE_ROAD |  State Road Indicator |  0 = No, 1 = Yes
| LOCAL_ROAD |  Local Road Indicator |  0 = No, 1 = Yes
| LOCAL_RO_1 |  Local Road Only Indicator |  0 = No, 1 = Yes
| TURNPIKE |  Turnpike Indicator |  0 = No, 1 = Yes
| WET_ROAD |  Wet Road Indicator |  0 = No, 1 = Yes
| SNOW_SLUSH |  Snow Slush Road Indicator |  0 = No, 1 = Yes
| ICY_ROAD |  Icy Road Indicator |  0 = No, 1 = Yes
| SUDDEN_DEE |  Sudden Deer Indicator |  0 = No, 1 = Yes
| SHLDR_RELA |  Shoulder Related Indicator |  0 = No, 1 = Yes
| REAR_END |  Rear End Collision Indicator |  0 = No, 1 = Yes
| HO_OPPDIR_ |  Head on or Side Swipe Indicator |  0 = No, 1 = Yes
| HIT_FIXED_ |  Hit Fixed Object Indicator |  0 = No, 1 = Yes
| SV_RUN_OFF |  Single Vehicle Run Off Road Indicator |  0 = No, 1 = Yes
| WORK_ZONE |  Work Zone Indicator |  0 = No, 1 = Yes
| PROPERTY_D |  Property Damage Only Indicator |  0 = No, 1 = Yes
| FATAL_OR_M |  Fatal or Major Injury Indicator |  0 = No, 1 = Yes
| INJURY |  Injury Indicator |  0 = No, 1 = Yes
| FATAL |  Fatality Indicator |  0 = No, 1 = Yes
| NON_INTERS |  Non Intersection Indicator |  0 = No, 1 = Yes
| INTERSECTI |  Intersection Indicator |  0 = No, 1 = Yes
| SIGNALIZED |  Signalized Intersection Indicator |  0 = No, 1 = Yes
| STOP_CONTR |  Stop Controlled Intersection Indicator |  0 = No, 1 = Yes
| UNSIGNALIZ |  Unsignalized Intersection Indicator |  0 = No, 1 = Yes
| SCHOOL_BUS |  School Bus Indicator |  0 = No, 1 = Yes
| SCHOOL_ZON |  School Zone Indicator |  0 = No, 1 = Yes
| HIT_DEER |  Hit Deer Indicator |  0 = No, 1 = Yes
| HIT_TREE_S |  Hit Tree or Shrub Indicator |  0 = No, 1 = Yes
| HIT_EMBANK |  Hit Embankment Indicator |  0 = No, 1 = Yes
| HIT_POLE |  Hit Pole Indicator |  0 = No, 1 = Yes
| HIT_GDRAIL |  Hit Gide Rail Indicator |  0 = No, 1 = Yes
| HIT_GDRA_1 |  Hit Gide Rail End Indicator |  0 = No, 1 = Yes
| HIT_BARRIE |  Hit Barrier Indicator |  0 = No, 1 = Yes
| HIT_BRIDGE |  Hit Bridge Indicator |  0 = No, 1 = Yes
| OVERTURNED |  Overturned Vehicle Indicator |  0 = No, 1 = Yes
| MOTORCYC_1 |  Motorcycle Indicator |  0 = No, 1 = Yes
| BICYCLE |  Bicycle Indicator |  0 = No, 1 = Yes
| HVY_TRUCK_ |  Heavy Truck Related Indicator |  0 = No, 1 = Yes
| VEHICLE_FA |  Vehicle Failure Indicator |  0 = No, 1 = Yes
| TRAIN_TROL |  Train or Trolley Indicator |  0 = No, 1 = Yes
| PHANTOM_VE |  Phantom Vehicle Indicator |  0 = No, 1 = Yes
| ALCOHOL_RE |  Alcohol Related Indicator |  0 = No, 1 = Yes
| DRINKING_D |  Drinking Driver Indicator |  0 = No, 1 = Yes
| UNDERAGE_D |  Underage Drinking Driver Indicator |  0 = No, 1 = Yes
| UNLICENSED |  Unlicensed Driver Indicator |  0 = No, 1 = Yes
| CELL_PHONE |  Driver Using Cell Phone Indicator |  0 = No, 1 = Yes
| NO_CLEARAN |  No Clearance Indicator |  0 = No, 1 = Yes
| RUNNING_RE |  Driver Running Red Light Indicator |  0 = No, 1 = Yes
| TAILGATING |  Tailgating Indicator |  0 = No, 1 = Yes
| CROSS_MEDI |  Cross Median Indicator |  0 = No, 1 = Yes
| CURVE_DVR_ |  Curve in Road Driver Error Indicator |  0 = No, 1 = Yes
| LIMIT_65MP |  65MPH Speed Limit Indicator |  0 = No, 1 = Yes
| SPEEDING |  Speeding Indicator |  0 = No, 1 = Yes
| SPEEDING_R |  Speeding Related Indicator |  0 = No, 1 = Yes
| AGGRESSIVE |  Aggressive Driving Indicator |  0 = No, 1 = Yes
| FATIGUE_AS |  Fatigue or Asleep Indicator |  0 = No, 1 = Yes
| DRIVER_16Y |  Driver 16 years of age Indicator |  0 = No, 1 = Yes
| DRIVER_17Y |  Driver 17 years of age Indicator |  0 = No, 1 = Yes
| DRIVER_65_ |  Driver is between 65 and 74 Indicator |  0 = No, 1 = Yes
| DRIVER_75P |  Driver is 75 years of age plus Indicator |  0 = No, 1 = Yes
| UNBELTED |  Anyone in crash is unbelted Indicator |  0 = No, 1 = Yes
| PEDESTRIAN |  Pedestrian Indicator |  0 = No, 1 = Yes
| DISTRACTED |  Distracted Driver Indicator |  0 = No, 1 = Yes


### Use Limitations  

None