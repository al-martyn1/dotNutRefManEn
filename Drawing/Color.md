## Drawing.Color class


```lua
class Drawing.Color
{
    // Member Fields

    r; // integer
    g; // integer
    b; // integer
    a; // integer


    // Functions

    constructor( clrInit   // integer|float|string|array of integer[r,g,b,a]|Drawing.Color
               )

    static
    function fromRgb( r   // integer
                    , g   // integer
                    , b   // integer
                    )
    // returns: Drawing.Color

    static
    function fromUnsigned( u   // integer
                         )
    // returns: Drawing.Color

    static
    function fromInt( u   // integer
                    )
    // returns: Drawing.Color

    static
    function fromInteger( u   // integer
                        )
    // returns: Drawing.Color

    static
    function fromString( nameOrIntStr   // string
                       )
    // returns: Drawing.Color

    function toUnsigned()
    // returns: integer

    function toInt()
    // returns: integer

    function tointeger()
    // returns: integer

    function tofloat()
    // returns: float

    function tostring()
    // returns: string

    function _tostring()
    // returns: string


} // class Drawing.Color
```



### Member fields

**r** (**integer**) - ![r]

**g** (**integer**) - ![g]

**b** (**integer**) - ![b]

**a** (**integer**) - ![a]


### Methods


[constructor](../Drawing/Color/constructor.md) - ![__BRIEF]


[fromRgb](../Drawing/Color/fromRgb.md) - ![__BRIEF]


[fromUnsigned](../Drawing/Color/fromUnsigned.md) - ![__BRIEF]


[fromInt](../Drawing/Color/fromInt.md) - ![__BRIEF]


[fromInteger](../Drawing/Color/fromInteger.md) - ![__BRIEF]


[fromString](../Drawing/Color/fromString.md) - ![__BRIEF]


[toUnsigned](../Drawing/Color/toUnsigned.md) - ![__BRIEF]


[toInt](../Drawing/Color/toInt.md) - ![__BRIEF]


**tointeger** - Convert the value to integer and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) for details. Exposed for compatibility with built-in types. The toInteger() method has also been implemented to comply with camelCase naming conventions.


**tofloat** - Convert the value to float and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) for details. Exposed for compatibility with built-in types. The toFloat() method has also been implemented to comply with camelCase naming conventions.


**tostring** - Convert the value to string and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) for details. Exposed for compatibility with built-in types. The toString() method has also been implemented to comply with camelCase naming conventions.


**_tostring** - Conversion to string support. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) for details.


