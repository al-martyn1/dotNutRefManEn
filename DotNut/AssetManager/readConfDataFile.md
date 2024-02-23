## DotNut.AssetManager.readConfDataFile method

Reads binary file from '/conf' folder of application distribution/package.


```lua
function readConfDataFile( confFileName   // string
                         )
// returns: DotNut.BinaryData
```


### Parameters

**confFileName** (**string**) - requested file name for reading.

### Return value

Return type: [DotNut.BinaryData](../../DotNut/BinaryData.md)



### Remarks

If an any error occurs, empty object will be returned.
