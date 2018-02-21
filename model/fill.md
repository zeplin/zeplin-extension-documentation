## Fill
**Kind**: global interface

<a name="Fill"></a>
* [Fill](#Fill)
    * _instance_
        * [.type](#Fill+type) : <code>String</code>
        * [.color](#Fill+color) : [<code>Color</code>](color.md)
        * [.gradient](#Fill+gradient) : [<code>Gradient</code>](gradient.md)
        * [.opacity](#Fill+opacity) : <code>Number</code>
        * [.blendMode](#Fill+blendMode) : [<code>BLEND_MODES</code>](#Fill.BLEND_MODES)
        * [.fill](#Fill+fill) : <code>Number</code>
    * _static_
        * [.BLEND_MODES](#Fill.BLEND_MODES) : <code>enum</code>

<a name="Fill+type"></a>

### fill.type : <code>String</code>
Type of the fill, `color` and `gradient`.

**Kind**: instance property of [<code>Fill</code>](#Fill)
<a name="Fill+color"></a>

### fill.color : [<code>Color</code>](color.md)
Color of the fill.

**Kind**: instance property of [<code>Fill</code>](#Fill)
<a name="Fill+gradient"></a>

### fill.gradient : [<code>Gradient</code>](gradient.md)
Gradient of the fill.

**Kind**: instance property of [<code>Fill</code>](#Fill)
<a name="Fill+opacity"></a>

### fill.opacity : <code>Number</code>
Opacity of the fill, [0, 1].

**Kind**: instance property of [<code>Fill</code>](#Fill)
<a name="Fill+blendMode"></a>

### fill.blendMode : [<code>BLEND_MODES</code>](#Fill.BLEND_MODES)
Blend mode of the fill, defined in [BLEND_MODES](#Fill.BLEND_MODES).

**Kind**: instance property of [<code>Fill</code>](#Fill)
<a name="Fill+fill"></a>

### Fill.BLEND_MODES : <code>enum</code>
Blend modes for a fill.

**Kind**: static enum of [<code>Fill</code>](#Fill)
**Properties**

| Name | Type | Default |
| --- | --- | --- |
| NORMAL | <code>String</code> | <code>normal</code> |
| DARKEN | <code>String</code> | <code>darken</code> |
| MULTIPLY | <code>String</code> | <code>multiply</code> |
| COLOR_BURN | <code>String</code> | <code>color-burn</code> |
| LIGHTEN | <code>String</code> | <code>lighten</code> |
| SCREEN | <code>String</code> | <code>screen</code> |
| COLOR_DODGE | <code>String</code> | <code>color-dodge</code> |
| OVERLAY | <code>String</code> | <code>overlay</code> |
| SOFT_LIGHT | <code>String</code> | <code>soft-light</code> |
| HARD_LIGHT | <code>String</code> | <code>hard-light</code> |
| DIFFERENCE | <code>String</code> | <code>difference</code> |
| EXCLUSION | <code>String</code> | <code>exclusion</code> |
| HUE | <code>String</code> | <code>hue</code> |
| SATURATION | <code>String</code> | <code>saturation</code> |
| COLOR | <code>String</code> | <code>color</code> |
| LUMINOSITY | <code>String</code> | <code>luminosity</code> |
| SOURCE_IN | <code>String</code> | <code>source-in</code> |
| SOURCE_OUT | <code>String</code> | <code>source-out</code> |
| SOURCE_ATOP | <code>String</code> | <code>source-atop</code> |
| DESTINATION_OVER | <code>String</code> | <code>destination-over</code> |
| DESTINATION_IN | <code>String</code> | <code>destination-in</code> |
| DESTINATION_OUT | <code>String</code> | <code>destination-out</code> |
| DESTINATION_ATOP | <code>String</code> | <code>destination-atop</code> |
| DISSOLVE | <code>String</code> | <code>dissolve</code> |
| LINEAR_BURN | <code>String</code> | <code>linear-burn</code> |
| LINEAR_DODGE | <code>String</code> | <code>linear-dodge</code> |
| DARKER_COLOR | <code>String</code> | <code>darker-color</code> |
| LIGHTER_COLOR | <code>String</code> | <code>lighter-color</code> |
| VIVID_LIGHT | <code>String</code> | <code>vivid-light</code> |
| LINEAR_LIGHT | <code>String</code> | <code>linear-light</code> |
| PIN_LIGHT | <code>String</code> | <code>pin-light</code> |
| HARD_MIX | <code>String</code> | <code>hard-mix</code> |
| SUBTRACT | <code>String</code> | <code>subtract</code> |
| DIVIDE | <code>String</code> | <code>divide</code> |
