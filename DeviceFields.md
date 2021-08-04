


ThrusterState
ThrusterCurrentThrust


MaterialScanner
YOLOL field | Description | Range
--- | --- | ---
Active | The scanner turns off when this is set to 0 and on when set to anything else | 0 - 1
Index | The current material to provide information for. Starting at 0 | 0 -
ScanResults | The number of diferent materials the object contains | 0 -
Material | The material of the current 'Index' i.e. "Ukonium" | String
Volume | The Volume of the current 'Index' i.e. 272 | 0 -
Scan | Must be set to 1 to initiate a scan, auto-resets to 0 once scan is complete | 0 - 1
Reset | Resets the stored scan result | 0 - 1

Utility tool capacitor
YOLOL field | description| range
--- | --- | ---
StoredLocalPower | How much power is stored in the utility ammo | 0 - 4000
MaxLocalPower | Maximum amount of power ammo that can be stored | 4000

Battery
YOLOL field | description| range
--- | --- | ---
BatteryPriority	Batteries with a lower priority get used first	
StoredBatteryPower	Current charge level of the battery	0 - 10 000
MaxBatteryPower	Maximum charge level of the battery	10 000