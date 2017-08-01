# vrp_garages
fx-server only, requires my vrp_lscustoms

Add:
```
AddEventHandler('vrp_garages:setVehicle', function(vtype, vehicle)
	vehicles[vtype] = vehicle
end)
```
to the top of your vrp/client/basic_garage.lua, under the local vehicles variable, for vehicle button compatibility.
