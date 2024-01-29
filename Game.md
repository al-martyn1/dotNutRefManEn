## Game namespace
```lua
table /* namespace */ Game
{


    // Functions

    function onLoad( bFirstTime   // bool
                   )

    function onPaint( dc   // Drawing.Context
                    )

    function onUpdate( tickDelta   // integer
                     )
    // returns: Drawing::CallbackResultFlags

    function onKeyEvent( bDown     // bool
                       , vk        // DotNut.Vk.Code
                       , nRepCnt   // int
                       )
    // returns: Drawing::CallbackResultFlags

    function onMouseMoveEvents( dc             // Drawing.Context
                              , mmEventType    // Drawing.MouseMoveEventType
                              , mbStateFlags   // Drawing.MouseButtonStateFlags
                              , pos            // Drawing.Coords
                              )
    // returns: Drawing::CallbackResultFlags

    function onMouseButtonEvents( dc             // Drawing.Context
                                , mouseButton    // Drawing.MouseButton
                                , mbEvent        // Drawing.MouseButtonEvent
                                , mbStateFlags   // Drawing.MouseButtonStateFlags
                                , pos            // Drawing.Coords
                                )
    // returns: Drawing::CallbackResultFlags

    function onMouseWheel( dc             // Drawing.Context
                         , zDelta         // integer
                         , mbStateFlags   // Drawing.MouseButtonStateFlags
                         , pos            // Drawing.Coords
                         )
    // returns: Drawing::CallbackResultFlags

    function onWindowSize( wszRequestType   // Drawing.WindowSizeRequestType
                         , size             // Drawing.Coords
                         )
    // returns: Drawing::CallbackResultFlags

    function onWindowSizing( sizingEdge   // Drawing.WindowSizingEventEdge
                           , size         // Drawing.Coords
                           )
    // returns: Drawing::CallbackResultFlags

    function onMouseCaptureLoss()
    // returns: Drawing::CallbackResultFlags

    function onCreate( clientAreaSize   // Drawing.Coords
                     )
    // returns: Drawing::CallbackResultFlags



} // table namespace Game
```


### Functions


[Game.onLoad](Game/onLoad.md) - ![__BRIEF]


[Game.onPaint](Game/onPaint.md) - ![__BRIEF]


[Game.onUpdate](Game/onUpdate.md) - ![__BRIEF]


[Game.onKeyEvent](Game/onKeyEvent.md) - ![__BRIEF]


[Game.onMouseMoveEvents](Game/onMouseMoveEvents.md) - ![__BRIEF]


[Game.onMouseButtonEvents](Game/onMouseButtonEvents.md) - ![__BRIEF]


[Game.onMouseWheel](Game/onMouseWheel.md) - ![__BRIEF]


[Game.onWindowSize](Game/onWindowSize.md) - ![__BRIEF]


[Game.onWindowSizing](Game/onWindowSizing.md) - ![__BRIEF]


[Game.onMouseCaptureLoss](Game/onMouseCaptureLoss.md) - ![__BRIEF]


[Game.onCreate](Game/onCreate.md) - ![__BRIEF]


