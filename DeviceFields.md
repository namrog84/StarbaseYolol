
Yolol field names

## MaterialScanner
YOLOL field | Description | Range
--- | --- | ---
Active | The scanner turns off when this is set to 0 and on when set to anything else | 0 - 1
Index | The current material to provide information for. Starting at 0 | 0 -
ScanResults | The number of diferent materials the object contains | 0 -
Material | The material of the current 'Index' i.e. "Ukonium" | String
Volume | The Volume of the current 'Index' i.e. 272 | 0 -
Scan | Must be set to 1 to initiate a scan, auto-resets to 0 once scan is complete | 0 - 1
Reset | Resets the stored scan result | 0 - 1

## Utility tool capacitor
YOLOL field | description| range
--- | --- | ---
StoredLocalPower | How much power is stored in the utility ammo | 0 - 4000
MaxLocalPower | Maximum amount of power ammo that can be stored | 4000

## Battery
YOLOL field | description| range
--- | --- | ---
BatteryPriority | Batteries with a lower priority get used first | 
StoredBatteryPower | Current charge level of the battery | 0 - 10 000
MaxBatteryPower | Maximum charge level of the battery | 10 000

## Turret cradle
https://wiki.starbasegame.com/index.php/Turret_cradle
YOLOL field | description| range
--- | --- | ---
TurretPitch | Target pitch of the cradle | 0
TurretCurrentPitch | Current rotation of the cradle | 0
MaxRotation | High limit of the rotation | 180 / 160 on basic cradle
MinRotation | Low limit of the rotation | -180 / -20 on basic cradle
TargetVelocity | Target velocity with which the cradle rotates | 3

## Cooling Rack
https://wiki.starbasegame.com/index.php/Cooling_rack
YOLOL field | description| range
--- | --- | ---
CoolerUnitRateLimit | Upper limit for conversion rate for this cooler | 0 - 100
CoolerUnitRate | Current conversion rate for this cooler. Conversion is being performed at 1 conversion * this percentage per second. | 0 - 100

## Fuel chamber
https://wiki.starbasegame.com/index.php/Fuel_chamber
YOLOL field | description| range
--- | --- | ---
FuelChamberFuel | The amount of fuel currently available in this chamber's fuel rod | 0 - 300000
FuelChamberMaxFuel | Maximum amount of fuel that can be stored in this chamber's rod, zero if no rod | 0 - 300000
FuelChamberUnitRateLimit | Upper limit for conversion rate for this fuel chamber | 0 - 100
FuelChamberUnitRate | Current conversion rate for this fuel chamber. Conversion is being performed at 1 conversion * this percentage per second | 0 - 100

## Generator unit
https://wiki.starbasegame.com/index.php/Generator_unit
YOLOL field | description| range
--- | --- | ---
GeneratorUnitRateLimit | Upper limit for conversion rate for this generator block | 0 - 100
GeneratorUnitRate | Current conversion rate for this generator block. Conversion is being performed at 1 conversion * this percentage per second. | 0 - 100