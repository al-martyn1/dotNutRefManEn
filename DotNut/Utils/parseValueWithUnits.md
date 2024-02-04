## DotNut.Utils.parseValueWithUnits function


```lua
function parseValueWithUnits( strValueWithUnits   // string
                            , valueType           // DotNut.ValueType
                            , caseMatch           // DotNut.CaseMatchType
                            , units               // array of [string unitStr,integer|float unitValue]
                            , defaultUnits        // integer|float
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Parameters

**strValueWithUnits** (**string**) - ![strValueWithUnits]

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - ![valueType]

**caseMatch** ([DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - ![caseMatch]

**units** (**array** of [**string** unitStr,**integer** | **float** unitValue]) - ![units]

**defaultUnits** (**integer** | **float**) - ![defaultUnits]

### Return value

Return type: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

