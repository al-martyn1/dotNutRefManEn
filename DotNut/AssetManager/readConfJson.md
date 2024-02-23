## DotNut.AssetManager.readConfJson method

Reads text file from '/conf' folder of application distribution/package and parse it as JSON to table.


```lua
function readConfJson( confJsonFileName   // string
                     )
// returns: table{DotNut.ErrorCode status, table data, string message}
```


### Parameters

**confJsonFileName** (**string**) - requested file name for reading.

### Return value

Return type: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **table** data, **string** message}



### Remarks

If an any error occurs, empty table will be returned.
