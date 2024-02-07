## DotNut.Tr namespace


Service for application localization (translation). Provides an API for obtaining localized messages.
```lua
table /* namespace */ DotNut.Tr
{


    // Functions

    function setDefLang( langId   // string
                       )
    // returns: string

    function getDefLang()
    // returns: string

    function setDefCategory( catId   // string
                           )
    // returns: string

    function getDefCategory()
    // returns: string

    function tr( msgId   // string
               )
    // returns: string

    function tr2( msgId   // string
                , catId   // string
                )
    // returns: string

    function tr3( msgId    // string
                , catId    // string
                , langId   // string
                )
    // returns: string

    function msgHasTr( msgId   // string
                     )
    // returns: bool

    function msgHasTr2( msgId   // string
                      , catId   // string
                      )
    // returns: bool

    function msgHasTr3( msgId    // string
                      , catId    // string
                      , langId   // string
                      )
    // returns: bool



} // table namespace DotNut.Tr
```


### Functions


[setDefLang](../DotNut/Tr/setDefLang.md) - Sets the default messages localization language.


[getDefLang](../DotNut/Tr/getDefLang.md) - Returns the current default locale language.


[setDefCategory](../DotNut/Tr/setDefCategory.md) - Set the default message category.


[getDefCategory](../DotNut/Tr/getDefCategory.md) - Returns the current messages category ID, which is the default for obtaining localized messages.


[tr](../DotNut/Tr/tr.md) - Returns a localized message string.


[tr2](../DotNut/Tr/tr2.md) - Returns a localized message string given the specified category.


[tr3](../DotNut/Tr/tr3.md) - Returns a localized message string based on the specified category and language.


[msgHasTr](../DotNut/Tr/msgHasTr.md) - Checks whether a message has a localization.


[msgHasTr2](../DotNut/Tr/msgHasTr2.md) - Checks whether a post in a category is localized.


[msgHasTr3](../DotNut/Tr/msgHasTr3.md) - Checks for localization for a post in a category for the specified language.

