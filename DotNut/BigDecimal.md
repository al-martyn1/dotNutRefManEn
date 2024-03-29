## DotNut.BigDecimal class


```lua
class DotNut.BigDecimal
{
    // Functions

    constructor( v   // bool|integer|float|string|DotNut.BigDecimal|DotNut.Integer64
               )

    function _add( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _sub( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _unm( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _mul( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _div( v   // DotNut.BigDecimal
                 )
    // returns: DotNut.BigDecimal

    function _cmp( v   // DotNut.BigDecimal
                 )
    // returns: integer

    function divEx( v           // DotNut.BigDecimal
                  , precision   // integer
                  )
    // returns: DotNut.BigDecimal

    function precision()
    // returns: integer

    function round( precision        // integer
                  , roundingMethod   // DotNut.BigDecimalRoundingMethod
                  )
    // returns: DotNut.BigDecimal

    function isZero()
    // returns: bool

    function izr()
    // returns: bool

    function sgn()
    // returns: integer

    function abs()
    // returns: DotNut.BigDecimal

    function neg()
    // returns: DotNut.BigDecimal

    function toStringEx( precision   // integer
                       )
    // returns: string

    function tostring()
    // returns: string

    function _tostring()
    // returns: string

    function tointeger()
    // returns: integer

    function tointeger64()
    // returns: DotNut.Integer64

    function tofloat()
    // returns: float


} // class DotNut.BigDecimal
```



### Methods


[constructor](../DotNut/BigDecimal/constructor.md) - ![__BRIEF]


**_add** - Support for the 'plus' ('+') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) for details.


**_sub** - Support for the 'minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) for details.


**_unm** - Support for the 'unary minus' ('-') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) for details.


**_mul** - Support for the 'multiply' ('*') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) for details.


**_div** - Support for the 'divide' ('/') operator. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) for details.


**_cmp** - Support for the compare (<, >, <=, >=, ==, !=) operators. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#cmp) for details.


[divEx](../DotNut/BigDecimal/divEx.md) - ![__BRIEF]


[precision](../DotNut/BigDecimal/precision.md) - ![__BRIEF]


[round](../DotNut/BigDecimal/round.md) - ![__BRIEF]


[isZero](../DotNut/BigDecimal/isZero.md) - ![__BRIEF]


[izr](../DotNut/BigDecimal/izr.md) - ![__BRIEF]


[sgn](../DotNut/BigDecimal/sgn.md) - ![__BRIEF]


[abs](../DotNut/BigDecimal/abs.md) - ![__BRIEF]


[neg](../DotNut/BigDecimal/neg.md) - ![__BRIEF]


[toStringEx](../DotNut/BigDecimal/toStringEx.md) - ![__BRIEF]


**tostring** - Convert the value to string and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) for details. Exposed for compatibility with built-in types. The toString() method has also been implemented to comply with camelCase naming conventions.


**_tostring** - Conversion to string support. See [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) for details.


**tointeger** - Convert the value to integer and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#integer) for details. Exposed for compatibility with built-in types. The toInteger() method has also been implemented to comply with camelCase naming conventions.


**tointeger64** - Convert the value to DotNut.Integer64 and returns it. The toInteger64() method has also been implemented to comply with camelCase naming conventions.


**tofloat** - Convert the value to float and returns it, see [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#float) for details. Exposed for compatibility with built-in types. The toFloat() method has also been implemented to comply with camelCase naming conventions.


