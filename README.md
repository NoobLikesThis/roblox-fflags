# roblox-fflags
### fv cmon im catching up
![roblox-roblox-run](https://github.com/user-attachments/assets/abf178be-4911-4be9-b557-a2f06922fc75)

### less updates sometimes, working on diff fflag list.

### HELPING USERS WHO WANT HELP ON THEIR LIST, MAKE AN ISSUE AND ILL HELP.
### want to help this list? make an issue!
###### archive: https://github.com/NoobLikesThis/roblox-fflags/blob/65313f1c20988ea5d9aa87ad0ccf10acd456ac7d/new%20noclip%20by%20me
##### FFlagDebugSimDefaultPrimalSolver was patched months ago. It may be the new physics engine in a year or so but will probably never happen now.
##### if a fflag doesnt work, tell me with an issue.
###### if a fflag says smth abt a path, add a , after the fflag that doesnt work


## links

### [Dont join luafvs group!](https://www.roblox.com/groups/34911020/FIVE55/)

### [Join my group1!](https://www.roblox.com/groups/32479917/Hub-of-Dreams#!/)

### [roblox scripts](https://github.com/retpirato/Roblox-Scripts)

### [new dc link for fflags.](https://discord.gg/kS3nyQPZhU)

### [720p roblox](https://github.com/NoobLikesThis/changing-roblox-resolution/)

### [custom fflags tutorial](https://github.com/GoingCrazyDude/roblox-custom-textures/)

### [guy who can get random fflags i would need for the weird fflags](https://github.com/d44df016fe28bc8d5974/rbxflags)

### [channel tracker](https://github.com/bluepilledgreat/Roblox-DeployHistory-Tracker)

### [rlly cool man!?!?](https://github.com/returnrqt)

### [fflag tracker](https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/roblox/FVariables.txt)
#### If you want to find some exploitable fast flags yourself then you can search them yourself here (big thanks to maximum adhd for this, the best things to search for are things like Humanoid, Velocity, HipHeight, PGS, Render, Debug and nearly anything thats a FInt)

#### If you want to test how much you can glitch out stuff, then just use very high/low numbers for Integer values (the highest/lowest values possible: -2147483648, 2147483648)

### [fishstrap](https://github.com/returnrqt/bloxstrap/)

### [project urly](https://github.com/NoobLikesThis/Project-Urly)
###### a way to get early versions of bloxstrap + fishstrap

### [fflags folder for textures and other](https://www.mediafire.com/folder/7lkiidpn7fui9/Documents)
##### reinstall after done or save the old file and put that one in after you are done.
##### tip: turn your graphics level to 3 or higher or use quality level overide fflag and make 6 or higher:
###### max is 21, I recommend 14, use graphics quality 6 for the same without the fflag.
``` json
{
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```

### [fflags video (not mine)](https://www.youtube.com/watch?v=fj0zVi6UG9A)

## Physics
### Slide on Terrain/Meshes
##### @tyetonix
``` json
{
    "DFIntSmoothTerrainPhysicsRayAabbSlop": "-9999"
}
```
### improved
##### @tyetonix [@slowvariable](https://github.com/phoubia)
``` json
{
    "DFIntSmoothTerrainPhysicsRayAabbSlop": "-9999",
    "DFIntMaximumFreefallMoveTimeInTenths": "2147483648"
}
```
### Better serversided character position
##### 100 makes your serversided character closer to your client
``` json
{
    "DFIntS2PhysicsSenderRate": "100"
}
```
### teleport ragdolled bodies to 0,0,0
##### use in cart ride games for weird movement, r6 is better than r15.
##### use for anti fall, buggy.
##### This automatically teleports all ragdolled players limbs (except torso) to the games 0,0,0 (very unreliable, only drags your torso to the 0,0,0)
##### Default: Unknown

```Json
{
  "DFIntGameNetLocalSpaceMaxSendIndex": "100000"
}
```
### freeze clientsided
###### ctrl +f7
``` json
{
"GETOFFMYDMS": "pls?"
}
```
### fling people
###### worlds buggiest stuff ever
``` json
{
 "DFIntNewRunningBaseGravityReductionFactorHundredth": "1695"
 }
```
### anything you touch goes to heaven
###### Cameron56378 on github
###### s you aswell but very high
``` json
{
"DFIntDebugSimPrimalLineSearch": "5000",
"DFIntBulletContactBreakOrthogonalThresholdPercent": "1000000",
"DFIntDebugSimPrimalWarmstartVelocity": "10000",
"FFlagDebugSimDefaultPrimalSolver": "True",
"FFlagDebugSimPrimalGSLump": "True",
"FIntDebugSimPrimalGSLumpAlpha": "-1111",
"DFIntDebugSimPrimalStiffness": "30000",
"DFIntMinClientSimulationRadius": "2147000000",
"DFIntMinimalSimRadiusBuffer": "2147000000",
"DFIntMaxClientSimulationRadius": "2147000000"
}
```
### Spin 1

###### @bloodraven
###### spin + fly

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
### spin 2
###### depends on walkspeed
``` json
{
 "FFlagSimAdaptiveTimesteppingDefault2": "True",
 "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
 "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

### lil bro tweakin 
###### BUGGY   
###### how did i find this, the first recording ik is in april, i found this in septemeber. https://www.youtube.com/watch?v=rndx4CG-om8
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

### Client Simulation Radius
Sets your clients simulation radius ( as far as i know )

```Json
{
  "DFIntMaxClientSimulationRadius":10000,
  "DFIntMinClientSimulationRadius":10000
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
### Drive vehicles slowly
###### set to -1 for slowest, this fflag changes the physicsreal throttle (see physicsreal by pressing shift + f4
###### @tyetonix
```json
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
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
### fly
###### equip  a tool,  kinda controllable, by popbob(kezcn)
``` json
{
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartVelocity": "100",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
```
### mesh noclip (RARE)
##### hold tab and should work (sometimes it stops u from holding fully) from 99chelic99
``` json
{
    "DFIntMaxMissedWorldStepsRemembered": "1000",
    "DFIntBulletContactBreakOrthogonalThresholdPercent": "0"
}
```
### Upside Down while slowly being sent to heaven
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartForce": "1000",
    "DFIntDebugSimPrimalWarmstartVelocity": "50"
}
```
### slow walk + low gravity
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartVelocity": "50"
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
### noclip 2
###### Adjust the value so you don't fall through the ground
``` json
{
    "DFIntSimBroadPhasePairCountMax": "50"
}
```
### noclip 3
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalNewtonIts": "1"
}
```
### noclip 4
###### Adjust the value so you don't fall through the ground
``` json
{
    "DFIntAssemblyExtentsExpansionStudHundredth": "-50"
}
```
###  noclip 5
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalPreconditioner": "1",
    "DFIntDebugSimPrimalPreconditionerMinExp": "10"
}
```
### noclip 6
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FFlagDebugSimPrimalGSLump": "True",
    "FIntDebugSimPrimalGSLumpAlpha": "-1111"
}
```
### noclip 7
###### dont climb stairs, dont jump, buggy.
``` json
{
"DFIntDebugSimPrimalLineSearch": "1",
"DFIntDebugSimPrimalWarmstartVelocity": "102",
"DFIntDebugSimPrimalWarmstartForce": "25",
}
```
### noclip 8
###### dont jump and buggy a bit.
``` json
{
"DFIntDebugSimPrimalLineSearch": "1",
"DFIntDebugSimPrimalWarmstartVelocity": "102",
"DFIntDebugSimPrimalWarmstartForce": "50",
}
```

###  Noclip + Low Gravity + Fly (Weird Movement)
``` json
{
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartForce": "160",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
```
### weird movement old
``` json
{
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartVelocity": "100",
    "DFIntDebugSimPrimalStiffness": "-50",
    "DFIntDebugSimPrimalStiffnessMax": "-20",
    "DFIntDebugSimPrimalStiffnessMin": "-10",
    "FFlagDebugSimDefaultPrimalSolver": "True"
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
### backwards speedhax 2.0
###### buggy and uses noclip
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
  "DFIntDebugSimPrimalWarmstartForce": "-2200",
  "DFIntDebugSimPrimalWarmstartVelocity": "-950",
  "DFIntMaximumFreefallMoveTimeInTenths": "1000",
  "DFIntDebugSimPrimalStiffness": "0"
}
```
### backwards speedhax but faster
###### not buggy but uses noclip bc so fast (not that fast cmon)
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
  "DFIntDebugSimPrimalWarmstartForce": "-1250",
  "DFIntDebugSimPrimalWarmstartVelocity": "-550",
  "DFIntMaximumFreefallMoveTimeInTenths": "1000",
  "DFIntDebugSimPrimalStiffness": "0"
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
### Stick unanchored parts to you
##### - = up, + = down
###### flings you a bit
``` json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### slide on wall walks/hops
###### buggy. only works in a certain angle.
###### [video 1](https://streamable.com/3r9a5v) [video 2](https://streamable.com/6w0yv2)
``` json
{
    "DFIntMaximumFreefallMoveTimeInTenths": "2147483648"
}
```
### unanchored buggy movement
###### makes unanchored parts do weird things, like moving faster in fps.
###### [video 1](https://streamable.com/erj8tz) [video 2](https://streamable.com/c4j4sz) [video 3](https://streamable.com/lk6y7m) [video 4](https://streamable.com/i584o3)
``` json
{
    "DFIntBulletContactBreakOrthogonalThresholdPercent": "1000000"
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
### Low Gravity 2 Control on Parts Improvement
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalNewtonIts": "1",
    "DFIntDebugSimPrimalPreconditioner": "15",
    "DFIntDebugSimPrimalPreconditionerMinExp": "10",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-150",
    "DFIntDebugSimPrimalWarmstartVelocity": "100"
}
```
### Low Gravity 3
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FFlagDebugSimPrimalGSLump": "True",
    "FIntDebugSimPrimalGSLumpAlpha": "-1111"
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
### make players a bit shiny

``` json
{
    "DFIntRenderClampRoughnessMax": "-1000000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```


### Random High Jumps
``` json
    {
        "FFlagSimAdaptiveTimesteppingDefault2": "True",
        "DFFlagSimHumanoidTimestepModelUpdate": "True"
    }
```



### Possible Super Jump
``` json
    {
        "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
    }
```

### Adjust Hip Height Clamps

###### https://www.roblox.com/bundles/63/Mage-Animation-Package
``` json

    {
        "DFIntHipHeightClamp": "-48"
    }

```
### Hip Height

###### Very controllable bounce, only works with negative values, 0 allows you to hover
``` json
    {
        "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
    }
```
### Network Ownership

###### Better network ownership of parts. This might get you banned in some games with anticheats (Limbobbia)
``` json
    {
        "DFIntMinClientSimulationRadius": "2147000000",
        "DFIntMinimalSimRadiusBuffer": "2147000000",
        "DFIntMaxClientSimulationRadius": "2147000000"
    }
```
### fixed network ownership
###### better [network ownership](https://create.roblox.com/docs/physics/network-ownership) of parts
``` json
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000",
    "DFFlagDebugPhysicsSenderDoesNotShrinkSimRadius": "True",
    "FFlagDebugUseCustomSimRadius": "True"
}
```
### Freeze
``` json
    {
        "FFlagDebugSimDefaultPrimalSolver": "True",
        "DFIntDebugSimPrimalLineSearch": "0"
    }
```
### freeze 2
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalNewtonIts": "0"
}
```
### bouncy
``` json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntMaxAltitudePDStickHipHeightPercent": "-200",
    "DFIntDebugSimPrimalLineSearch": "1"
}
```
### bouncy v2
###### by a youtuber called erick yeah. https://www.youtube.com/@erickyeah0
``` json
{
"DFIntDebugSimPrimalLineSearch": "1",
"DFIntDebugSimPrimalWarmstartVelocity": "100",
"DFIntDebugSimPrimalWarmstartForce": "500",
}
```

### Drunk
``` json
    {
        "FFlagSimAdaptiveTimesteppingDefault2": "True",
        "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
        "DFFlagSimHumanoidTimestepModelUpdate": "True"
    }
```
### Tool Desyncs
``` json
    {
        "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
    }
```


### Speed 2
\[!NOTE\] **Not backwards but more buggy**
``` json
    {
        "DFIntDebugSimPrimalWarmstartForce": "-285",
        "DFIntDebugSimPrimalWarmstartVelocity": "750",
        "FIntDebugSimPrimalGSLumpAlpha": "-2147483647",
        "FFlagDebugSimDefaultPrimalSolver": "True",
        "DFIntDebugSimPrimalPreconditioner": "100",
        "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
        "DFIntDebugSimPrimalNewtonIts": "1",
        "DFIntDebugSimPrimalToleranceInv": "10",
        "DFFlagSimHumanoidTimestepModelUpdate": "True",
        "FFlagSimAdaptiveTimesteppingDefault2": "True",
        "DFIntDebugSimPrimalLineSearch": "100"
    }
```
### Hip Height modifier
###### This one is a percentage for smth
makes you go bounce, on 0 you float a little bit above the ground, always needs to be below zero for bouncing

```Json
{
  "DFIntMaxAltitudePDStickHipHeightPercent":-2147483648
}
```
### Desync FFlag
``` json
    {
        "DFFlagPhysicsSkipNonRealTimeHumanoidForceCalc2": "False",
        "DFIntS2PhysicsSenderRate": "3",
        "DFIntTaskSchedulerTargetFps": 5588562
    }
```
### Desnyc again
``` json
{
  "FFlagFixGraphicsQuality": "True",
  "DFIntTaskSchedulerTargetFps": "0",
  "DFIntS2PhysicsSenderRate": "1",
  "FIntPGSAngularDampingPermilPersecond": "0",
  "DFIntS2NumPhysicsPacketsPerStep": "2",
  "DFIntPhysicsSenderMaxBandwidthBps": "10",
  "DFIntPhysicsSenderMaxBandwidthBpsScaling": "10",
  "DFIntDataSenderRate": "2",
  "DFIntDataSenderMaxBandwidthBps": "555",
  "DFIntDataSenderMaxJoinBandwidthBps": "222",
  "DFIntDebugSimPhysicsSteppingMethodOverride": "777",
  "DFFlagPhysicsSkipNonRealTimeHumanoidForceCalc2": "False"
}
```
### Ultimate desync
``` json
{ "DFIntS2PhysicsSenderRate": "1", "FIntPGSAngularDampingPermilPersecond": "0" }
```
### Invisible 1

> \[!NOTE\] **Restricts the client from sending any physics-related
> information. This means other people can topple you over.**

``` json
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```
### Invisible 2

> \[!NOTE\] **Locks your character's position on the server to (0, 0,
> 0), having the side effect of turning you invisible. This only affects
> the server and other clients, not you. server-sided things that rely
> on your position, like clicking to get tools, will not function. In
> some games these can be abusable. Here is a list of them:
> [Link](https://github.com/luafv/rbxflags/blob/master/assets/lists/experiences/specific.md)**

``` json
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```
### Invisible 3

###### Stops the physics on your character froms sending to the server so your character doesn't move for the server. You can move on your client.
``` json
    {
        "DFIntS2PhysicsSenderRate": "-30"
    }
```
### Invisible 4

###### Restricts the client from sending any physics-related information. This means other people can topple you over.
``` json
    {
        "FFlagDebugSimDefaultPrimalSolver": "True",
        "DFFlagDebugSimPrimalFeedback": "True",
        "DFIntDebugSimPrimalStiffnessMax": "0",
        "DFIntDebugSimPrimalStiffnessMin": "0",
        "DFIntMaximumFreefallMoveTimeInTenths": "1000"
    }
```
### Invisible 5
###### Restricts the client from sending any physics-related information. This means other people can topple you over.
``` json
{
    "DFIntTaskSchedulerTargetFps": 360,
    "FFlagSimIslandizerManager": "false",
    "FFlagDebugSimIntegrationStabilityTesting": "True",
    "DFIntDebugSimPhysicsSteppingMethodOverride": "10000000",
    "DFIntS2PhysicsSenderRate": "10000000"
}
```
## Physics Slowdown
#### This fast flag sets the current physics "FPS", this slows down all the physics related stuff aka falling, walking. Change 1, 2, 3 and 4 for an effect, use 3 and with 60 fps for the best effect, use 4 with any fps lower than 45.
##### Default: 16

``` json
{
  "DFIntMaxMissedWorldStepsRemembered": "1"
}
```
## Active Physics FPS Change
#### Go into settings  and change your FPS to 240 (if you can reach that amount of FPS) and you will have full Physics speed, at 30 fps its around 7,5/s. Any Part you have network Ownershipship over is also slowed down, as well as shot projectiles.
###### note: these will do the same thing
``` json
{
  "FFlagGameBasicSettingsFramerateCap": "True",
  "DFIntTaskSchedulerTargetFps": "0",
  "DFIntMaxMissedWorldStepsRemembered": "1"
}
```

##### Games: any game (obbys are easier to do with slow Physics)

### warp
##### to warp, first walk and continue walking then hold the white window bar and untab.
``` json
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
```
### Wallglide
``` json
{
    "DFIntUnstickForceAttackInTenths": "-4"
}
```
### wallfling
``` json
{
"DFIntUnstickForceAttackInTenths": "-10000"
}
```
### fling yourself
###### there is a chance that you noclip through the map
```json
{
    "DFIntDebugSimPrimalLineSearch": "1",
    "DFIntDebugSimPrimalWarmstartForce": "160",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
```

### real hitbox 🤑
``` json
{
	"FFlagHumanoidParallelFixTickleFloor2": "true",
	"FFlagFixMemoryPriorizationCrash": "True",
	"FIntUGCValidationTorsoThresholdFront": "100",
	"FIntUGCValidationTorsoThresholdSide": "100",
	"FIntUGCValidationTorsoThresholdBack": "100",
	"FIntUGCValidationLeftArmThresholdBack": "23",
	"FIntUGCValidationLeftArmThresholdFront": "25",
	"FIntUGCValidationLeftArmThresholdSide": "40",
	"FIntUGCValidationLeftLegThresholdBack": "40",
	"FIntUGCValidationLeftLegThresholdFront": "40",
	"FIntUGCValidationLeftLegThresholdSide": "36",
	"FIntUGCValidationRightArmThresholdBack": "23",
	"FIntUGCValidationRightArmThresholdFront": "25",
	"FIntUGCValidationRightArmThresholdSide": "40",
	"FIntUGCValidationRightLegThresholdBack": "40",
	"FIntUGCValidationRightLegThresholdFront": "40",
	"FIntUGCValidationRightLegThresholdSide": "38"
}
```
### Remap R6 to R15 Rigs/Weird Movement
```json
{
    "FFlagRemapAnimationR6ToR15Rig": "True"
}
```
### Weird Leg Movement
``` json

    {
        "DFFlagAnimatorPostProcessIK": "True"
    }
```
### delay animations
###### client
``` json
{
    "FFlagProcessAnimationLooped": "False"
}
```
### No Animations
###### Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client
``` json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Disable other players animations (Clientsided)
``` json
{
  "FFlagProcessAnimationLooped":"False",
  "FFlagReplicateAnimationLooped":"False"
}
```
### Limits number of animations being played
##### 0 removes most player animations, 1-5 removes the walk animation after jumping
``` json
{
    "DFIntMaxActiveAnimationTracks": "0"
}
```
# idk where to put
### faster preloading
``` json
{
    "DFIntNumAssetsMaxToPreload": "9999999",
    "DFIntAssetPreloading": "9999999"
}
```
### Limits light updates
```json
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
```
### Disables fade in and fade out animation every light update
```json
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```
### Disable In-game Advertisements
```json
{
    "FFlagAdServiceEnabled": "False"
}
```
### Disable Telemetry 
```json
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True",
    "FStringTencentAuthPath": "null"
}
```
### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```
### MTU 
```json
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
```
### Disable Shadows
###### @Uvoltan 
```json
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647"
}
```
### Preserve rendering quality with display setting
```json
{
    "DFFlagDisableDPIScale": "True"
}
```
### reduce avatar item particles in first person
``` json
{
    "FFlagUserHideCharacterParticlesInFirstPerson": "True"
}
```
### Maximum Threads
```json
{
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```
### Minimum Threads
```json
{
    "FIntTaskSchedulerThreadMin": "3"
}
```
### Smoother Terrain
```json
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
```
### Force Graphics Quality Level
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```
### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```
### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```json
{
    "DFIntMaxFrameBufferSize": "4"
}
```
### 5 decimal digits limit for camera sensitivity
###### basically like idk 8 months ago roblox added a 3 decimal digits limit, some people that I know used those extra digits
```json
{
    "FFlagFixSensitivityTextPrecision": "False"
}
```
### Disable voicechat
###### Setting this to True will not do anything 
###### [TIP] Use PlaceFilter for specific games
```json
{
    "DFFlagVoiceChat4": "False"
}
```
### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```json
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```
### Automatically unmutes your mic on join (VC)
```json
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
```
### opt-out Experience Language
###### Removes the Experience Language option in settings
```json
{
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```
### Lets you change the zoom out limit
###### Only applies to games that haven't changed the default zoom limit
```json
{
    "FIntCameraMaxZoomDistance": "9999"
}
```
### Exclusive Fullscreen
```json
{
    "FFlagHandleAltEnterFullscreenManually": "False"
}
```
### Remove layered clothing related for searching in lua app catalog
###### From: https://discord.gg/nKjV3mGq6R
```json
{
    "FStringAXCategories": "ClassicShirts.ClassicTShirts.ClassicPants"
}
```

### bypass group id gui hiding (idk)
``` json
{
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True"
}
```
### verified badge on u 
###### client sided
``` json
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```
### verifed  badge on everyone
###### client sided aswell
``` json
{
    "FFlagOverridePlayerVerifiedBadge": "True"
}
```

### Disable Touch Events
```json
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```
### quick game launch
###### may cause bugs
``` json
{
    "FFlagEnableQuickGameLaunch": "True"
}
```
### remove fullscreen title bar
``` json
{
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### remove translated supported message on join
``` json
{
    "FFlagChatTranslationEnableSystemMessage": false
}
```
### force MSAA
###### values are 0, 1, 2, 4 and 8. values over 4 may cause viewport bugs
``` json
{
    "FIntDebugForceMSAASamples": "4"
}
```
### new camera mode
``` json
{
    "FFlagNewCameraControls": "True"
}
```
### Always display Render Stats
###### pretty self explanatory fflag, you can't disable them using the hotkey
```json
{
    "FFlagDebugAlwaysDisplayRenderStats": "true"
}
```
### New Report Menu
```json
{
    "FStringSelectInSceneReportMenuOverrideUserIds": "UserID"
}
```
### remove unnecessary kicks
###### removes being kicked for being afk
``` json
{
    "DFFlagDebugDisableTimeoutDisconnect": "True"
}
```
### N/A
###### causes memory leaks
``` json
    {
        "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
        "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
        "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
        "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
    }
```
### Chrome UI First Time User Experience
``` json
{
    "FFlagEnableChromeFTUX": "True"
}
```
### Hide playerlist close button on Chrome UI
``` json
{
    "FFlagDisablePlayerListDisplayCloseBtn": "True"
}
```
### Pin Chat on Chrome UI
``` json
{
    "FFlagEnableChromePinnedChat": "True"
}
```
### Chrome UI TopBar
``` json
{
    "FFlagEnableReportAbuseMenuRoactABTest2": "True",
    "FFlagEnableInGameMenuChromeABTest2": "True",
    "FFlagEnableInGameMenuChromeABTest3": "True"
}
```
### do not disturb
``` json
{
    "FFlagToastNotificationsProtocolEnabled2": "False"
}
```
### Chrome UI Topbar Removal
``` json
{
  "FFlagEnableInGameMenuChromeABTest2": "False",
  "FFlagChromeBackwardsSignalAPI": "False",
  "FFlagInGameMenuChrome": "False",
  "FFlagEnableInGameMenuChrome": "False",
  "FFlagEnableInGameMenuChromeABTest3": "False",
  "FFlagEnableReportAbuseMenuRoact2": "False",
  "FFlagEnableReportAbuseMenuRoactABTest": "False",
  "FFlagEnableInGameMenuChromeABTest4": "False",
  "FFlagChromeBetaFeature": "False",
  "FFlagEnableInGameMenuControls": "False",
  "FFlagEnableInGameMenuModernization": "False",
  "FFlagEnableMenuControlsABTest": "False",
  "FFlagEnableMenuModernizationABTest": "False",
  "FFlagEnableMenuModernizationABTest2": "False",
  "FFlagEnableV3MenuABTest3": "False",
  "FFlagFixReportButtonCutOff": "False",
  "FIntNewInGameMenuPercentRollout3": "0"
}
```
### disable burger icon
###### removes the 2015 3 lines icon from chrome ui and reverts it to the 9 dots square
```json
{
    "FFlagEnableHamburgerIcon": "True"
    "FFlagEnableHamburgerIcon": "False"
}
```
### Stop the Chinese from spying on you
``` json
{
    "FStringTencentAuthPath": "null"
}
```
### roblox shaders
##### false = old true  = new
``` json
{
    "FFlagShaderLightingRefactor": "true"
}
```
### better ping??
``` json
{
    "DFIntTrackCountryRegionAPIHundredthsPercent": "10000"
}
```
### better vulkan
``` json
{
    "FFlagDebugGraphicsDisableVulkan": "False",
    "FFlagDebugGraphicsDisableVulkan11": "False",
    "FFlagDebugVulkanDisablePreRotate": "False",
    "FFlagGraphicsVulkanBonusMemory": "True",
    "FFlagRenderEnableGlobalInstancingVulkan": "True"
}
```
### Multi Try On
###### Allows you to try on multiple things in the catalog and buy everything at once
###### some accessories in the same category cannot be tried on at the same time
```json
{
   "FFlagAXEnableMultiTryOnUI": "True"
}
```
### No opacity to Chrome UI
##### So when this fflag is set to false when you change the background transparency in the esc menu it won't affect the small 3 buttons of chrome ui and will keep them semi-transparent
##### the bg transparency set to opaque and the fflag is true and one on the right is bg transparency set to opaque and the fflag is false
##### found by satlybpro (708463225578192968) in Bloxstrap stuff
``` json
{
    "FFlagChromeUsePreferredTransparency": "False"
}
```
### Extra + left healthbar for chrome ui Topbar
``` json
{
    "FFlagEnableUnibarMaxDefaultOpen": "True",
    "FFlagUpdateHealthBar": "False",
    "FFlagUseNewPinIcon": "False"
}
```
#### Revert the new chrome ui to the old one
``` json
{
    "FFlagEnableHamburgerIcon": "False",
    "FFlagEnableUnibarV4IA": "False",
    "FFlagEnableAlwaysOpenUnibar2": "False",
    "FFlagUseNewUnibarIcon": "False",
    "FFlagUseSelfieViewFlatIcon": "False",
    "FFlagUnibarRespawn": "False",
    "FFlagEnableChromePinIntegrations2": "False"
}
```
### cleaner desktop home page
##### Tho it wont remove the Recommended for you and Sponsored sections but it will remove the Recommended section (the insanely long one)
``` json
{
    "FIntGameGridFlexFeedItemTileNumPerFeed": "0"
}
```
### Preferred text size scale
##### enables a font scaler in the escape menu
##### found by Sky (364112742153584640) in Bloxstrap stuff
``` json
{
     "FFlagEnablePreferredTextSizeScale": "True",
     "FFlagEnablePreferredTextSizeSettingInMenus2": "True"
}
```
### Enable Better Haptics
``` json
{
    "FFlagEnableBetterHapticsResultHandling": "True"
}
```
### Better Trackpad Scrolling
``` json
{
    "FFlagBetterTrackpadScrolling": "True"
}
```

### Thick healthbar
###### Disabling it will completly remove the healthbar
``` json
{
    "FFlagUpdateHealthBar": "True"
}
```
### Fix broken health bar
``` json
{
    "FFlagEnableAlwaysOpenUnibar2": "False"
}
```
### red font
###### You need to use Default Roblox Font to activate this. Also it can be glitchy in the settings menu
```json
{
    "FStringDebugHighlightSpecificFont": "rbxasset://fonts/families/BuilderSans.json"
}
```
### V2 Menu
###### enables the 2020 sidebar menu
```json
{
    "FIntNewInGameMenuPercentRollout3": "100",
    "FFlagEnableInGameMenuControls": "False",
    "FFlagDisableNewIGMinDUA": "True",
    "FFlagEnableInGameMenuChromeABTest4": "False"
}
```
### Fix the 2015 escape menu
``` json
{
    "FFlagFixReportButtonCutOff": "False"
}
```
### Reset Character instead of Respawn in Experience Menu
``` json
{
    "FFlagInExperienceMenuResetButtonTextToRespawn": "False"
}
```
### Enable Highlight Outlines on any Rendering API
``` json
{
    "FFlagHighlightOutlinesOnMobile": "True"
}
```
### 00
``` json
{
    "FFlagAppChatAddConnectUnibarForActiveSquad": "False"
}
```
### Reshuffle Party Icons
``` json
{
    "FFlagReshufflePartyIconsInUnibar": "False"
}
```
### Rename Party 2 Roblox Chat
``` json
{
    "FFlagAppChatRebrandStringUpdates": "False"
}
```
### Disable Avatar Chat
``` json
{
    "FFlagAvatarChatServiceEnabled3": "False"
}
```
### Break Collectible Icon
``` json
{
    "FFlagDisplayCollectiblesIcon": "False"
}
```
### Break Top Bar Menu
``` json
{
    "FStringNewInGameMenuForceds": "UserID",
    "FFlagEnableInGameMenuChrome": "True"
}
```
### Dont Render Screen GUIs
``` json
{
    "FFlagDebugDontRenderScreenGui": "True"
}
```
### No Transparency V4 Menu (2023)
``` json
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```
### Overlay that shows what you type
``` json
{
    "FFlagDebugTextBoxServiceShowOverlay": "True"
}
```
### Ammount of lines to show at once for above
``` json
{
    "DFIntTextBoxServiceHistorySize": "1"
}
```
### Hides gui
``` json
{
    "FFlagDebugAdornsDisabled":  "True"
}
```
### Disable Camera & Selfview
``` json
{
    "FFlagSelfieViewEnabled": "True"
}
```
### Disable Bubble Chat
``` json
{
    "FFlagEnableBubbleChatFromChatService": "False"
}
```
### Disable Autocomplete
``` json
{
    "FFlagEnableCommandAutocomplete": "False"
}
```
### ShadowMap Bias
##### Future & ShadowMap only
``` json
{
    "FIntRenderShadowmapBias": "75"
}
```
### Simulation Optimization Flag
##### Optimization, latency, delay FFlag
``` json
{
   "FFlagSimEnableDCD16": "true"
}
```
### Unified Lighting Blend Zone
##### Smaller value = FPS boost > Bigger value = FPS loss
##### Explanation:
##### Controls the distance over which light transitions blend.
##### Lower values create sharper transitions.
##### Higher values make transitions smoother.
``` json
{
     "FIntUnifiedLightingBlendZone": 400
}
```
### Disable In-Game Purchases
##### gives an error when you try and buy something.
``` json
{
    "DFFlagOrder66": "True"
}
```
### Vertex Smoothing Group Tolerance
##### The FIntVertexSmoothingGroupTolerance flag controls the tolerance level for vertex smoothing groups in 3D graphics.
##### Lower values result in lower smoothing quality as more errors are tolerated, making models appear more angular and less smooth.
##### Higher values increase the smoothing accuracy, leading to smoother, more visually appealing models with fewer artifacts.
``` json
{
    "FIntVertexSmoothingGroupTolerance": "1000"
}
```
### Object Reflection Support!
``` json
{
    "FFlagObjectReflectionSupport": "true"
}
```
### Better shadows
##### Loading will take longer but the shadows are much better
``` json
{
    "FFlagRenderInitShadowmaps": "true"
}
```
### Mini webview
``` json
{
    "FFlagWebViewProtocol": "False"
}
```
### Disable Haptics Option
``` json
{
    "FFlagAddHapticsToggle": "False"
}
```
### Raycast Performance Improvements
##### tip: Uses workspace:Raycast() instead of worldmodel:FindPartOnRayWithIgnoreList()
``` json
{
    "FFlagUserRaycastPerformanceImprovements": "true"
}
```
### Render Occlusion Culling
##### [@CloneTrooper1019](https://x.com/MaximumADHD/status/1832331711486865769)
``` json
{
    "DFFlagUseVisBugChecks": "True",
    "FFlagEnableVisBugChecks27": "True",
    "FFlagVisBugChecksThreadYield": "True",
    "FIntEnableVisBugChecksHundredthPercent27": "100"
}
```
### Remove Unrequired Connections
##### Disconnects unrequired connections, better memory usage
``` json
{
    "FFlagUserUpdateInputConnections": "true"
}
```
### Walk Speed Scale Based
##### Taller characters have a slower walking animation.
``` json
{
    "DFFlagUserAnimateScaleRun ": "true"
}
```
### V1 Menu Fix
``` json
{
    "FFlagSettingsHubIndependentBackgroundVisibility": "True",
    "FFlagFixReportButtonCutOff": "False"
}
```
### stop screaming bro
``` json
{
    "FIntDebugTextElongationFactor": "6785"
}
```
### Removes the new ingame chrome chat button
###### if you use v1 menu, this reverts the chat icon to the old one
###### @kezcn
```json
{
    "FFlagAppChatInExperienceEnabledV647new": "False"
}
```
### V2 Menu
``` json
{
    "FIntNewInGameMenuPercentRollout3": "1000"
}
```
### Disable Profile Picture Customization
``` json
{
     "FFlagAXDefaultAvatarToShopEnabled3": "False"
}
```
### Preferred Text Size Settings (new)
``` json
{
  "FFlagEnablePreferredTextSizeGuiService": true,
  "FFlagEnablePreferredTextSizeScale": true,
  "FFlagEnablePreferredTextSizeScalePerLayerCollector": true,
  "FFlagEnablePreferredTextSizeSettingInMenus2": true,
  "FFlagEnablePreferredTextSizeStyleFixesInCaptureMenu": true,
  "FFlagEnablePreferredTextSizeStyleFixesInExperienceMenu": true,
  "FFlagEnablePreferredTextSizeStyleFixesInPlayerList": true,
  "FFlagPreferredTextSizeSettingBetaFeature": true,
  "FIntPreferredTextSizeSettingBetaFeatureRolloutPercent": 100,
  "FFlagEnablePreferredTextSizeConnection": true,
  "FFlagEnablePreferredTextSizeStyleFixesAddFriends": true,
  "FFlagEnablePreferredTextSizeStyleFixesGameTile": true,
  "FFlagEnablePreferredTextSizeStyleFixesInAppShell3": true,
  "FFlagEnablePreferredTextSizeStyleFixesInPurchasePrompt": true,
  "FFlagEnablePreferredTextSizeStyleFixesInReportMenu": true
}
```
### Keyboard Latency
##### Default value: 500 > > Lower value = more responsive keyboard.
##### This flag controls the keyboard input latency in milliseconds.By setting this value to 1, it minimizes the delay between key presses and the game's recognition of the input, effectively improving keyboard responsiveness. However, such a low value might cause excessively frequent key registration, which can lead to issues like repeated actions during key holds. The default value is 500 milliseconds, providing a balance between input responsiveness and preventing unintentional key repetition.
``` json
{
  "FIntActivatedCountTimerMSKeyboard": 500
}
```
### Mouse Latency
##### Default value: 500 > > Lower value = more responsive mouse
##### This flag determines the mouse input delay in milliseconds. A lower value (such as 1) will reduce the latency between mouse movement or clicks and the game's response, making the mouse feel more responsive. However, setting the value too low could result in excessively sensitive mouse input, potentially leading to issues like unintended multiple clicks or overly sensitive pointer movements. The default value of 500 milliseconds provides a balance between responsiveness and control, reducing the risk of input errors.
``` json
{
  "FIntActivatedCountTimerMSMouse": 500
}
```
### Shoe Skip Render Mesh
##### skips shoe rendering
``` json
{
  "FFlagShoeSkipRenderMesh": "false"
}
```
### Render Skip Reading Shader Data
##### Skips reading shader data
``` json
{
  "FFlagRenderSkipReadingShaderData": "false"
}
```
### Render Shadow Skip Huge Culling
##### Skipping shadows of large objects in the distance
``` json
{
  "FFlagRenderShadowSkipHugeCulling": "true"
}
```
### Smoother/Faster Input
##### Tip: When enabled the game will use an updated implementation for processing user input, which may lead to smoother and more responsive interactions. This flag controls the refactoring of the legacy input handling system in Roblox.
##### Recommendation: Test your game thoroughly after enabling this flag to ensure that everything functions as expected.
``` json
{
    "FFlagLuaAppLegacyInputSettingRefactor": true
}
```
### Move Pre-Render Phase [~25% Performance Boost]
###### This FastFlag moves the Pre-Render task to an off thread after all other tasks are completed. By default, Pre-Render runs first, forcing the render thread to wait until the Pre-Render process finishes before it can start rendering a frame.
###### With this FastFlag enabled, Pre-Renderer is executed while the main thread is processing the previous frame. This adjustment allows the main thread to proceed without waiting for Pre-Renderer, leading to increased framerates at the expense of some frame latency.
###### This flag is most effective in CPU-bound scenarios.
###### This fflag might cause issues
###### @blobanium
```json
{
    "FFlagMovePrerender": "True"
}
```
### New Version of Render
##### Enables an updated rendering system to improve performance and manage render calls.
``` json
{
  "FFlagRenderCBRefactor2": true
}
```
### Directional Attenuation Max Points
##### Tip: Lower values: May improve performance but reduce lighting accuracy. > Higher values: Increase lighting accuracy at the cost of performance, potentially leading to slower rendering, especially in scenes with complex lighting setups.
##### Explanation:
##### Limits the maximum number of sample points for calculating directional light attenuation..
##### Lower values improve performance but may reduce lighting accuracy.
##### Higher values increase lighting accuracy but may slow rendering in complex lighting setups.
``` json
{
   "FIntDirectionalAttenuationMaxPoints": "400"
}
```
### Simulation Optimization Flag
##### Be mindful that while optimization can improve performance, it may also require testing to ensure that the behavior of sets remains consistent and that no necessary details are lost during the optimization process. The DFFlagSimOptimizeSetSize flag is used to optimize the size of sets in simulations. Enabling this flag activates optimization techniques that reduce the size of simulation sets, leading to better performance by decreasing memory usage and potentially improving processing speeds during simulations.
``` json
{
  "DFFlagSimOptimizeSetSize": true
}
```
### Old Version of FRM
##### Graphics quality will use an older approach/method which may help improve FPS for some users.
##### true = new
``` json
{   
   "FFlagFRMRefactor": "false"
}
```
### old luaapp chat button
``` json
{
    "FStringNewChatTabExperimentLayerValue": "2024MUSIC"
}
```
``` json
{
    "FFlagEnableNewChatTabExperiment5": "False"
}
```
# textures
### No Textures
``` json
{
          "FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
          "FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
          "FStringTerrainMaterialTable2022": "",
          "FStringTerrainMaterialTablePre2022": "",
          "FFlagMSRefactor5": "False"
}
```
### Black Textures
``` json
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\u0022color\u0022:[55, 55, 55, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\u0022color\u0022:[55, 55, 55, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]}}",
    "FFlagMSRefactor5": "False"
}
```
### White Textures
``` json
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\u0022color\u0022:[255, 255, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\u0022color\u0022:[255, 255, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]}}",
    "FFlagMSRefactor5" :"False"
}
```

### Minecraft Textures
``` json
{
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://9873266399\",\"rbxassetid://9438410239\"],\"color\":[238,238,238,255]},\"asphalt\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[227,227,228,234]},\"basalt\":{\"ids\":[\"rbxassetid://11545552824\",\"rbxassetid://11545440462\"],\"color\":[160,160,158,238]},\"brick\":{\"ids\":[\"rbxassetid://9924770651\",\"rbxassetid://9924770538\"],\"color\":[229,214,205,227]},\"cobblestone\":{\"ids\":[\"rbxassetid://9919719550\",\"rbxassetid://9438453972\"],\"color\":[218,219,219,243]},\"concrete\":{\"ids\":[\"rbxassetid://9924775913\",\"rbxassetid://9924775826\"],\"color\":[225,225,224,255]},\"crackedlava\":{\"ids\":[\"rbxassetid://9920485426\",\"rbxassetid://9438453972\"],\"color\":[76,79,81,156]},\"diamondplate\":{\"ids\":[\"rbxassetid://10237721036\",\"rbxassetid://9438453972\"],\"color\":[210,210,210,255]},\"fabric\":{\"ids\":[\"rbxassetid://9920517963\",\"rbxassetid://9438453972\"],\"color\":[221,221,221,255]},\"glacier\":{\"ids\":[\"rbxassetid://9920518995\",\"rbxassetid://9438453972\"],\"color\":[225,229,229,243]},\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://9920550720\",\"rbxassetid://9438453972\"],\"color\":[210,206,200,255]},\"grass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[196,196,189,241]},\"ground\":{\"ids\":[\"rbxassetid://11546360009\",\"rbxassetid://11545533676\"],\"color\":[165,165,160,240]},\"ice\":{\"ids\":[\"rbxassetid://9920556429\",\"rbxassetid://9438453972\"],\"color\":[235,239,241,248]},\"leafygrass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[182,178,175,234]},\"limestone\":{\"ids\":[\"rbxassetid://9920561624\",\"rbxassetid://9438453972\"],\"color\":[250,248,243,250]},\"marble\":{\"ids\":[\"rbxassetid://9873292869\",\"rbxassetid://9438453972\"],\"color\":[181,183,193,249]},\"metal\":{\"ids\":[\"rbxassetid://11546526557\",\"rbxassetid://11546431794\"],\"color\":[226,226,226,255]},\"mud\":{\"ids\":[\"rbxassetid://9920578676\",\"rbxassetid://9438453972\"],\"color\":[193,192,193,252]},\"pavement\":{\"ids\":[\"rbxassetid://11546539560\",\"rbxassetid://11546440685\"],\"color\":[218,218,219,236]},\"pebble\":{\"ids\":[\"rbxassetid://9920581197\",\"rbxassetid://9438453972\"],\"color\":[204,203,201,234]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://9868015012\"],\"color\":[255,255,255,255]},\"rock\":{\"ids\":[\"rbxassetid://11546570730\",\"rbxassetid://11546456858\"],\"color\":[211,211,210,248]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://11545623165\",\"rbxassetid://11545476330\"],\"color\":[206,177,163,180]},\"salt\":{\"ids\":[\"rbxassetid://9920590478\",\"rbxassetid://9438453972\"],\"color\":[249,249,249,255]},\"sand\":{\"ids\":[\"rbxassetid://11546588111\",\"rbxassetid://11546468464\"],\"color\":[218,216,210,240]},\"sandstone\":{\"ids\":[\"rbxassetid://9920596353\",\"rbxassetid://9438453972\"],\"color\":[241,234,230,246]},\"slate\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[235,234,235,254]},\"snow\":{\"ids\":[\"rbxassetid://11536062048\",\"rbxassetid://11108916253\"],\"color\":[239,240,240,255]},\"wood\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[217,209,208,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[207,208,206,254]}}",
    "FFlagMSRefactor5": "False"
}
```
### Trollface Textures
``` json
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[238,238,238,255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[227,227,228,234]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[160,160,158,238]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[229,214,205,227]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,219,219,243]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,225,224,255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[76,79,81,156]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,210,210,255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[221,221,221,255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,229,229,243]},\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,206,200,255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[196,196,189,241]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[165,165,160,240]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,239,241,248]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[182,178,175,234]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[250,248,243,250]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[181,183,193,249]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[226,226,226,255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[193,192,193,252]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,218,219,236]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[204,203,201,234]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://9475422736\u0022],\u0022color\u0022:[255,255,255,255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[211,211,210,248]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[206,177,163,180]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[249,249,249,255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,216,210,240]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[241,234,230,246]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,234,235,254]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[239,240,240,255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[217,209,208,255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[207,208,206,254]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[238,238,238,255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[227,227,228,234]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[160,160,158,238]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[229,214,205,227]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,219,219,243]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,225,224,255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[76,79,81,156]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,210,210,255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[221,221,221,255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,229,229,243]},\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,206,200,255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[196,196,189,241]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[165,165,160,240]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,239,241,248]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[182,178,175,234]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[250,248,243,250]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[181,183,193,249]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[226,226,226,255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[193,192,193,252]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,218,219,236]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[204,203,201,234]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://9475422736\u0022],\u0022color\u0022:[255,255,255,255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[211,211,210,248]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[206,177,163,180]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[249,249,249,255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,216,210,240]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[241,234,230,246]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,234,235,254]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[239,240,240,255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[217,209,208,255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[207,208,206,254]}}",
    "FFlagMSRefactor5": "False"
}
```
### dark map/textures
``` json
{
"DFIntTaskSchedulerTargetFps": 5588562,
"FFlagDebugSkyGray": true,
"FFlagMSRefactor5": false,
"FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"asphalt\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"basalt\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"brick\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"cobblestone\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"concrete\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"crackedlava\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"diamondplate\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"fabric\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"glacier\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"glass\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"granite\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"grass\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"ground\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"ice\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"leafygrass\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"limestone\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"marble\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"metal\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"mud\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"pavement\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"pebble\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"rock\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9439557520\"],\"color\":[0,0,0]},\"salt\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"sand\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"sandstone\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"slate\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9439613006\"],\"color\":[0,0,0]},\"snow\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"wood\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9439649548\"],\"color\":[0,0,0]},\"woodplanks\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]}}"
}
```
# Visuals ig
### semi fullbright
``` json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True"
}
```
### fullbright 1
###### use in games with massive or games with lots of clouds, make sure the game is daytime or has daytime.
###### fullbright 1 and 2 will let you noclip a bit inside a wall, be-aware.
###### tip: change the DFIntDebugFRMQualityLevelOverride fflag to 0 when you dont want quality 1 and wanna change it in game, best to hide ur fullbright while someone is watching.
``` json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagRenderFixFog": "True",
    "FFlagDisablePostFx": "True"
}
```
### fullbright 2
###### use in games with massive or games with lots of clouds, make sure the game is daytime or has daytime.
###### same stuff needed as fullbright but its better, fullbright 1 and 2 will let you noclip a bit inside a wall, be-aware.
##### tip: change the DFIntDebugFRMQualityLevelOverride fflag to 0 when you dont want quality 1 and wanna change it in game, best to hide ur fullbright while someone is watching.
##### tip: for expirenced people, add opengl and remove ur old rendering mode, remove the shaders with a fflag for less shadows.
##### fflags in fflags folder, random fflags 2.

``` json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FIntRenderShadowIntensity": "0",
    "FFlagRenderFixFog": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagRenderNoLowFrmBloom": "false",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "FIntBloomFrmCutoff": "1654515",
    "DFFlagDebugPauseVoxelizer": "True",
    "FFlagNewLightAttenuation": "True",
    "FFlagFRMRefactor": "false",
    "FFlagDisablePostFx": "True"
}
```
### Change the Layered Clothing deform Limit
###### The changes are only clientsided. When you set it to the (positive) signed 32 bit integer Limit (2147483647), then you can create really large Clothing combinations.  All deformations are disabled when put to a low value. The check dimension flag and check max cage dist are needed for this to work.
```Json
{
  "DFFlagCheckMaxCageDistance":"False",
  "FFlagLCCheckCageDimensions":"False",
  "DFIntLCCageDeformLimit":"2147483647"
}
```
### unifed lighing
``` json
{
    "FFlagRenderUnifiedLighting10": "True",
    "FFlagUnifiedLightingBetaFeature": "True"
}
```
### Capture posts
###### twitter but roblox edition
```
{
    "FFlagCapturesPostEnabledForAll_v4": "true"
}
```
### white everything
###### by [new guy](https://github.com/Storm99999)
``` json
  "FFlagSkyUseRGBEEncoding": "True",
```
### white sky
###### by [new guy](https://github.com/Storm99999)
``` json
  "FFlagSkyUseRGBEEncoding": "True",
  "FFlagDebugSkyGray": "True",
```
### grey sky
##### i thought that you guys wanted it
``` json
{
    "FFlagDebugSkyGray": "True",
}
```
### black sky
##### buggy.
###### i def dont have to put credits
``` json
{
    "FFlagDebugSkyGray": true,
    "FIntCameraFarZPlane": 600
}
```
### black wall
##### buggy.
###### i def dont have to put credits
``` json
{
    "FIntCameraFarZPlane": "60",
}
```
### Speed up particle emitters
``` json
{
  "FFlagDebugDeterministicParticles":"True"
}
```
### Crash all CoreGui scripts
###### Won't let the game load your core gui. Resets the seasonal quests in Blade Ball
```Json
{
  "FFlagFFlagLogAllGuacRead":"True"
}
```
### Simple coregui settings
```json
{
    "FFlagRefactorInExpGameSettings2": "True"
}
```
### disable postfx
``` json
{
    "FFlagDisablePostFx": "True"
}
```
### Low Quallity Terrain Textures
###### 4 for less quality 16, 32, 64 for higher quality
```json
{
    "FIntTerrainArraySliceSize": "4"
}
```
### High Quality Textures 
###### *[1-3]*
```json
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
```
### Lower Quality Textures 
###### *[1-3]*
```json
{
    "DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
```
### Dev Console Logging
###### Changes how long a Message can be, doesn't give you the ability to exceed the 16k Message Length Limit
```Json
{
  "FIntStandardOutputMaximumCharacterLength":"1"
}
```
### No more highlights
###### Stops all highlights from rendering.
```Json
{
  "DFFlagRenderHighlightManagerPrepare":"True"
}
```
### fully dark map
``` json
{
  "DFIntDebugFRMQualityLevelOverride": "1"
  "DFIntRenderClampRoughnessMax": "-640000000",
  "DFIntRenderClampRoughnessMin": "-640000000"
}
```
### No avatar textures
```json
{
    "DFIntTextureCompositorActiveJobs": "0"
}
```
### Texture Manager

###### 1-4 Blurry, 5-7 low quality also removes studs, 8 Removes almost everything, use 8 for "no textures" in any game
###### [rivals video](https://www.youtube.com/watch?v=nv4jD1sdmWE)
```json
{
    "FIntDebugTextureManagerSkipMips": "-1"
}
```
### remove sky/clouds
``` json
{
    "FFlagRenderNoLowFrmBloom": "false",
    "FFlagFRMRefactor": "false"
}
```
### remove bloom
``` json
{
  "FIntBloomFrmCutoff":"1654515",
  "FFlagRenderNoLowFrmBloom":"True"
}
```
### quality level override
###### use 1-21
``` json
{
    "DFIntDebugFRMQualityLevelOverride": "2"
}
```
### frm levels
```
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```
### failsafehumanoid
###### grey avatars
``` json
{
    "FFlagFailsafeHumanoid_3": "True"
}
```
### HyperThreading
``` json
{
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True"
}
```
### Makes stuff slightly brighter
``` json
{
    "FFlagRenderFixFog": "True"
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
### Stuttery Animation Fix
``` json

    {
        "DFIntTimestepArbiterThresholdCFLThou": "300"
    }
```
### darker dark mode?
``` json
{
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True"
}
```
### Max Raycast Distance
###### Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
###### Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3
```json
{
    "DFIntRaycastMaxDistance": "3"
}
```
### Applies cool colors to stuff
``` json
{
"FFlagDebugDisplayUnthemedInstances": "True"
}
```
### Rename "Charts" back to "Discovery"
``` json
{
    "FFlagLuaAppChartsPageRenameIXP": false
}
```
### Disable Ads
``` json
{
    "FFlagAdServiceEnabled": false
}
```
### Stuttery Animation Fix
``` json
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
```
### lower render distance
###### Only works on games which turned StreamingEnabled on.
``` json
{
    "DFIntDebugRestrictGCDistance": "1"
}
```
### no grass :D
###### best for gamers
``` json
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0"
}
```

### Increased Grass Motion & No Grass Motion
###### best for non gamers to touch grass
```json
{
    "FIntGrassMovementReducedMotionFactor": 999
}
```
```json
{
    "FIntGrassMovementReducedMotionFactor": 0
}
```
### Remove head roll limit for face tracking
###### server sided???
``` json
{
    "DFIntAvatarFaceChatHeadRollLimitDegrees": "360"
}
```
### Enable GPULightCulling
###### use with lighting attenuation for better vision
``` json
{
    "FFlagFastGPULightCulling3": "True"
}
```
### Enable CPULightCulling
``` json
{
    "FFlagDebugForceFSMCPULightCulling": "True"
}
```
### Esp..?
###### adds red circle under avatar and a grey thing above

``` json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest4": "False",
    "FFlagEnableInGameMenuChrome": "False",
    "FFlagEnableInGameMenuSongbirdABTest": "False"
}
```

### roblox fps unlocker
``` json
{
    "FFlagGameBasicSettingsFramerateCap5": "True",
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "0"
}
```
### unlimited fps
``` json
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "1000000000"
}
```
### Humanoid Outline
> [!NOTE]
> **Draws an outline around every part and every humanoid**
```json
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```
### fflag above but more complex
> [!NOTE]
> **Draws an outline around every body part**
```json
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```
### blue theme
###### patched?
``` json
{
    "FFlagLuaAppEnableFoundationColors7": "True"
}
```
### Disable Blue theme
```json
{
    "FFlagLuaAppFoundationColorsABTest": "False"
}
```
### Enable New Settings Layout
```
{
    "FFlagOverrideInExperienceMenuReorderVariant1": "True"
}
```
### make low quality roblox memes
``` json
{
  "DFIntDebugDynamicRenderKiloPixels":"2"
}
```
### Buggy ZPlane Camera
```json
{
    "FIntCameraFarZPlane": "1"
}
```
### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{
    "FFlagDebugHumanoidRendering": "True"
}
```
### Crash Roblox 1
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "0"
}
```
### Crash Roblox 2
```json
{
    "DFFlagVideoCaptureServiceEnabled": "False"
}
```
### Crash roblox 3 
##### when you try to launch roblox it won't open
```json
{
    "DFFlagDebugSimulateHangAtStartup": "True"
}
```
### Crash roblox 4
##### the same thing from above but it only crashes when you try to close roblox
```json
{
    "DFFlagDebugSimulateHangAtShutdown": "True"
}
```
## crash roblox
###### The Value must be 26778 for games to load.
```Json
{
  "DFIntWriterInputCheckLength":"1"
}
```
### custom accessory positions
###### found by maxiumadhd, almost lost ages ago, only for people who can't use.
``` json
{
"FFlagAXAccessoryAdjustmentlXPEnabledForAll": "True",
"DFFlagUseVisBugChecks": "True",
"DFFlagUseVisBugChecks27": "True",
}
```
### Increase Ping 
```json
{
    "DFIntDataSenderMaxBandwidthBps": "150"
}
```
### Shows the state of a flag
```json
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
```
> [!TIP]
> 
```json
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```
### Show Outlined Chunks
```json
{
    "FFlagDebugLightGridShowChunks": "True"
}
```
### Show Outlined Chunks that are being interacted
```json
{
    "DFFlagDebugEnableStreamingSolverVisualization": "True"
}
```
### Prevents Remote Events from running
###### @spectroscopic
```json
{
    "DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
```
### Lag remote events periodically
###### Does what it says, 0 and 2147483647 don't let you load games.
```Json
{
  "FIntRakNetResendBufferArrayLength":"1"
}
```
### log local player deaths/how you die and joins
###### only works with the new chat it goes in dev console so idk man
###### @return_request
```json
{
    "FStringDebugLuaLogLevel": "debug",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
```
### log player joins,leaves,messages
###### only works with the new chat
###### @return_request
```json
{
    "FStringDebugLuaLogLevel": "trace",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
```
### Max dev console log count
###### Control how many developer console logs can be shown at once, for example if you set the limit to be 100, then 100 different log messages will be shown while any older ones will be deleted when the limit is reached
###### @satlybpro
``` json
{
    "FIntNewDevConsoleMaxLogCount": "2147483647"
}
```
### Dev Console Logging
Changes how long a Message can be, doesn't give you the ability to exceed the 16k Message Length Limit
```Json
{
  "FIntStandardOutputMaximumCharacterLength":"1"
}
```
### Replace all Decals with a Test Image
###### @.rbx.bloxy
```json
{
    "FFlagDebugTestImageDrawItem": "True"
}
```
### Octree Validation
```json
{
    "FFlagDebugEnableOctreeValidation": "True"
}
```
### Self Explanatory 1
```json
{
    "DFFlagDebugPrintDataPingBreakDown": "True"
}
```
### Self Explanatory 2
```json
{
    "DFFlagDebugAudioLogging": "True"
}
```
### Duplicate of Above
```json
{
    "DFFlagDebugAudioLogging2": "True"
}
```
### Self Explanatory 3
```json
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```
### Self Explanatory 4
> [!NOTE]
> **Disable Drag Detectors**
```json
{
    "FFlagDragDetectors1": "False"
}
```
### Self Explanatory 5
> [!NOTE]
> **Disable CTM Climbing**
```json
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
```
### Self Explanatory 6
> [!NOTE]
> **Disable Feedback Button in ESC**
```json
{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
```
### Self Explanatory 7
###### @thefrenchguy4
``` json
{
    "FFlagRenamePassesAndGearToSubscriptionsAndPasses": "False"
}
```

### Self Explanatory 8
###### LDL dev console printing
###### @tyetonix
```json
{
    "DFFlagDebugSimLDLProgramPrintBuildStats": "True",
    "DFFlagDebugSimLDLProgramPrintExecStats": "True"
}
```
### Self Explanatory 9
###### prints body allocations counts in dev console
###### @tyetonix
```json
{
    "FFlagDebugCountSimBodyAllocations": "True"
}
```
### Abusive Game Specific Presets
###### this is stolen from luafv

#### You can contribute by making an issue.

## Fling Things and People

### Send people to hell 😈😈

``` json
{
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntDebugSimPrimalWarmstartVelocity": "-10",
    "DFIntDebugSimPrimalWarmstartForce": "1750",
    "DFIntDebugSimPrimalPreconditioner": "-20",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalToleranceInv": "2"
}
```
### Bury people alive
##### everything that you grab will fall through the ground
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalStiffness": "0"
}
```
### Send people to hell V2

> \[!TIP\] Modify warmstart to change speed

``` json
{
    "DFIntDebugSimPrimalNewtonIts": "2",
    "DFIntDebugSimPrimalPreconditioner": "1100",
    "DFIntDebugSimPrimalPreconditionerMinExp": "1000",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-800",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "FIntDebugSimPrimalGSLumpAlpha": "-2147483647"
}
```

### Send people to heaven

``` json
{
    "DFIntDebugSimPrimalNewtonIts": "1",
    "DFIntDebugSimPrimalPreconditioner": "15",
    "DFIntDebugSimPrimalPreconditionerMinExp": "10",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-150",
    "DFIntDebugSimPrimalWarmstartVelocity": "100",
    "FFlagDebugSimDefaultPrimalSolver": "True",
}
```
## slap battles and ability wars

## Good Anti KB
This combination works with every game that uses Ragdolls (the Anti KB is always active). You can change the NewtonIts Flag to stop being stuck on walls or objects (anything below 0 Crashes your game)

```Json
{
  "DFIntDebugSimPrimalPreconditionerMinExp": "1",
  "DFIntDebugSimPrimalNewtonIts": "2",
  "DFIntDebugSimPrimalWarmstartForce": "0",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalWarmstartVelocity": "0",
  "DFIntDebugSimPrimalToleranceInv": "1",
  "DFIntDebugSimPrimalPreconditioner": "1"
}
```
## Anti Kb 
##### use for anti fall, buggy.
##### This automatically teleports all ragdolled players limbs (except torso) to the games 0,0,0 (very unreliable, only drags your torso to the 0,0,0)
##### Default: Unknown

```Json
{
  "DFIntGameNetLocalSpaceMaxSendIndex": "100000"
}
```
## doors
### dark map 
###### only works in non lighted rooms + use voxel + use FFlagRenderFixFog if yk if it works
``` json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFIntTaskSchedulerTargetFps": "5588562",
    "FFlagDebugSkyGray": "true",
    "DFIntDebugFRMQualityLevelOverride": "2",
    "FIntRenderShadowIntensity": "0",
    "FFlagMSRefactor5": false,
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"asphalt\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"basalt\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"brick\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"cobblestone\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"concrete\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"crackedlava\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"diamondplate\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"fabric\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"glacier\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"glass\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"granite\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"grass\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"ground\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"ice\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"leafygrass\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"limestone\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"marble\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"metal\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"mud\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"pavement\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"pebble\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://13576561565\"],\"color\":[0,0,0]},\"rock\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9439557520\"],\"color\":[0,0,0]},\"salt\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"sand\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"sandstone\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"slate\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9439613006\"],\"color\":[0,0,0]},\"snow\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]},\"wood\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9439649548\"],\"color\":[0,0,0]},\"woodplanks\":{\"ids\":[\"rbxassetid://13576561565\",\"rbxassetid://9438453972\"],\"color\":[0,0,0]}}"

}
```


###### We are accepting performance Fast Flags that aren't listed or known.

### absolutely kill your game quality with fflags known to me
##### @dynamitebumblemouth
```json
{
    "FFlagDisablePostFx": "True",
    "FIntDebugTextureManagerSkipMips": "-1",
    "DFIntTextureCompositorActiveJobs": "0",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "DFIntTextureQualityOverride": "1"
}
```
### Absoulutely kills your game graphics
###### may be someone elses, or an older one.
``` json
{
    "FFlagDisablePostFx": "True",
    "FIntDebugTextureManagerSkipMips": "-1",
    "DFIntTextureCompositorActiveJobs": "0",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "DFIntTextureQualityOverride": "1"
}
```
### faster speed fflag (not walkspeed, doesnt increase fps, increases visual speed)
``` json
{
  "FFlagSimAdaptiveMinorOptimizations": "True",
  "DFIntNumAssetsMaxToPreload": "9999999",
  "FIntSmoothClusterTaskQueueMaxParallelTasks": "20",
  "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
  "DFIntDebugFRMQualityLevelOverride": "1",
  "DFIntMegaReplicatorNumParallelTasks": "20",
  "FIntSimWorldTaskQueueParallelTasks": "20",
  "DFIntMaxMissedWorldStepsRemembered": "1000",
  "DFIntAssetPreloading": "9999999",
  "DFIntReplicationDataCacheNumParallelTasks": "20",
  "DFIntPhysicsReceiveNumParallelTasks": "20",
  "DFIntConnectionMTUSize": "900",
  "DFFlagDebugPauseVoxelizer": "True",
  "FFlagFRMRefactor": "false"
}
```
### Low Graphics - High Render Distance
``` json
{
"DFFlagDebugRenderForceTechnologyVoxel": true,
"DFIntDebugFRMQualityLevelOverride": 1,
"FIntRenderShadowIntensity": 0
}
```

### Lower Ping
``` json
{
"DFIntConnectionMTUSize": 900,
"FIntRakNetResendBufferArrayLength": "128",
"FFlagOptimizeNetwork": "True",
"FFlagOptimizeNetworkRouting": "True",
"FFlagOptimizeNetworkTransport": "True",
"FFlagOptimizeServerTickRate": "True",
"DFIntServerPhysicsUpdateRate": "60",
"DFIntServerTickRate": "60",
"DFIntRakNetResendRttMultiple": "1",
"DFIntRaknetBandwidthPingSendEveryXSeconds": "1",
"DFIntOptimizePingThreshold": "50",
"DFIntPlayerNetworkUpdateQueueSize": "20",
"DFIntPlayerNetworkUpdateRate": "60",
"DFIntNetworkPrediction": "120",
"DFIntNetworkLatencyTolerance": "1",
"DFIntMinimalNetworkPrediction": "0.1"
}
```

### Boost FPS (Comfort To Play)
``` json
{
"DFIntCSGLevelOfDetailSwitchingDistance": 250,
"DFIntCSGLevelOfDetailSwitchingDistanceL12": 500,
"DFIntCSGLevelOfDetailSwitchingDistanceL23": 750,
"DFIntCSGLevelOfDetailSwitchingDistanceL34": 1000,
"DFIntTextureQualityOverride": 1,
"FFlagDisablePostFx": true
}
```

### Boost FPS
``` json
{
"FFlagDebugDisableTelemetryEphemeralCounter": true,
"FFlagDebugDisableTelemetryEphemeralStat": true,
"FFlagDebugDisableTelemetryEventIngest": true,
"FFlagDebugDisableTelemetryPoint": true,
"FFlagDebugDisableTelemetryV2Counter": true,
"FFlagDebugDisableTelemetryV2Event": true,
"FFlagDebugDisableTelemetryV2Stat": true
}
```

### OPTIMIZATION FFLAG
###### low quality mode
``` json
{
  "FFlagDebugGraphicsPreferD3D11FL10": "True",
  "FFlagGameBasicSettingsFramerateCap5": "False",
  "DFIntTaskSchedulerTargetFps": "5588562",
  "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
  "DFIntMaxFrameBufferSize": "4",
  "FIntDebugForceMSAASamples": "0",
  "DFFlagDebugPerfMode": "True",
  "FFlagDisablePostFx": "True",
  "FFlagFixGraphicsQuality": "True",
  "DFFlagDisableDPIScale": "True",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "DFIntCSGLevelOfDetailSwitchingDistance": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "DFFlagVoxelizerDisableTerrainSIMD": "True",
  "DFFlagDebugSkipMeshVoxelizer": "True",
  "FIntRenderShadowIntensity": "0",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
  "FIntRenderLocalLightUpdatesMax": "1",
  "FIntRenderLocalLightUpdatesMin": "1",
  "FFlagDebugRenderingSetDeterministic": "True",
  "FIntTerrainArraySliceSize": "4",
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0",
  "FIntRenderGrassDetailStrands": "0"
}
```
### OPTIMIZATION FFLAG
###### balanced quality mode.
``` json
{
  "FFlagDebugGraphicsPreferD3D11FL10": "True",
  "FFlagGameBasicSettingsFramerateCap5": "False",
  "DFIntTaskSchedulerTargetFps": "5588562",
  "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
  "DFIntMaxFrameBufferSize": "4",
  "FIntDebugForceMSAASamples": "0",
  "DFFlagDebugPerfMode": "True",
  "FFlagFixGraphicsQuality": "True",
  "DFFlagDisableDPIScale": "True",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "DFFlagVoxelizerDisableTerrainSIMD": "True",
  "DFFlagDebugSkipMeshVoxelizer": "True",
  "FIntRenderShadowIntensity": "0",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
  "FIntRenderLocalLightUpdatesMax": "1",
  "FIntRenderLocalLightUpdatesMin": "1",
  "FFlagDebugRenderingSetDeterministic": "True",
  "FIntTerrainArraySliceSize": "8",
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0",
  "FIntRenderGrassDetailStrands": "0"
}
```
### OPTIMIZATION FFLAG
###### high quality mode optimized.
``` json
{
  "FFlagDebugGraphicsPreferD3D11FL10": "True",
  "FFlagGameBasicSettingsFramerateCap5": "False",
  "DFIntTaskSchedulerTargetFps": "5588562",
  "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
  "DFIntMaxFrameBufferSize": "4",
  "FIntDebugForceMSAASamples": "0",
  "DFFlagDebugPerfMode": "True",
  "FFlagDisablePostFx": "True",
  "FFlagFixGraphicsQuality": "True",
  "DFFlagDisableDPIScale": "True",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "DFFlagVoxelizerDisableTerrainSIMD": "True",
  "DFFlagDebugSkipMeshVoxelizer": "True",
  "FIntRenderShadowIntensity": "0",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
  "FIntRenderLocalLightUpdatesMax": "1",
  "FIntRenderLocalLightUpdatesMin": "1",
  "DFFlagTextureQualityOverrideEnabled": "True",
  "DFIntTextureQualityOverride": "3",
  "FFlagDebugRenderingSetDeterministic": "True",
  "FIntTerrainArraySliceSize": "12",
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0",
  "FIntRenderGrassDetailStrands": "0"
}
```
### kaids optimization fflags
``` json
{
  "DFIntTaskSchedulerTargetFps": 540,
  "FFlagHandleAltEnterFullscreenManually": false,
  "FFlagFastGPULightCulling3": true,
  "FFlagPreloadAllFonts": true,
  "DFIntS2PhysicsSenderRate": 100,
  "FFlagFixGraphicsQuality": true,
  "FFlagAdServiceEnabled": false,
  "DFIntClientLightingTechnologyChangedTelemetryHundredthsPercent": 0,
  "DFStringCrashUploadToBacktraceBaseUrl": "null",
  "DFStringCrashUploadToBacktraceMacPlayerToken": "null",
  "DFStringCrashUploadToBacktraceWindowsPlayerToken": "null",
  "GoogleAnalyticsAccountPropertyID": "null",
  "GoogleAnalyticsAccountPropertyIDPlayer": "null",
  "FStringCoreScriptBacktraceErrorUploadToken": "null",
  "FStringGamesUrlPath": "/games/",
  "DFFlagClientBaseNetworkMetrics": false,
  "DFStringRobloxAnalyticsURL": "null",
  "DFStringTelegrafHTTPTransportUrl": "null",
  "DFStringAltTelegrafHTTPTransportUrl": "null",
  "DFStringTelegrafAddress": "127.0.0.1",
  "DFStringAltTelegrafAddress": "127.0.0.1",
  "DFStringTelemetryV2Url": "null",
  "DFFlagEnableLightstepReporting2": false,
  "DFIntLightstepHTTPTransportHundredthsPercent2": 0,
  "DFStringLightstepHTTPTransportUrlHost": "null",
  "DFStringLightstepHTTPTransportUrlPath": "null",
  "DFStringLightstepToken": "null",
  "FFlagDebugDisableTelemetryEphemeralCounter": true,
  "FFlagDebugDisableTelemetryEphemeralStat": true,
  "FFlagDebugDisableTelemetryEventIngest": true,
  "FFlagDebugDisableTelemetryPoint": true,
  "FFlagDebugDisableTelemetryV2Counter": true,
  "FFlagDebugDisableTelemetryV2Event": true,
  "FFlagDebugDisableTelemetryV2Stat": true,
  "DFStringHttpPointsReporterUrl": "null",
  "DFStringAltHttpPointsReporterUrl": "null",
  "DFStringAnalyticsEventStreamUrlEndpoint": "null"
}
```
### MY OPTIMIZATION FFLAG (CAN CRASH DUE TO VULKAN)
###### make sure to remove preferdirect3d11 and not disabledirect3d11 dont use in fighting games.
``` json
{
  "FLogNetwork": "7",
  "FFlagDisableNewIGMinDUA": "True",
  "FFlagEnableInGameMenuControls": "True",
  "FFlagEnableInGameMenuModernization": "True",
  "FFlagEnableMenuControlsABTest": "False",
  "FFlagEnableV3MenuABTest3": "False",
  "FFlagFixGraphicsQuality": "True",
  "FFlagEnableInGameMenuChrome": "False",
  "FFlagEnableInGameMenuChromeABTest3": "False",
  "DFIntTextureQualityOverride": "3",
  "DFFlagTextureQualityOverrideEnabled": "True",
  "FIntPGSPenetrationMarginMax": "-100000000",
  "FIntPGSPenetrationMarginMin": "-100000000",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "FFlagDebugDisableTelemetryPoint": "True",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "DFIntCSGLevelOfDetailSwitchingDistance": "500",
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": "1000",
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": "2000",
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": "4000",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagDebugGraphicsDisableDirect3D11": "True",
  "FFlagDebugGraphicsPreferVulkan": "True",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "DFIntDebugFRMQualityLevelOverride": "2",
  "DFIntCanHideGuiGroupId": "32380007",
  "FIntRenderShadowIntensity": "0",
  "FFlagCoreGuiTypeSelfViewPresent": "False",
  "FFlagInGameMenuV1FullScreenTitleBar": "False",
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
  "FFlagDisablePostFx": "True",
  "DFFlagDisableDPIScale": "True",
  "DFIntMaxMissedWorldStepsRemembered": "1000",
  "DFIntNumAssetsMaxToPreload": "9999999",
  "DFIntAssetPreloading": "9999999"
}
```
### Improve Animation Speed, Visual Fidelity, and Ping
``` json
{
    "FFlagSimEnableDCD10": "True",
    "FFlagDebugGraphicsPreferD3D11FL10": "True",
    "DFIntBufferCompressionLevel": "0",
    "DFIntBufferCompressionThreshold": "100",
    "DFIntPerformanceControlFrameTimeMax": "1",
    "DFIntPerformanceControlFrameTimeMaxUtility": "-1",
    "FFlagPushFrameTimeToHarmony": "True",
    "FFlagUISUseLastFrameTimeInUpdateInputSignal": "True",
    "DFIntAnimatorThrottleMaxFramesToSkip": "1",
    "DFIntNumFramesAllowedToBeAboveError": "1",
    "DFIntVisibilityCheckRayCastLimitPerFrame": "10",
    "DFIntNetworkSchemaCompressionRatio": "100",
    "DFIntTimeBetweenSendConnectionAttemptsMS": "200"
}
```
### Extreme Latency
``` json
{
    "DFIntLargePacketQueueSizeCutoffMB": "1000",
    "DFIntMaxProcessPacketsJobScaling": "10000",
    "DFIntMaxProcessPacketsStepsAccumulated": "0",
    "DFIntMaxProcessPacketsStepsPerCyclic": "5000",
    "DFIntMegaReplicatorNetworkQualityProcessorUnit": "10"
}
```
### Network CPU RSS Tweaks
``` json
{
    "DFIntPhysicsReceiveNumParallelTasks": "20",
    "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
    "FFlagSimAdaptiveMinorOptimizations": "True",
    "FIntSimWorldTaskQueueParallelTasks": "20",
    "FIntSmoothClusterTaskQueueMaxParallelTasks": "20",
    "DFIntReplicationDataCacheNumParallelTasks": "20",
    "DFIntMegaReplicatorNumParallelTasks": "20"
}
```
### V1
###### very low quality for performance, by espresso-soft
``` json
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "9999",
    "FFlagDebugRenderingSetDeterministic": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "DFFlagDisableDPIScale": "True",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6",
    "FIntRenderLocalLightFadeInMs": "-1",
    "FFlagDisablePostFx": "True",
    "DFFlagDebugPauseVoxelizer": "True",
    "FFlagDebugSkyGray": "True",
    "FFlagFastGPULightCulling3": "True",
    "DFIntMaxFrameBufferSize": "4",
    "FIntTerrainArraySliceSize": "4",
    "DFIntTextureCompositorActiveJobs": "0",
    "FIntDebugTextureManagerSkipMips": "8",
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntRenderGrassHeightScaler": "0",
    "FIntRenderShadowmapBias": "-1",
    "FFlagAdServiceEnabled": "False",
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0",
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableInGameMenuChromeABTest3": "False",
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True",
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### V2
###### by espresso-soft
``` json
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "9999",
    "FFlagRenderFixFog": "True",
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "DFFlagDisableDPIScale": "True",
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True",
    "FIntRenderLocalLightUpdatesMax": "6",
    "FIntRenderLocalLightUpdatesMin": "4",
    "FIntRenderLocalLightFadeInMs": "0",
    "FFlagDisablePostFx": "True",
    "FFlagNewLightAttenuation": "True",
    "FFlagDebugForceFSMCPULightCulling": "True",
    "DFIntMaxFrameBufferSize": "6",
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3",
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntDebugForceMSAASamples": "0",
    "FFlagGameBasicSettingsFramerateCap5": "False",
    "FFlagUserShowGuiHideToggles": "True",
    "FFlagGuiHidingApiSupport2": "True",
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
    "DFIntTimestepArbiterThresholdCFLThou": "300",
    "FFlagAdServiceEnabled": "False",
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True",
    "DFIntDefaultTimeoutTimeMs": "10000",
    "FFlagEnableQuickGameLaunch": "True",
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0",
    "FFlagHandleAltEnterFullscreenManually": "False",
    "FIntRobloxGuiBlurIntensity": "0",
    "FFlagErrorPromptResizesHeight": "False",
    "FFlagNewCameraControls": "True",
    "DFIntS2PhysicsSenderRate": "10000"
}
```
### v2 modified
###### espresso-soft's v2, not youtuber optimizations.
##### use lower ping for lower ping.
##### early fflag optimization, do not use if your using a game with heavy light.
``` json
{
  "FLogNetwork": "7",
  "DFIntAnimationLodFacsVisibilityDenominator": "0",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
  "FFlagGuiHidingApiSupport2": "True",
  "FFlagEnableInGameMenuChrome": "False",
  "FFlagEnableV3MenuABTest3": "False",
  "FIntTerrainArraySliceSize": "4",
  "DFIntTextureQualityOverride": "3",
  "DFIntAnimationLodFacsDistanceMin": "0",
  "FIntRenderShadowIntensity": "0",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "FFlagErrorPromptResizesHeight": "False",
  "FFlagEnableInGameMenuControls": "True",
  "FFlagDebugCheckRenderThreading": "True",
  "FIntRenderLocalLightUpdatesMax": "6",
  "DFIntMaxMissedWorldStepsRemembered": "1000",
  "FIntSmoothClusterTaskQueueMaxParallelTasks": "20",
  "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
  "FFlagDisablePostFx": "True",
  "DFFlagTextureQualityOverrideEnabled": "True",
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
  "DFFlagDisableDPIScale": "True",
  "DFIntPhysicsReceiveNumParallelTasks": "20",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FIntRobloxGuiBlurIntensity": "0",
  "FFlagUserRaycastPerformanceImprovements": "true",
  "FIntDebugForceMSAASamples": "0",
  "FFlagUserShowGuiHideToggles": "True",
  "FFlagEnableInGameMenuChromeABTest4": "False",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "DFIntCanHideGuiGroupId": "32380007",
  "FFlagEnableMenuControlsABTest": "False",
  "DFIntDebugFRMQualityLevelOverride": "1",
  "FIntFRMMinGrassDistance": "0",
  "FIntSimWorldTaskQueueParallelTasks": "20",
  "FFlagDebugForceFSMCPULightCulling": "True",
  "DFIntTaskSchedulerTargetFps": "0",
  "FFlagEnableInGameMenuChromeABTest3": "False",
  "DFIntAnimationLodFacsDistanceMax": "0",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagEnableInGameMenuModernization": "True",
  "FFlagSimAdaptiveMinorOptimizations": "True",
  "DFIntConnectionMTUSize": "900",
  "FIntRenderGrassDetailStrands": "0",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
  "FIntNewInGameMenuPercentRollout3": "0",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "DFIntDefaultTimeoutTimeMs": "10000",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "FFlagGameBasicSettingsFramerateCap5": "True",
  "DFIntReplicationDataCacheNumParallelTasks": "20",
  "FFlagRenderFixFog": "True",
  "FFlagNewLightAttenuation": "True",
  "DFIntMegaReplicatorNumParallelTasks": "20",
  "FIntRenderLocalLightUpdatesMin": "4",
  "DFIntAssetPreloading": "9999999",
  "DFIntMaxFrameBufferSize": "6",
  "FFlagRenderDebugCheckThreading2": "True",
  "FIntRenderLocalLightFadeInMs": "0",
  "FFlagCommitToGraphicsQualityFix": "True",
  "FFlagEnableQuickGameLaunch": "True",
  "DFIntTimestepArbiterThresholdCFLThou": "300",
  "DFIntS2PhysicsSenderRate": "10000",
  "FFlagDebugGraphicsDisableDirect3D11": "True",
  "FFlagNewCameraControls": "True",
  "FFlagFixGraphicsQuality": "True",
  "FFlagAdServiceEnabled": "False",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
  "FIntFRMMaxGrassDistance": "0",
  "FFlagFRMRefactor": "false",
  "DFIntNumAssetsMaxToPreload": "9999999",
  "FFlagDebugDisableTelemetryPoint": "True",
  "DFFlagDebugPauseVoxelizer": "True",
  "FFlagDebugGraphicsPreferVulkan": "True",
  "FFlagDebugForceFutureIsBrightPhase2": "True",
  "FFlagUserUpdateInputConnections": "true",
  "DFIntHttpRbxApiMaxBudgetMultiplier": "2",
  "DFIntHttpRbxApiJobFrequencyInSeconds": "60",
  "DFIntHttpRbxApiClientPerMinuteRequestLimit": "60",
  "DFIntHttpRbxApiMaxRetryBudgetPerMinute": "60",
  "DFIntHttpRbxApiMaxRetryCount": "3",
  "DFIntHttpRbxApiMaxRetryQueueSize": "1000",
  "DFIntHttpRbxApiMaxSyncRetries": "3",
  "DFIntHttpRbxApiPerMinuteRequestLimit": "60",
  "DFIntHttpRbxApiSameUrlRequestLimit": "30",
  "DFIntHttpRbxApiServiceDecaySeconds": "300",
  "DFIntHttpRbxApiMaxThrottledQueue": "500",
  "DFFlagSimOptimizeSetSize": "True",
  "FIntDirectionalAttenuationMaxPoints": "50",
  "FFlagRenderCBRefactor2": "True",
  "FFlagLuaAppLegacyInputSettingRefactor": "True",
  "FFlagRenderShadowSkipHugeCulling": "true",
  "FFlagShoeSkipRenderMesh": "false",
  "FFlagEnableNewChatTabExperiment5": "False",
  "FIntRakNetResendBufferArrayLength": "128",
  "FFlagOptimizeNetwork": "True",
  "FFlagOptimizeNetworkRouting": "True",
  "FFlagOptimizeNetworkTransport": "True",
  "FFlagOptimizeServerTickRate": "True",
  "DFIntServerPhysicsUpdateRate": "60",
  "DFIntServerTickRate": "60",
  "DFIntRakNetResendRttMultiple": "1",
  "DFIntRaknetBandwidthPingSendEveryXSeconds": "1",
  "DFIntOptimizePingThreshold": "50",
  "DFIntPlayerNetworkUpdateQueueSize": "20",
  "DFIntPlayerNetworkUpdateRate": "60",
  "DFIntNetworkPrediction": "120",
  "DFIntNetworkLatencyTolerance": "1",
  "DFIntMinimalNetworkPrediction": "0.1",
  "FFlagMovePrerender": "True"
}
```
### youtuber optimizations
### v1
###### [video](https://www.youtube.com/watch?v=fj0zVi6UG9A)
##### Basic FPS Boosting Flaglist
``` json
{
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FLogNetwork": "7",
  "FIntDebugForceMSAASamples": "0",
  "FIntRenderShadowIntensity": "0",
  "FFlagDisablePostFx": "True",
  "FIntTerrainArraySliceSize": "0",
  "DFIntTaskSchedulerTargetFps": "160",
  "FFlagDebugGraphicsPreferD3D11": "True",
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
  "FFlagNewLightAttenuation": "True",
  "DFIntDebugFRMQualityLevelOverride": "1",
  "FFlagDebugDisplayFPS": "True",
  "FFlagGlobalWindRendering": "False",
  "FFlagGlobalWindActivated": "False",
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0",
  "FIntRenderGrassDetailStrands": "0",
  "FIntRenderGrassHeightScaler": "0"
}
```
### v2
##### Will literally disable major load components like textures, lighting, skybox, UI, etc.
``` json
{
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FLogNetwork": "7",
  "FIntDebugForceMSAASamples": "0",
  "FIntRenderShadowIntensity": "0",
  "FFlagDisablePostFx": "True",
  "FIntTerrainArraySliceSize": "4",
  "DFIntTaskSchedulerTargetFps": "160",
  "FFlagDebugGraphicsPreferD3D11": "True",
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
  "FFlagNewLightAttenuation": "True",
  "DFIntDebugFRMQualityLevelOverride": "1",
  "FFlagDebugDisplayFPS": "True",
  "FFlagGlobalWindRendering": "False",
  "FFlagGlobalWindActivated": "False",
  "FIntFRMMinGrassDistance": "0",
  "FIntFRMMaxGrassDistance": "0",
  "FIntRenderGrassDetailStrands": "0",
  "FIntRenderGrassHeightScaler": "0",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
  "DFFlagDebugPauseVoxelizer": "True",
  "FFlagDebugSkyGray": "True",
  "DFIntCSGLevelOfDetailSwitchingDistance": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
  "FFlagDebugForceFSMCPULightCulling": "True",
  "DFIntPerformanceControlTextureQualityBestUtility": "-1",
  "DFIntTextureCompositorActiveJobs": "0",
  "DFFlagTextureQualityOverrideEnabled": "True",
  "DFIntTextureQualityOverride": "0",
  "FFlagUpdateHealthBar": "False"
}
```
### v1 modified
###### making in a week or so, make an issue if you have one.
### v2 modified
###### making in a week or so, make an issue if you have one.
### RCOOL OPTIMIZATIONS (MAY BE OLD)
``` json
{
    "FFlagHandleAltEnterFullscreenManually": "False",
    "FLogNetwork": "7",
    "DFIntTaskSchedulerTargetFps": "9999",
    "FFlagFixGraphicsQuality": "True",
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FIntRenderLocalLightFadeInMs": "0",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True",
    "FStringPartTexturePackTable2022": "{\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://7547304948\u0022,\u0022rbxassetid://7546645118\u0022],\u0022color\u0022:[254,254,254,7]}}",
    "FStringTerrainMaterialTable2022": "",
    "FStringTerrainMaterialTablePre2022": "",
    "FFlagGlobalWindActivated": "False",
    "FFlagEnableBetaFacialAnimation2": "False",
    "FFlagFacialAnimationSupport1": "False",
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0",
    "DFFlagEnableDynamicHeadByDefault": "False",
    "FIntRobloxGuiBlurIntensity": "0",
    "FFlagDebugRenderingSetDeterministic": "True",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "FIntRenderLocalLightUpdatesMax": "1",
    "FIntRenderLocalLightUpdatesMin": "1",
    "FFlagAdServiceEnabled": "False",
    "FFlagFastGPULightCulling3": "True",
    "FFlagNewLightAttenuation": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagEnableCommandAutocomplete": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True",
    "FIntFRMMaxGrassDistance": "0",
    "FFlagSoundsUsePhysicalVelocity": "True",
    "FIntRenderGrassDetailStrands": "0",
    "FFlagChromeBetaFeature": "False",
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableChromePinnedChat": "False",
    "FFlagEnableInGameMenuChrome": "False",
    "FFlagEnableInGameMenuChromeABTest": "False",
    "FFlagEnableInGameMenuChromeSignalAPI": "False",
    "FFlagPlayerListChromePushdown": "False",
    "FStringEnableChromePinnedChatForcedUserIds": "1",
    "FStringGameMenuChromeForcedUserIds": "1",
    "FFlagVoiceBetaBadge": "False",
    "FFlagTopBarUseNewBadge": "False",
    "FFlagEnableBetaBadgeLearnMore": "False",
    "FFlagBetaBadgeLearnMoreLinkFormview": "False",
    "FFlagControlBetaBadgeWithGuac": "False",
    "FStringVoiceBetaBadgeLearnMoreLink": "null",
    "FIntRenderGrassHeightScaler": "0",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "DFFlagDisableDPIScale": "True",
    "DFIntTextureCompositorActiveJobs": "0",
    "FFlagCoreGuiTypeSelfViewPresent": "False",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "FFlagDisableNewIGMinDUA": "True",
    "FFlagPreloadAllFonts": "True",
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagDebugSkyGray": "True",
    "DFIntMaxFrameBufferSize": "4",
    "FFlagRenderGpuTextureCompressor": "True",
    "FFlagGpuGeometryManager7": "True",
    "DFFlagPredictedOOM": "False",
    "DFIntPredictedOOMPercent": "0",
    "FFlagDisablePostFx": "True",
    "FFlagEnableQuickGameLaunch": "True",
    "DFFlagDebugPauseVoxelizer": "True",
    "FIntTerrainArraySliceSize": "4",
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "1",
    "FFlagEnableAudioOutputDevice": "False"
}
```

### you finished??
### heres the code frequency:
 ![image](https://github.com/user-attachments/assets/7110f208-5ba5-445f-9ce8-6e66fa9850ca)


 ### no telemetry
 ``` json
{
"DFStringTelegrafHTTPTransportUrl": "n.google.com",
"DFStringTelemetryV2Url": "n.google.com",
"DFStringTelegrafAddress": "0.0.0.0",
"DFStringRobloxAnalyticsURL": "n.google.com",
"FFlagEnableBooleanRobloxTelemetry": false,
"FFlagLuaAppChallengeMoreTelemetryEnabled": false,
"FFlagLuaAppLogoutTelemetry": false,
"FFlagReportRenderDistanceTelemetry": false,
"FFlagSocialAnalyticsSupportTelemetry": false,
"FFlagSTUDIOPLAT34382ANRMoreTelemetry": false,
"FFlagTimeAndNewJoinDataTelemetry": false,
"FFlagVideoCaptureFailureTelemetry": false,
"FFlagVoiceChatDontSendTelemetryForPubIceTrickle": true,
"FFlagVoiceChatEnableRobloxTelemetryServiceInitEvent": false,
"FIntBootstrapperTelemetryReportingHundredthsPercentage": 0,
"FIntConnectionTelemetryPollIntervalMS": 32700000,
"FIntHttpWrapperTelemetryHundredthsPercent": 0,
"FIntUserActionTrackerTelemetryHundredthsPercent": 0,
"DFFlagAddDynamicHeadTelemetryToSessionTracking2": false,
"DFFlagAddPlaySessionIdTelemetry": false,
"DFFlagAudioDeviceTelemetry": false,
"DFFlagBrowserTrackerIdTelemetryEnabled": false,
"DFFlagClientLightingTechnologyChangedTelemetryTrackTimeSpent": false,
"DFFlagClientRolloutPhaseTelemetry": false,
"DFFlagEnableTelemetryV2FRMStats": false,
"DFFlagFFlagRolloutDuplicateRobloxTelemetryCountersEnabled": false,
"DFFlagFFlagRolloutDuplicateTelemetryCountersEnabled": false,
"DFFlagGraphicsQualityUsageTelemetry": false,
"DFFlagReportLegacyFRMStatsToTelemetryV2": false,
"DFFlagSessionTelemetryLayeredClothing": false,
"DFFlagVoiceReliabilityTelemetryEventIngest": false,
"FFlagDebugDisableTelemetryEphemeralCounter": "True",
"FFlagDebugDisableTelemetryEphemeralStat": "True",
"FFlagDebugDisableTelemetryEventIngest": "True",
"FFlagDebugDisableTelemetryPoint": "True",
"FFlagDebugDisableTelemetryV2Counter": "True",
"FFlagDebugDisableTelemetryV2Event": "True",
"FFlagDebugDisableTelemetryV2Stat": "True"
}
```
