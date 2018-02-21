## Project
**Kind**: global interface

<a name="Project"></a>
* [Project](#Project)
    * [.type](#Project+type) : <code>String</code>
    * [.name](#Project+name) : <code>String</code>
    * [.textStyles](#Project+textStyles) : [<code>Array.&lt;TextStyle&gt;</code>](textStyle.md)
    * [.colors](#Project+colors) : [<code>Array.&lt;Color&gt;</code>](color.md)
    * [.density](#Project+density) : <code>String</code>
    * [.densityDivisor](#Project+densityDivisor) : <code>Number</code>
    * [.lengthUnit](#Project+lengthUnit) : <code>String</code>
    * [.textLengthUnit](#Project+textLengthUnit) : <code>String</code>
    * [.findTextStyleByName(name)](#Project+findTextStyleByName) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findTextStyleEqual(textStyle)](#Project+findTextStyleEqual) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findColorByName(name)](#Project+findColorByName) ⇒ [<code>Color</code>](color.md)
    * [.findColorEqual(color)](#Project+findColorEqual) ⇒ [<code>Color</code>](color.md)
    * [.findColorByHexAndAlpha(values)](#Project+findColorByHexAndAlpha) ⇒ [<code>Color</code>](color.md)

<a name="Project+type"></a>

### project.type : <code>String</code>
Type of the project, `web`, `android`, `ios` or `macos`.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+name"></a>

### project.name : <code>String</code>
Name of the project.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+textStyles"></a>

### project.textStyles : [<code>Array.&lt;TextStyle&gt;</code>](textStyle.md)
Text styles in the Styleguide.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+colors"></a>

### project.colors : [<code>Array.&lt;Color&gt;</code>](color.md)
Colors in the Styleguide.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+density"></a>

### project.density : <code>String</code>
Pixel density of the project.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+densityDivisor"></a>

### project.densityDivisor : <code>Number</code>
Divisor corresponding to the density, used to obtain actual values from unit values.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+lengthUnit"></a>

### project.lengthUnit : <code>String</code>
Length unit of the project, based on the type, e.g. `px` for Web, `pt` for iOS.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+textLengthUnit"></a>

### project.textLengthUnit : <code>String</code>
Text length unit of the project, based on the type, e.g. `dp` for Android.

**Kind**: instance property of [<code>Project</code>](#Project)
<a name="Project+findTextStyleByName"></a>

### project.findTextStyleByName(name) ⇒ [<code>TextStyle</code>](textStyle.md)
Finds text style in the project by name.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type |
| --- | --- |
| name | <code>String</code> |

<a name="Project+findTextStyleEqual"></a>

### project.findTextStyleEqual(textStyle) ⇒ [<code>TextStyle</code>](textStyle.md)
Finds text style in the project equal to another text style.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type |
| --- | --- |
| textStyle | <code>TextStyle</code> |

<a name="Project+findColorByName"></a>

### project.findColorByName(name) ⇒ [<code>Color</code>](color.md)
Finds color in the project by name.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type |
| --- | --- |
| name | <code>String</code> |

<a name="Project+findColorEqual"></a>

### project.findColorEqual(color) ⇒ [<code>Color</code>](color.md)
Finds color in the project equal to another color.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type |
| --- | --- |
| color | <code>Color</code> |

<a name="Project+findColorByHexAndAlpha"></a>

### project.findColorByHexAndAlpha(values) ⇒ [<code>Color</code>](color.md)
Finds color in the project by hex and alpha values.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| values | <code>Object</code> |  |
| values.hex | <code>String</code> | Hex string for RGB components of the color, e.g. `rrggbb`. |
| values.alpha | <code>String</code> | Alpha value of the color. |
