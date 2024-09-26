# roblox-fflags

### THANKS TO LUAFV AND MORE FOR FINDING THESE
###### rare ones have a bit bigger text than usual

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

### Client Simulation Radius
Sets your clients simulation radius ( as far as i know )

```Json
{
  "DFIntMaxClientSimulationRadius":10000,
  "DFIntMinClientSimulationRadius":10000
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
### N/A
``` json
    {
        "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
        "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
        "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
        "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
    }
```
### Crash Roblox
``` json

    {
        "DFIntTimestepArbiterThresholdCFLThou": "0"
    }
```
### Stuttery Animation Fix
``` json

    {
        "DFIntTimestepArbiterThresholdCFLThou": "300"
    }
```

### Remap R6 to R15 Rigs/Weird Movement
``` json

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

### Freeze
``` json
    {
        "FFlagDebugSimDefaultPrimalSolver": "True",
        "DFIntDebugSimPrimalLineSearch": "0"
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
This fast flag sets the current physics "FPS", this slows down all the physics related stuff aka falling, walking
Default: 16

```Json
{
  "DFIntMaxMissedWorldStepsRemembered":1
}
```
## Active Physics FPS Change
Go into settings  and change your FPS to 240 (if you can reach that amount of FPS) and you will have full Physics speed, at 30 fps its around 7,5/s. Any Part you have network Ownershipship over is also slowed down, as well as shot projectiles.

```Json
{
  "FFlagGameBasicSettingsFramerateCap": "True",
  "DFIntTaskSchedulerTargetFps": 0,
  "DFIntMaxMissedWorldStepsRemembered":"1"
}
```

##### Games: any game (obbys are easier to do with slow Physics)

### Slow motion
###### aka physics slow down
###### change for diffrent effects

``` json
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```
### warp
``` json
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
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
# Visuals ig
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
### logs stuff in dev console
```json
{
    "FStringDebugLuaLogLevel": "debug",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
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
```
{
    "FFlagRenamePassesAndGearToSubscriptionsAndPasses": "False"
}
```

#

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
This automatically teleports all ragdolled players limbs (except torso) to the games 0,0,0 (very unreliable, only drags your torso to the 0,0,0)
Default: Unknown

```Json
{
  "DFIntGameNetLocalSpaceMaxSendIndex":100000
}
```
