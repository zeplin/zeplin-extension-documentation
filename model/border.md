## Border
**Kind**: global interface  

<a name="Border"></a>
* [Border](#Border)
    * [.position](#Border+position) : <code>String</code>
    * [.thickness](#Border+thickness) : <code>Number</code>
    * [.fill](#Border+fill) : <code>Fill</code>
    * [.dashPattern](#Border+dashPattern) : <code>DashPattern</code>
    * [.join](#Border+join) : <code>String</code>
    * [.miterLimit](#Border+miterLimit) : <code>Number</code>
    * [.individualThickness](#Border+individualThickness) : <code>IndividualThickness</code>
    * [.blendMode](#Border+blendMode) : [<code>Fill.BLEND_MODES</code>](fill.md)

<a name="Border+position"></a>

### border.position : <code>String</code>
Position of the border, `center`, `inside` or `outside`.

**Kind**: instance property of [<code>Border</code>](#Border)
<a name="Border+thickness"></a>

### border.thickness : <code>Number</code>
Thickness of the border, a positive integer.

**Kind**: instance property of [<code>Border</code>](#Border)
<a name="Border+fill"></a>

### border.fill : [<code>Fill</code>](fill.md)
Fill of the border.

**Kind**: instance property of [<code>Border</code>](#Border)
<a name="Border+dashPattern"></a>

### border.dashPattern : [<code>DashPattern</code>](dashPattern.md)
Dash pattern of the border.

**Kind**: instance property of [<code>Border</code>](#Border)
<a name="Border+join"></a>

### border.join : <code>String</code>
Type of the border join: `miter`, `round` or `bevel`.

**Kind**: instance property of [<code>Border</code>](#Border)
<a name="Border+miterLimit"></a>

### border.miterLimit : <code>Number</code>
A positive integer that denotes the limit of the miter if join type is `miter`.

**Kind**: instance property of [<code>Border</code>](#Border)
<a name="Border+individualThickness"></a>

### border.individualThickness : [<code>IndividualThickness</code>](individualThickness.md)
Individual thickness of the border if border has different thickness values.

**Kind**: instance property of [<code>Border</code>](#Border)

<a name="Border+blendMode"></a>

### border.blendMode : [<code>Fill.BLEND_MODES</code>](fill.md)
Blend mode of the border, defined in [Fill.BLEND_MODES](fill.md).

**Kind**: instance property of [<code>Border</code>](#Border)