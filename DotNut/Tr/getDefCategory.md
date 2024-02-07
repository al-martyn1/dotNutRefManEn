## DotNut.Tr.getDefCategory function

Returns the current messages category ID, which is the default for obtaining localized messages.


```lua
function getDefCategory()
// returns: string
```


When setting a default message category, it is not necessary to call the [DotNut/Tr/tr2](../../DotNut/Tr/tr2.md) or [DotNut/Tr/tr3](../../DotNut/Tr/tr3.md) function; to obtain a localized message, it is enough to call the [DotNut/Tr/tr](../../DotNut/Tr/tr.md) function.


### Parameters

This function has no parameters.

### Return value

Return type: **string**

Returns the default category value.

