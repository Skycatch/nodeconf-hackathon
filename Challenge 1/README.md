# DataSet Content

The folder will contain diferent dataset from diferent drones:

* EX1 is from our drone called Explore1
* P4P is from another drone
* Simulations are flight logs that we obtain through a virtual simulation of both of the drones above

One time Headers (these only appear in the first line of the CSV):

* appVersion
* AircraftComercialName	
* AircraftSerialNumber	
* RemoteSerialNumber	
* BatterySerialNumber	
* BatteryFullCapacity	
* dischargeCount	
* batteryLife	
* AircraftModel	
* sonar_altitude	
* isTakingVideo

Regular Headers (the value in these columns are constantly being inserted during the flight)

* latitude
* longitude	
* flight_time (in milliseconds)
* altitude (meters, relative to takeoff point)
* speed	(m/s)
* satellites	
* gps_level (signal strength)
* pitch (degrees)
* roll (degrees)	
* yaw (degrees)
* timestamp (in UTC format)
* last_updated (when was the data last updated, in milliseconds)
* velocityX	
* velocityY	
* velocityZ	
* Isflying (1 for true, 0 for false)
* remainBatteryPercent	
* currentCurrent
* batteryChargeRemaining	
* batteryVoltage	
* batteryTemperature	
* flightMode	(this is an integer, belonging to the enumeration described below)
* Istakingphoto (1 for true, 0 for false)
* downlinkSignal	
* uplinkSignal	
* radioChannel	
* rc_elevator	
* rc_aileron	
* rc_throttle	
* rc_rudder	
* Battery_Cell1 (The voltage of cell 1 - in volts*1000)
* Battery_Cell2	
* Battery_Cell3	
* Battery_Cell4	
* Battery_Cell5	
* Battery_Cell6	
* gimbalPitch	
* gimbalYaw	
* gimbalRoll	
* app_Tip  (Used for optionally describe the status of the mission)
* app_Warning (Used for reporting errors, either custom or reported by DJI)

Flight Modes

Hello                                                                      |  hello
---------------------------------------------------------------------------|----------------------------------------
 /** Manual mode. */                                                       |  DJIFlightModeManual = 0
 /** Attitude mode. */                                                     |  DJIFlightModeAtti = 1,
/**  Attitude course lock mode.  */                                        |  DJIFlightModeAttiCourseLock = 2,
/**  GPS Attitude mode. */                                                 |  DJIFlightModeGPSAtti = 6,
/** GPS course lock mode. */                                               |  DJIFlightModeGPSCourseLock = 7,
/** GPS Home mode.*/                                                       |  DJIFlightModeGPSHomeLock = 8,
/** GPS hot point mode.*/                                                  |  DJIFlightModeGPSHotPoint = 9,
 /**  Assisted takeoff mode.*/                                             |  DJIFlightModeAssistedTakeoff = 10,
/**  Auto takeoff mode.*/                                                  |  DJIFlightModeAutoTakeoff = 11,
  /**  Auto landing mode. */                                               |  DJIFlightModeAutoLanding = 12,
 /**  GPS waypoint mode. */                                                |  DJIFlightModeGPSWaypoint = 14,
 /** Go home mode. */                                                      |  DJIFlightModeGoHome = 15,
/**  Joystick mode. */                                                     |  DJIFlightModeJoystick = 17,
/** Attitude limited mode.*/                                               |  DJIFlightModeGPSAttiWristband = 18,
/** Draw mode.  */                                                         |  DJIFlightModeDraw = 24,
 /**  GPS follow me mode.*/                                                |  DJIFlightModeGPSFollowMe = 25,
 /**  ActiveTrack mode.*/                                                  |  DJIFlightModeActiveTrack = 26,
 /**  TapFly mode.*/                                                       |  DJIFlightModeTapFly = 27,
 /**  Sport mode. */                                                       |  DJIFlightModeGPSSport = 31,
 /**  GPS Novice mode. */                                                  |  DJIFlightModeGPSNovice = 32,
 /**  Confirm landing mode.*/                                              |  DJIFlightModeConfirmLanding = 33,
 /**  The aircraft should move following the terrain.*/                    |  DJIFlightModeTerrainFollow = 35,
 /**  Tripod mode.*/                                                       |  DJIFlightModeTripod = 38,
 /**  Active track mode, corresponds to Spotlight active track mode. */    |  DJIFlightModeActiveTrackSpotlight = 39,
 /**  The motors are just started. */                                      |  DJIFlightModeMotorsJustStarted = 41,
 /**  The main controller flight mode is unknown.  */                      |  DJIFlightModeUnknown = 0xFF,

