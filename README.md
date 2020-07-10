# mirrox-hud
Hud with /cinema and traction control built-in

### Requirements
* mythic_notify (https://github.com/mythicrp/mythic_notify)

# F3-meny
```
if data.current.value == 'beltToggle' then
  beltToggle()
end	

if data.current.value == 'tc' then
  TriggerEvent('tc')
end


function beltToggle()
  if IsPedInAnyVehicle(GetPlayerPed(-1), false) and GetVehicleClass(GetVehiclePedIsIn(GetPlayerPed(-1), false)) ~= 8 and GetVehicleClass(GetVehiclePedIsIn(GetPlayerPed(-1), false)) ~= 13 and GetVehicleClass(GetVehiclePedIsIn(GetPlayerPed(-1), false)) ~= 14 then
    TriggerEvent('balte')
  end
end
```

## Screenshots

<img src="https://i.imgur.com/HrQgidz.png">
<img src="https://i.imgur.com/Y1pU9Sg.png">
