## DotNut.Utils.parseValueWithUnits function


```lua
function parseValueWithUnits( strValueWithUnits                          // string
                            , valueType                                  // DotNut.ValueType
                            , caseMatch                                  // DotNut.CaseMatchType
                            , [string unitStr,integer|float unitValue]   // array of
                            , defaultUnits                               // integer|float
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Parameters

**strValueWithUnits** (**string**) - ![strValueWithUnits]

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - ![valueType]

**caseMatch** ([DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - ![caseMatch]

**[string unitStr,integer|float unitValue]** (**array** of) - ![[string unitStr,integer|float unitValue]]

**defaultUnits** (**integer** | **float**) - ![defaultUnits]

### Return value

Return type: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

