# Region Commands

The commands available in the region view.

## Commands

### Cancel

Cancels the current UI selection.

### LoadCity

Loads the named city.

Parameters: 
`<city name>` `<city size string>` `<city established string>`.

`<city name>` - if empty the game loads the first city it finds.    
`<city size string>` - one of _small_, _medium_, _large_, or _any_.    
`<city established string>` - either _empty_ (unestablished) or _full_ (established).

### LoadRegion

Loads the specified region.

Parameters: `<region name string>`

### QuitGame

Quits the game.

Parameters: `<true/false>` - Show the confirmation dialog.

### RegionBitmapLoad

Displays a file browser dialog to select the region bitmap.

### ScrollDown

Scrolls down.

### ScrollDownStop

Stops the previous *ScrollDown* command.

### ScrollLeft

Scrolls left.

### ScrollLeftStop

Stops the previous *ScrollLeft* command.

### ScrollRight

Scrolls right.

### ScrollRightStop

Stops the previous *ScrollRight* command.

### ScrollUp

Scrolls up.

### ScrollUpStop

Stops the previous *ScrollUp* command.

### SetExpandedToolTips

Sets a value indicating if the game should use expanded tool tips.

Parameters: `[true/false]`

When used without parameters the game will toggle the current value.