# City Commands

The commands available in the city view.

## Commands

### AnimationRecorder
### ApplyTerrainBrush
### AvenueTool
### Cancel
### CenterOnCursor
### DemolishSignsAndLabels
### DemolishTool
### DeZoneTool
### DispatchFireTool
### DispatchPoliceTool
### EnableDayAndNight
### EnableDayOnly
### EnableNightOnly
### FullScreenRefresh
### GetAltitude

Gets the altitude at the specified position.

Parameters:

`<x>` `<z>`

`<x>` - the x position as a float32 value.    
`<z>` - the z position as a float32 value.

Returns the altitude as a float32 value.

### GetCellAltitude

Gets the altitude at the specified cell.

Parameters:

`<cell x>` `<cell z>`

`<cell x>` - the cell x position.    
`<cell z>` - the cell z position.

Returns the altitude as a float32 value.

### GetCityEstablished

Gets a value indicating if the city is established (in mayor mode).

### GetCityName

Gets the city name.

### GetCitySize

Returns two integers, the x cell count and the z cell count.

### GetMayorName

Gets the mayor name.

### GetSeaLevel

Gets the sea level.

Returns the sea level as a float32 value.

### GetSimulationDate

Gets the simulation date.

Parameters:

One to six strings from the following table with spaces as the separator.

| Date String | Description |
|-------------|-------------|
| `"day of month"` | The day of the month. |
| `"day of week"` | The day of the week. Range of 1-7 representing Monday-Sunday. |
| `"day of year"` | The day of the year. |
| `"month"` | The month. Range of 1-12 representing January-December. |
| `"number"` | The internal date representation. |
| `"year"` | The year. |

Returns numbers for each of the requested string values.

Remarks:

The start date for the simulation is January 1st, 2000.

### HighwayTool
### LabelTool
### LightRailTool
### OpenAudioOptionsDialog
### OpenCheatCodeDialog
### OpenGraphicOptionsDialog
### OpenObliterateCityDialog
### OpenPhotoAlbumDialog
### OpenPlayOptionsDialog
### OpenSnapshotDialog
### PauseAnimation
### PipesTool
### PlaceBuilding

Places a building at the specified position.

Parameters:

`<building id>` `<position x>` `<position z>`

`<building id>` - the building id number.   
`<position x>` - the x position.    
`<position z>` - the z position.    

### PlaceBusStopTool
### PlaceClinicTool
### PlaceCollegeTool
### PlaceElementarySchoolTool
### PlaceFerryTerminalTool
### PlaceFlora

Places flora at the specified position.

Parameters:

`<flora id>` `<position x>` `<position z>`

`<flora id>` - the flora id number.   
`<position x>` - the x position.    
`<position z>` - the z position.    

### PlaceFreightDepotTool
### PlaceHighSchoolTool
### PlaceHospitalTool
### PlaceJailTool
### PlaceLargeFireStationTool
### PlaceLargePoliceStationTool
### PlaceLightRailStationTool
### PlaceLotTool

Activates the place lot tool with the specified lot configuration exemplar instance id.

Parameters: `<lot id>`

### PlacePassengerDepotTool
### PlacePoliceKioskTool
### PlaceSmallFireStationTool
### PlaceSmallPoliceStationTool
### PlaceSubwayStationTool
### PowerLinesTool
### QueryTool
### QuitCity

Exits to the region view.

Parameters:

`<show confirmation dialog>`

`<show confirmation dialog>` - A Boolean indicating weather to show a confirmation dialog to the user.

### QuitGame

Exits the game.

Parameters:

`<show confirmation dialog>` `<save city>`

`<show confirmation dialog>` - A Boolean indicating weather to show a confirmation dialog to the user.    
`<save city>` - A Boolean indicating weather to save the city.

### RailTool
### RoadTool
### RotateCCW
### RotateCW
### RotateLotCCW
### RotateLotCW
### SaveCity
### SaveCityQuick
### ScrollDown
### ScrollDownOnce
### ScrollDownStop
### ScrollLeft
### ScrollLeftOnce
### ScrollLeftStop
### ScrollRight
### ScrollRightOnce
### ScrollRightStop
### ScrollUp
### ScrollUpOnce
### ScrollUpStop
### SetAltitude

Sets the altitude at the specified position.

Parameters:

`<x>` `<z>` `<altitude>`

`<x>` - the x position as a float32 value.    
`<z>` - the z position as a float32 value.    
`<altitude>` - the altitude as a float32 value.

### SetCellAltitude

Sets the altitude at the specified position.

Parameters:

`<x1>` `<z1>` `[x2]` `[z2]` `<altitude>`

`<x1>` - the starting cell x position.    
`<z1>` - the starting cell z position.    
`[x2]` - the ending cell x position.    
`[z2]` - the ending cell z position.    
`<altitude>` - the altitude as a float32 value.    

The `x2` and `z2` parameters are optional, when used they form a bounding box of cells that will
have the altitude changed.
If omitted, the altitude will only be changed for the cell specified by `x1` and `z1`.

### SetCityEstablished

Sets the city to established (mayor mode).

### SetCityName

Sets the city name.

Parameters: `name string`

### SetExpandedToolTips

Toggles the use of expanded tool tips.

### SetMayorName

Sets the mayor name.

Parameters: `name string`

### SetSeaLevel

Sets the sea level.

Parameters: `<sea level>` - the sea level as a float32 value.

### SignTool
### SimSpeedFast
### SimSpeedMedium
### SimSpeedPause
### SimSpeedSlow
### StepAnimation
### StreetTool
### SubwayTool
### TextDecal
### ToggleGodPanel
### ToggleGridVisibility
### ToggleMayorPanel
### ToggleMySimPanel
### ToggleOptionsPanel
### ToggleSignsAndLabels
### ToggleTerrainContourDisplay
### ToggleUIVisibility
### ToxicSpill
### TrafficQueryTool
### ZoneAgriculturalTool
### ZoneHighCommercialTool
### ZoneHighIndustrialTool
### ZoneHighResidentialTool
### ZoneLandfillTool
### ZoneLowCommercialTool
### ZoneLowResidentialTool
### ZoneMediumCommercialTool
### ZoneMediumIndustrialTool
### ZoneMediumResidentialTool
### Zoom0
### Zoom1
### Zoom2
### Zoom3
### Zoom4
### Zoom5
### ZoomIn
### ZoomOut
