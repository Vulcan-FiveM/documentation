# Handling data

This is some basic documentation to assist with a handling editor to reference.

## handling.meta fields

... and specifically, ones we care about.

[Source](https://gtamods.com/wiki/Handling.meta)

### Physical

These seven values represent the vehicle's physical proportions within the game.

* fMass
* fInitialDragCoeff
* fDownForceModifier
* fPercentSubmerged
* vecCentreOfMassOffset
* vecInertiaMultiplier

### Transmission

These values describe the vehicle's straight line performance. Rate of acceleration is determined by fDriveBiasFront, nInitialDriveGears, fInitialDriveForce, fDriveInertia, and fInitialDriveMaxFlatVel. Rate of deceleration is determined by fBrakeForce and fBrakeBiasFront. fSteeringLock can be thought of as a measure of sideways acceleration.

* fDriveBiasFront
* nInitialDriveGears
* fInitialDriveForce
* fDriveInertia
* fClutchChangeRateScaleUpShift
* fClutchChangeRateScaleDownShift
* fInitialDriveMaxFlatVel
* fBrakeForce
* fBrakeBiasFront
* fHandBrakeForce
* fSteeringLock

### Wheel Traction

The following attributes describe how the vehicle will behave dynamically, from negotiating corners to acceleration and deceleration. This section has been updated from previous game versions.

* fTractionCurveMax
* fTractionCurveMin
* fTractionCurveLateral
* fTractionSpringDeltaMax
* fLowSpeedTractionLossMult
* fCamberStiffnesss
* fTractionBiasFront
* fTractionLossMult

### Suspension

* fSuspensionForce
* fSuspensionCompDamp
* fSuspensionReboundDamp
* fSuspensionUpperLimit
* fSuspensionLowerLimit
* fSuspensionRaise
* fSuspensionBiasFront
* fAntiRollBarForce
* fAntiRollBarBiasFront
* fRollCentreHeightFront
* fRollCentreHeightRear

### Damage

The following attributes dictate how the vehicle will react to damaging effects.

* fCollisionDamageMult
* fWeaponDamageMult
* fDeformationDamageMult
* fEngineDamageMult
* fPetrolTankVolume
* fOilVolume

### Miscellaneous

* fSeatOffsetDistX
* fSeatOffsetDistY
* fSeatOffsetDistZ
* nMonetaryValue
* strModelFlags
* strHandlingFlags
* strDamageFlags
* AIHandling
