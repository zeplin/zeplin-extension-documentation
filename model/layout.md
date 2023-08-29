## Layout
**Kind**: global interface

<a name="Layout"></a>
* [Layout](#Layout)
    * _instance_
        * [.direction](#Layout+direction) : [<code>DIRECTION</code>](#Layout.DIRECTION)
        * [.padding](#Layout+padding) : <code>Object</code>
        * [.gap](#Layout+gap) : <code>Number</code>
        * [.sizingMode](#Layout+sizingMode) : [<code>SIZING_MODE</code>](#Layout.SIZING_MODE)
        * [.itemAlignment](#Layout+itemAlignment) : [<code>ALIGNMENT</code>](#Layout.ALIGNMENT)
        * [.distribution](#Layout+distribution) : [<code>DISTRIBUTION</code>](#Layout.DISTRIBUTION)
        * [.wrap](#Layout+wrap) : <code>Boolean</code>
        * [.wrapGap](#Layout+wrapGap) : <code>Number</code>
    * _static_
        * [.DIRECTION](#Layout.DIRECTION) : <code>enum</code>
        * [.SIZING_MODE](#Layout.SIZING_MODE) : <code>enum</code>
        * [.ALIGNMENT](#Layout.ALIGNMENT) : <code>enum</code>

<a name="Layout+direction"></a>
### layout.direction : <code>String</code>
Determines how the children of the layer are laid out in this layer:
 - `"row"`: The children are placed on a line horizontally
 - `"column"`: The children are stacked vertically

**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout+padding"></a>
### layout.padding : <code>Object</code>
Padding between the borders of the layer and its children.

**Kind**: instance property of [<code>Layout</code>](#Layout)

**Properties**

| Name | Type |
| --- | --- |
| horizontal | <code>Number</code> |
| vertical | <code>Number</code> |

<a name="Layout+gap"></a>
### layout.gap : <code>Number</code>
Distance between children of the layer.

**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout+sizingMode"></a>
### layout.sizingMode : <code>String</code>
Determines if the layer has fixed or automatic length for its axis which is orthogonal to its layout direction, i.e., its width if `Layer.direction` is `"column"` or its height if `Layer.direction` is `"row"`.

**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout+itemAlignment"></a>
### layout.itemAlignment : <code>String</code>
Determines how the children are aligned inside the layer in the counter axis direction.

When layout direction is `"row"`:
- `"min"`: Align the children to the top of the layer
- `"max"`: Align the children to the bottom of the layer
- `"center"`: Vertically center the children
- `"baseline"`: Aligns all children along the text baseline

When layout direction is `"column"`:
- `"min"`: Align the children to the left of the layer
- `"max"`: Align the children to the right of the layer 
- `"center"`: Horizontally center the children
- `"baseline"`: NOT applicable for this direction

**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout+distribution"></a>
### layout.distribution : <code>String</code>
Determines how the children should be aligned inside the layer in the primary axis direction.

When layout direction is `"row"`:
- `"min"`: Align the children to the left of the layer
- `"max"`: Align the children to the right of the layer
- `"center"`: Horizontally center the children
- `"space-between"`: Align the children to space themselves evenly by putting the extra space between them

When layout direction is `"column"`:
- `"min"`: Align the children to the top of the layer
- `"max"`: Align the children to the bottom of the layer
- `"center"`: Vertically center the children
- `"space-between"`: Align the children to space themselves evenly by putting the extra space between them


**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout+wrap"></a>
### layout.wrap : <code>Boolean</code>
Indicates whether the children wraps if they don't fit the width/height.

**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout+wrapGap"></a>
### layout.wrapGap : <code>Number</code>
Spacing in counter axis of the direction.

**Kind**: instance property of [<code>Layout</code>](#Layout)

<a name="Layout.DIRECTION"></a>
### Layout.DIRECTION : <code>enum</code>
Directions for a layout.

**Kind**: static enum of [<code>Layout</code>](#Layout)
**Properties**

| Name | Type | Default |
| --- | --- | --- |
| ROW | <code>String</code> | <code>row</code> |
| COLUMN | <code>String</code> | <code>column</code> |

<a name="Layout.SIZING_MODE"></a>
### Layout.SIZING_MODE : <code>enum</code>
Sizing mode for a layout.

**Kind**: static enum of [<code>Layout</code>](#Layout)
**Properties**

| Name | Type | Default |
| --- | --- | --- |
| FIXED | <code>String</code> | <code>fixed</code> |
| AUTO | <code>String</code> | <code>auto</code> |

<a name="Layout.ALIGNMENT"></a>
### Layout.ALIGNMENT : <code>enum</code>
Alignment for a layout.

**Kind**: static enum of [<code>Layout</code>](#Layout)
**Properties**

| Name | Type | Default |
| --- | --- | --- |
| MIN | <code>String</code> | <code>min</code> |
| CENTER | <code>String</code> | <code>center</code> |
| MAX | <code>String</code> | <code>max</code> |
| STRETCH | <code>String</code> | <code>stretch</code> |
| INHERIT | <code>String</code> | <code>inherit</code> |
| BASELINE | <code>String</code> | <code>baseline</code> |

<a name="Layout.DISTRIBUTION"></a>
### Layout.DISTRIBUTION : <code>enum</code>
Distribution for children of layout.

**Kind**: static enum of [<code>Layout</code>](#Layout)
**Properties**

| Name | Type | Default |
| --- | --- | --- |
| CENTER | <code>String</code> | <code>center</code> |
| MAX | <code>String</code> | <code>max</code> |
| MIN | <code>String</code> | <code>min</code> |
| SPACE_BETWEEN | <code>String</code> | <code>space-between</code> |
