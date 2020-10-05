## Data store types


### General data
The data about the project.

|Name|Description|Type of data|Example|
|----|-----------|------------|-------|
|api_version|The current version of the API|Version|`1.0.0`
|firmware_version|The current version of the firmware|Version|`1.0.0`
|dashboard_version|The current version of the dashboard|Version|`2.2.6`
|total_team_members|The current total team member count|Number|`15`


### General probe data
The general data/information of a probe.

|Name|Description|Type of data|Example|
|----|-----------|------------|-------|
|LaunchID|The id of the launch|Number|`3`
|Launchtime|The timestamp when the probe started|Timestamp|`2020-09-20 18:51:16`
|Launchsuccessful|Whether the probe has crashed|Bool|`true`
|Datareceived|Whether data was received|Bool|`false`
|ProbeWeight|The weight of the probe|Float(uses unit gram)|`3.5`
|ProbeVersion|The version of the probe|Version|`1.2`
|BalloonWeight|The weight of the balloon|Float(uses unit gram, is negative)|`-3.9`
|BalloonVersion|The version of the balloon|Version|`4.2`
|FirmwareVersion|The version of the firmware|Version|`7.4`
 
 
 ### Measure data
The measure data form the probes. 
 
|Name|Description|Type of data|Example|
|----|-----------|------------|-------|
|MeasureTimestamp|The timestamp when the data was received|Timestamp|`2020-09-29 15:57:05`
|Temp|The temperature of the probe|Float(uses unit °C)|`-10.1`
|CoordinatesLat|The position|Coordinate|`40.7143528`
|CoordinatesLon|The position|Coordinate|`-74.0059731`
|Altitude|The altitude of the probe|Float|`4`
|Speed|The speed of the probe|Float|`12`
|SolarPanelVoltage|The solar panel voltage of the probe(uses unit V)|Float|`1.4`
|Pressure|The pressure of the probe|Float|`453`
|Humidity|The humidity of the probe|Float|`3443`
|UVRadiation|The UV radiation of the probe|Float|`34`
|GatewayLocationLat|The position of the RF gateway|Text|`52.1234`
|GatewayLocationLon|The position of the RF gateway|Text|`6.1234`
|GatewayID|The id of the RF gateway|Text|`ttn-herengracht-ams`
|RSSI|The RSSI of the RF|Float|`-25`
|SNR|The SNR of the RF|Float|`5`
|Sparing factor|The sparing factor of the RF|Float|`I dont know`
|Frequency|The frequency of the RF|Float|`868.1`
