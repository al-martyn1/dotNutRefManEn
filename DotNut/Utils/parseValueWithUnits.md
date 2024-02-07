## DotNut.Utils.parseValueWithUnits function

Parse a string with units of measurement, for example: '12.5cm'.


```lua
function parseValueWithUnits( strValueWithUnits   // string
                            , valueType           // DotNut.ValueType
                            , caseMatch           // bool|DotNut.CaseMatchType
                            , units               // array of [string unitStr, integer unitValue]
                            , defaultUnits        // integer
                            )
// returns: table{DotNut.ErrorCode status, integer|float value, integer units}
```


### Parameters

**strValueWithUnits** (**string**) - An input string containing a value with units.

**valueType** ([DotNut.ValueType](../../DotNut/ValueType.md)) - value type, affects the characters allowed in the string and the type of the result (float | integer).

**caseMatch** (**bool** | [DotNut.CaseMatchType](../../DotNut/CaseMatchType.md)) - one of the values [DotNut.CaseMatchType](../../DotNut/CaseMatchType.md), or bool: false - for exact case matching, true - to ignore the case of characters in the unit of measurement.

**units** (**array** of [**string** unitStr, **integer** unitValue]) - an array of possible values of units of measurement in the form of pairs (arrays) of a string representation and an integer identifier.

**defaultUnits** (**integer**) - default units of measurement if they are not present in the string.

### Return value

Return type: **table**{[DotNut.ErrorCode](../../DotNut/ErrorCode.md) status, **integer** | **float** value, **integer** units}

- status ([DotNut.ErrorCode](../../DotNut/ErrorCode.md)) - error code, DotNut.ErrorCode.Ok, if the conversion was successful.
- value (integer | float) - value of the quantity
- units (integer) - unit identifier , one of those specified in the **units** parameter.



### Example

An example of parsing a length value; values can be specified in millimeters, centimeters, decimeters, meters and kilometers:
```lua
// Задаем сразу степени 10, по умолчанию - сантиметры
// Set up powers of ten, cm by default
local valWithUnits = DotNut.Utils.parseValueWithUnits( "10.5cm"
                                                     , DotNut.ValueType.ValueFloat
                                                     , DotNut.CaseMatchType.CaseIgnore
                                                     , [ ["mm",-3]
                                                       , ["cm",-2]
                                                       , ["dm",-1]
                                                       , ["m",0]
                                                       , ["km",3]
                                                       ]
                                                     , -2
                                                     );
if (valWithUnits.status!=DotNut.ErrorCode.Ok)
{
    smpprintln("Failed to parse value with units");
}
else
{
    smpprintln("Value with units, value module: [" + valWithUnits.value.tostring() + "], value units: [" + valWithUnits.units.tostring() + "]");
}
```
.
