## Color
**Kind**: global interface

<a name="Color"></a>
* [Color](#Color)
    * _instance_
        * [.name](#Color+name) : <code>String</code>
        * [.originalName](#Color+originalName) : <code>String</code>
        * [.r](#Color+r) : <code>Number</code>
        * [.g](#Color+g) : <code>Number</code>
        * [.b](#Color+b) : <code>Number</code>
        * [.a](#Color+a) : <code>Number</code>
        * [.sourceId](#Color+sourceId) : <code>String</code>
        * [.getFormattedName(namingScheme)](#Color+getFormattedName) ⇒ <code>String</code>
        * [.equals(c)](#Color+equals) ⇒ <code>Boolean</code>
        * [.blend(c)](#Color+blend) ⇒ [<code>Color</code>](#Color)
        * [.toHex()](#Color+toHex) ⇒ <code>Object</code>
        * [.toHSL()](#Color+toHSL) ⇒ <code>Object</code>
    * _static_
        * [.blendAll(colors)](#Color.blendAll) ⇒ [<code>Color</code>](#Color)

<a name="Color+name"></a>

### color.name : <code>String</code>
`[DEPRECARED]` Formatted name of the color, only exists on project colors. Please use [`Color.originalName`](#Color+originalName) and [`Color.getFormattedName`](#Color+getFormattedName) instead.

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+originalName"></a>

### color.originalName : <code>String</code>
Name of the color, only exists on project colors. To check if a color (e.g. from a layer) exists in the project, see [`Project.findColorEqual`](project.md#Project+findColorEqual).

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+r"></a>

### color.r : <code>Number</code>
Red component of the color, [0, 255].

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+g"></a>

### color.g : <code>Number</code>
Green component of the color, [0, 255].

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+b"></a>

### color.b : <code>Number</code>
Blue component of the color, [0, 255].

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+a"></a>

### color.a : <code>Number</code>
Alpha component of the color, [0, 1].

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+sourceId"></a>

### color.sourceId : <code>String</code>
Id of the color in the source design document.

**Kind**: instance property of [<code>Color</code>](#Color)
<a name="Color+equals"></a>

### color.equals(c) ⇒ <code>Boolean</code>
Checks whether another color is equal to this one.

**Kind**: instance method of [<code>Color</code>](#Color)

| Param | Type | Description |
| --- | --- | --- |
| c | [<code>Color</code>](#Color) | Color object to be compared. |
<a name="Color+getFormattedName"></a>

### color.getFormattedName(namingScheme) ⇒ <code>String</code>
Formats name according to provided naming scheme.

**Kind**: instance method of [<code>Color</code>](#Color)

| Param | Type | Description |
| --- | --- | --- |
| namingScheme |`"snake"\|"camel"\|"pascal"\|"kebab"\|"constant"` | naming scheme to format the name. "constant" by default. |

<a name="Color+blend"></a>

### color.blend(c) ⇒ [<code>Color</code>](#Color)
Blends another color with this one, via alpha compositing.

**Kind**: instance method of [<code>Color</code>](#Color)

| Param | Type | Description |
| --- | --- | --- |
| c | [<code>Color</code>](#Color) | Color object to be blended. |

<a name="Color+toHex"></a>

### color.toHex() ⇒ <code>Object</code>
Hex representation of the color.

**Kind**: instance method of [<code>Color</code>](#Color)

**Properties**

| Name | Type |
| --- | --- |
| r | <code>Number</code> |
| g | <code>Number</code> |
| b | <code>Number</code> |
| a | <code>Number</code> |

<a name="Color+toHSL"></a>

### color.toHSL() ⇒ <code>Object</code>
HSLA representation of the color, e.g. `hsla(..., a)` or `hsl(...)`.

**Kind**: instance method of [<code>Color</code>](#Color)

**Properties**

| Name | Type |
| --- | --- |
| h | <code>Number</code> |
| s | <code>Number</code> |
| l | <code>Number</code> |

<a name="Color.blendAll"></a>

### Color.blendAll(colors) ⇒ [<code>Color</code>](#Color)
Blends multiple colors.

**Kind**: static method of [<code>Color</code>](#Color)

| Param | Type | Description |
| --- | --- | --- |
| colors | [<code>Array&lt;Color&gt;</code>](#Color) | List of color objects to be blended. |
