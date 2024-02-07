## DotNut.Utils namespace
```lua
table /* namespace */ DotNut.Utils
{


    // Functions

    function parseValueWithUnits( strValueWithUnits   // string
                                , valueType           // DotNut.ValueType
                                , caseMatch           // bool|DotNut.CaseMatchType
                                , units               // array of [string unitStr, integer unitValue]
                                , defaultUnits        // integer
                                )
    // returns: table{DotNut.ErrorCode status, integer|float value, integer units}



} // table namespace DotNut.Utils
```


### Functions


[parseValueWithUnits](../DotNut/Utils/parseValueWithUnits.md) - Parse a string with units of measurement, for example: '12.5cm'.

