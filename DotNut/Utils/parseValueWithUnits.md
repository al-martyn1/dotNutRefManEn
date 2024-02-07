## DotNut.Utils.parseValueWithUnits function


```lua
function parseValueWithUnits( strValueWithUnits   // string
                            , valueType           // DotNut.ValueType
                            , caseMatch           // bool|DotNut.CaseMatchType
                            , units               // array of [string unitStr,integer unitValue]
                            , defaultUnits        // integer
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Parameters

**strValueWithUnits** (**string**) - ![strValueWithUnits]

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - ![valueType]

**caseMatch** (**bool** | [DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - ![caseMatch]

**units** (**array** of [**string** unitStr,**integer** unitValue]) - ![units]

**defaultUnits** (**integer**) - ![defaultUnits]

### Return value

Return type: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

