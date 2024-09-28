# RANDOM FFLAGS      
###### at least these aint gatekepted because these are sick


### thanks to fishe for these
###### some may not work.

Physics Changing Flags
### Uncap FPS
```json
{
"DFIntTaskSchedulerTargetFps": "9999"
}
```
### Causes some character collision from jumping physics breakdown, making model ragdoll
``` json
{
"DFIntLandedBalanceD": "-2000"
}
```
### All type of wallhops, longjumps, headhitters and probably more stop working
``` json
{
"DFFlagSimHumanoidPhysics": "True"
}
```
### Break legs collision from 2 to -inf, kinda break camera on values over 3
``` json
{
"DFIntRaycastMaxDistance": "0"
}
```
### Kinda breaks movement and some other stuff on higher negative values
``` json
{
"FIntPGSAngularDampingPermilPersecond": "-10000"
}
```
### Default is for the first one is "True". Basically with False, and True. It allows you to fall quicker and ignore certain block designs. For example if you're playing phantom forces and normally if you go up a slanted hill that goes upward it makes you slower. But, this makes you pretty much have no slowdowns.
``` json
{ 
"FFlagHumanoidOnlySetCollisionsOnStateChangeDefaultIsEnabled": "False",
"FFlagHumanoidParallelFasterSetCollision": "True" 
}
```
### Gear desync just by dropping it
``` json
{
"DFIntDataSenderRate": "-1"
}
```
### Another noclip fflag but acts differently
``` json
{
"DFIntAssemblyExtentsExpansionStudHundredth": "-150"
}
```
### Freezes character in any state, can cause crashes, basically stacks input data
``` json
{
"FFlagSimIslandizerManager": "false"
}
```
### Spins character when moving
``` json
{
"DFIntRunningBaseOrientationP": "-14"
}
```
### Makes character upside down
``` json
{
"DFIntFreeFallBalanceP": "-9999"
}
```
### Makes character ragdoll forever
``` json
{
"DFIntGettingUpBalanceP": "0"
}
```
### Lags the player
``` json
{
"DFIntS2PhysicsSenderRate": "10000000"
}
```
### Spins character while they are in falling/jumping state
``` json
{
"DFIntFreeFallOrientationP": "-14"
}
```
### Noclip FFlags, require to be used in combo
``` json
{
"FIntPGSPenetrationMarginMax": "2147483647",
"FIntPGSPenetrationMarginMin": "2147483647"
}
```
### Allows you to bounce high from flicks
``` json
{
"DFIntNewRunningBaseAltitudeP": "49534"
}
```
### Character gets into a ragdoll loop (only when you're in a ragdoll state already)
``` json
{
"DFIntGettingUpBalanceD": "-10000"
}
```
### Bounces character constantly at 0. Jump to randomly bounce yourself high or just fall through the map at 500
``` json
{
"DFIntNewRunningBaseAltitudeD": "0"
}
```
### Very limited speed fflag that works only in a few games, one of them being Phantom Forces, and it makes you only slightly faster
``` json
{
"DFIntDebugSimPhysicsSteppingMethodOverride": 10000000
}
```
### Makes it so your gravity is reduced by a factor of Int value you put in when on the ground, weird trigger + very sensitive (2000 makes you fling like 100 studs up everytime u touch the floor) 1500 makes you "hop" very quickly on the ground, if u hold jump sometimes you are able to jump with the gravity reduction meaning a super jump
``` json
{
"DFIntNewRunningBaseGravityReductionFactorHundredth": "1000"
}
```
### Very controllable bounce, only works with negative values, 0 allows you to hover
``` json
{
"DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
```
### Adds head colission to r15 
``` json
{
"FFlagMeshPartHeadsDefaultIsEnabled": false
}
```
### World speed flag based on player's fps, boosts the physics fps basically
``` json
{
"FFlagDebugSimIntegrationStabilityTesting": "True"
}
```
###  noclip, but like complete noclip, you will fall through the floor
``` json
{
"DFIntSHCellMinSizeAsBitShift": "4"
}
```
### Wallglide
``` json
{
"DFIntUnstickForceAttackInTenths": "-1"
}
```

# patched.
### thanks to fishy again
``` json
{
"DFIntDebugSimForceWorldStepCount": "14"
"DFIntJumpPowerInstantControllerMultiplierPercent": "1000"
"DFIntDefaultBalanceD": "-10"
"DFIntDefaultBalanceP": "-10"
"DFIntFreeFallFloorSearchDistanceIncreaseVelocity": "1"
"DFIntSolidFloorPercentForceApplication": "1000"
"DFIntGeometricStiffnessAlpha": "-100000"
}
```
