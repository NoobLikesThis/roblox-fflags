# roblox-fflags

### THANKS TO LUAFV AND MORE FOR FINDING THESE

### Spin 1

###### @bloodraven

``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FIntDebugSimPrimalGSLumpAlpha": "-2147483647",
    "DFIntDebugSimPrimalPreconditioner": "1100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "DFIntDebugSimPrimalWarmstartForce": "-800",
    "DFIntDebugSimPrimalToleranceInv": "1"
}
```
### Xray
###### MAY MAKE FLOOR INVISIBLE SOMETIMES
###### by me

``` json
{
  "DFIntCullFactorPixelThresholdMainViewHighQuality": "1250",
  "DFIntCullFactorPixelThresholdMainViewLowQuality": "1250",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "1250",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "1250",
  "DFIntDebugFRMQualityLevelOverride": "2"
}
```

### lil bro tweakin 

###### BUGGY   

``` json
 { 
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "50",
    "DFIntDebugSimPrimalWarmstartVelocity": "45",
    "DFIntDebugSimPrimalWarmstartForce": "200",
    "DFIntDebugSimPrimalStiffness": "50",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalPreconditioner": "1100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
 }

```
### Esp..?

``` json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest2": "False"
}
```
### Vehicle SpeedHack
``` json
{
    "DFIntDebugSimPrimalWarmstartForce": "40",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "41"
}
```
### Tool Fly

###### by luafv on github

``` json
{
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "DFIntMaxClientSimulationRadius": "2147000000",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntNonSolidFloorPercentForceApplication": "-12000",
    "DFIntDebugSimPrimalPreconditioner": "100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "100",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalWarmstartVelocity": "-150",
    "DFIntDebugSimPrimalWarmstartForce": "-775",
    "DFIntDebugSimPrimalToleranceInv": "1"
}
```
### Backwards Speedhax with noclip

``` json
{
  "DFIntDebugSimPrimalToleranceInv": "1",
  "DFIntDebugSimPrimalPreconditioner": "69",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntMinClientSimulationRadius": "2147000000",
  "DFIntDebugSimPrimalPreconditionerMinExp": "69",
  "DFIntDebugSimPrimalNewtonIts": "1",
  "DFIntMinimalSimRadiusBuffer": "2147000000",
  "DFIntMaxClientSimulationRadius": "2147000000",
  "DFIntDebugSimPrimalWarmstartForce": "-885",
  "DFIntDebugSimPrimalWarmstartVelocity": "-250",
  "DFIntMaximumFreefallMoveTimeInTenths": "1000",
  "DFIntDebugSimPrimalStiffness": "0"
}
```
### BEST NOCLIP

###### @burgerboxer & @dis_spencer

``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntMaximumFreefallMoveTimeInTenths": "1000",
    "DFIntDebugSimPrimalStiffness": "0"
}
```
### Backwards SpeedHax

 \[!WARNING\] **Bugginess and speed depend on the value of
`DFIntDebugSimPrimalWarmstartForce`. Recommended values are `775` and
the value I put.**

\[!TIP\] **For `DFIntDebugSimPrimalWarmstartVelocity`, it's
recommended to use a value of `150`. However, it might be difficult to
 control.**


``` json
{
  "DFIntDebugSimPrimalNewtonIts": "1",
  "DFIntDebugSimPrimalPreconditioner": "69",
  "DFIntDebugSimPrimalPreconditionerMinExp": "69",
  "DFIntDebugSimPrimalToleranceInv": "1",
  "DFIntDebugSimPrimalWarmstartForce": "-885",
  "DFIntDebugSimPrimalWarmstartVelocity": "-350",
  "FFlagDebugSimDefaultPrimalSolver": "True"
}
```

### Low Gravity 1
###### all by luafv between low gravity 1 and low gravity 2

> \[!NOTE\] `'FFlagDebugSimDefaultPrimalSolver' : True`\
> This flag enables the new simulation engine or whatever it is.

\[!CAUTION\] `'DFIntDebugSimPrimalLineSearch' : 1`\
This setting is a poor man's gravity/flight. The default value is
100: - **Above 0:** Low gravity. - **Below 1 to -1:** Will make
gameplay weird, especially with physics. - **Below -1:** Acts as a
poor man's fly mode (not really usable). \
###### [@Amity](https://www.youtube.com/watch?v=5M411LL17B0)

``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "3"
}
```

### Void Unanchored Parts

``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "222"
}
```

### Low Gravity 2
\[!CAUTION\] This is more buggy

``` json
{
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalPreconditioner": "100",
  "DFIntDebugSimPrimalPreconditionerMinExp": "100",
  "DFIntDebugSimPrimalNewtonIts": "1",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalWarmstartVelocity": "-150",
  "DFIntDebugSimPrimalWarmstartForce": "-775",
  "DFIntDebugSimPrimalToleranceInv": "1"
}
```
### Don't touch walls!!!
``` json
    {
        "DFIntDebugSimPrimalNewtonIts": "-2147483647",
        "DFIntDebugSimPrimalToleranceInv": "-2147483647",
        "FFlagDebugSimDefaultPrimalSolver": "True"
    }
```

### Dont Touch The Walls!!! 2

``` json
{
    "DFIntDebugSimPrimalPreconditionerMinExp": "20",
    "DFIntDebugSimPrimalWarmstartVelocity": "-101",
    "DFIntDebugSimPrimalPreconditioner": "1000",
    "DFIntDebugSimPrimalWarmstartForce": "1",
    "DFIntDebugSimPrimalNewtonIts": "4000",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalToleranceInv": "6",
    "DFIntDebugSimPrimalLineSearch": "1"
}
```
### omg i cant believe roblox is that dumb to do this...
###### why do i see this everywhere?

``` json
{
    "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
    "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
    "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
    "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
}
```
### Glossy thingy

``` json
{
    "DFIntRenderClampRoughnessMax": "-1000000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```
