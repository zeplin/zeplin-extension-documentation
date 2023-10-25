## TextStyle
**Kind**: global interface

<a name="TextStyle"></a>
* [TextStyle](#TextStyle)
    * [.name](#TextStyle+name) : <code>String</code>
    * [.sourceId](#TextStyle+sourceId) : <code>String</code>
    * [.fontFace](#TextStyle+fontFace) : <code>String</code>
    * [.fontSize](#TextStyle+fontSize) : <code>Number</code>
    * [.fontWeight](#TextStyle+fontWeight) : <code>Number</code>
    * [.fontStyle](#TextStyle+fontStyle) : <code>String</code>
    * [.fontFamily](#TextStyle+fontFamily) : <code>String</code>
    * [.fontStretch](#TextStyle+fontStretch) : <code>String</code>
    * [.lineHeight](#TextStyle+lineHeight) : <code>Number</code>
    * [.textAlign](#TextStyle+textAlign) : <code>String</code>
    * [.verticalAlignment](#TextStyle+verticalAlignment) : <code>String</code>
    * [.letterSpacing](#TextStyle+letterSpacing) : <code>Number</code>
    * [.color](#TextStyle+color) : [<code>Color</code>](color.md)
    * [.weightText](#TextStyle+weightText) : <code>String</code>
    * [.equals(t)](#TextStyle+equals) ⇒ <code>Boolean</code>
    * [.paragraphSpacing](#TextStyle+paragraphSpacing) : <code>Number</code>
    * [.paragraphIndent](#TextStyle+paragraphIndent) : <code>Number</code>
    * [.listSpacing](#TextStyle+listSpacing) : <code>Number</code>
    * [.hyperlink](#TextStyle+hyperlink) : <code>String</code>    
    * [.textDecoration](#TextStyle+textDecoration) : [<code>TextDecoration</code>](textDecoration.md)
    * [.textTransform](#TextStyle+textTransform) : [<code>TEXT_TRANSFORM</code>](#TextStyle.TEXT_TRANSFORM)
  * _static_
    * [.TEXT_TRANSFORM](#TextStyle.TEXT_TRANSFORM) : <code>enum</code>
<a name="TextStyle+name"></a>

### textStyle.name : <code>String</code>
Name of the text style, only exists on project text styles. To check if a text style (e.g. from a layer) exists in the project, see [`Project.findTextStyleEqual`](project.md#Project+findTextStyleEqual).

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle+sourceId"></a>

### textStyle.sourceId : <code>String</code>
Id of the text style in the source design document.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+fontFace"></a>

### textStyle.fontFace : <code>String</code>
Complete font name of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+fontSize"></a>

### textStyle.fontSize : <code>Number</code>
Font size of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+fontWeight"></a>

### textStyle.fontWeight : <code>Number</code>
Font weight of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+fontStyle"></a>

### textStyle.fontStyle : <code>String</code>
Font style of the text style, e.g. `italic`, `oblique`.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+fontFamily"></a>

### textStyle.fontFamily : <code>String</code>
Font family of the text style, e.g. `Roboto`, `Arial`.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+fontStretch"></a>

### textStyle.fontStretch : <code>String</code>
Font stretch form of the text style, e.g. `condensed`, `expanded`.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+lineHeight"></a>

### textStyle.lineHeight : <code>Number</code>
Minimum height of a line for the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+textAlign"></a>

### textStyle.textAlign : <code>String</code>
Horizontal alignment of the text style, `left`, `right`, `center`, or `justify`.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+verticalAlignment"></a>

### textStyle.verticalAlignment : <code>String</code>
Vertical alignment of the text style, `top`, `center`, or `bottom`.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+letterSpacing"></a>

### textStyle.letterSpacing : <code>Number</code>
Letter spacing of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+color"></a>

### textStyle.color : [<code>Color</code>](color.md)
Color of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+weightText"></a>

### textStyle.weightText : <code>String</code>
Textual representation of the text style's weight, e.g. `bold` for 700, `medium` for 500.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)
<a name="TextStyle+equals"></a>

### textStyle.equals(t) ⇒ <code>Boolean</code>
Checks whether another text style. is equal to this one.

**Kind**: instance method of [<code>TextStyle</code>](#TextStyle)

| Param | Type | Description |
| --- | --- | --- |
| t | [<code>TextStyle</code>](#TextStyle) | TextStyle object to be compared. |


<a name="TextStyle+paragraphSpacing"></a>
### textStyle.paragraphSpacing : <code>Number</code>
Paragraph spacing of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle+paragraphIndent"></a>
### textStyle.paragraphIndent : <code>Number</code>
Paragraph indent of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle+listSpacing"></a>
### textStyle.listSpacing : <code>Number</code>
List spacing of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle+hyperlink"></a>

### textStyle.hyperlink : <code>String</code>
Hyperlink of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle+textDecoration"></a>
### textStyle.textDecoration : [<code>TextDecoration</code>](textDecoration.md)
Text decoration of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle+textTransform"></a>
### textStyle.textTransform : [<code>TEXT_TRANSFORM</code>](#TextStyle.TEXT_TRANSFORM)
Text transform of the text style.

**Kind**: instance property of [<code>TextStyle</code>](#TextStyle)

<a name="TextStyle.TEXT_TRANSFORM"></a>
### TextStyle.TEXT_TRANSFORM : <code>enum</code>
Text transforms for a text style.

**Kind**: static enum of [<code>TextStyle</code>](#TextStyle)
**Properties**

| Name      | Type                | Default                |
|-----------|---------------------|------------------------|
| UPPERCASE | <code>String</code> | <code>uppercase</code> |
| LOWERCASE | <code>String</code> | <code>lowercase</code> |
| TITLECASE | <code>String</code> | <code>titlecase</code> |
