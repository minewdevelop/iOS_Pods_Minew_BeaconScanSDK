# Change Log

## [1.0.0](https://github.com/minewdevelop/iOS_Pods_Minew_WristbandSDK/releases/tag/1.0.0)(12/4/2020)

Released on Friday, December 4, 2020. 

#### Added

- MinewBeaconManager
  
  - Core
    - Start scan
    - Stop scan
  
  - Delegate
    - minewBeaconManager: didUpdateState:
    - minewBeaconManager: appearBeacons:
    - minewBeaconManager: disappearBeacons:
    - minewBeaconManager: didRangeBeacons:
  
- MinewBeacon
  
   - Core
     - getBeaconValue
  
  - Types of beacon value
    - BeaconValueIndex_UUID = 1,   // UUID stringValue
    - BeaconValueIndex_Major,     // major, intValue
    - BeaconValueIndex_Minor,     // minor, intValue
    - BeaconValueIndex_Name,     // device's name, stringValue
    - BeaconValueIndex_WechatId,   // wechat device id, intValue
    - BeaconValueIndex_Mac,      // Mac Address, stringValue
    - BeaconValueIndex_RSSI,     // RSSI, intValue
    - BeaconValueIndex_BatteryLevel, // Battery, intValue
    - BeaconValueIndex_Temperature,  // Temperature, floatValue
    - BeaconValueIndex_Humidity,   // Humidity, floatValue
    - BeaconValueIndex_TxPower,    // TxPower intValue
    - BeaconValueIndex_InRage,    // Is in range, boolValue
    - BeaconValueIndex_Connectable,  // Connectable state, boolValue