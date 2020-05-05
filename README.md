# Debug functionalities for Lua.
### [Stanley](https://github.com/Wolf2789/Stanley) package for simple debugging operations in Lua.

## Features
* dump variable content to string
* print message according to verbose level
* use different verbose levels for different debug messages
* getting required number of arguments for function

## Usage
```lua
local var = 'string variable'
local tab = {'table', variable = 3}
debug.verbose = 3 -- set verbose level
debug('Print message if verbose level >= 1')
debug(3, 'Print message if verbose level >= 3')
debug(2, 'Dump variable if verbose level >= 2', var)
debug('Dump table if verbose level >= 1', tab)
```
