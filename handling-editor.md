# Handling Editor

## Custom Events

I copied the vehiclechecker.lua from baseevents.lua and made a client-only variant. The events are as follows:

### clientEnteredVehicle

Returns:
```lua
vehicleId, seat, displayName
```

### clientLeftVehicle

Returns:
```lua
vehicleId, seat, displayName
```

### clientEnterVehicleAborted

No returned values

### clientEnteringVehicle

Returns:
```lua
vehicleId, seat, displayName
```

Source is not specified. The source is always the local player.
