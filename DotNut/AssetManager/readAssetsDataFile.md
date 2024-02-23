## DotNut.AssetManager.readAssetsDataFile method

Reads binary file from '/assets' folder of application distribution/package.


```lua
function readAssetsDataFile( assetFileName   // string
                           )
// returns: DotNut.BinaryData
```


### Parameters

**assetFileName** (**string**) - requested file name for reading.

### Return value

Return type: [DotNut.BinaryData](../../DotNut/BinaryData.md)



### Remarks

If an any error occurs, empty object will be returned.
