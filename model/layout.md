## Layout
**Kind**: global interface

<a name="Layout"></a>
* [Layout](#Layout)
    * [.direction](#Layout+direction) : <code>String</code>
    * [.padding](#Layout+padding) : <code>Object</code>
    * [.gap](#Layout+gap) : <code>Number</code>
    * [.sizingMode](#Layout+sizingMode) : <code>String</code>
    * [.alignment](#Layout+alignment) : <code>String</code>

<a name="Layout+direction"></a>
### layout.direction : <code>String</code>
Determines how the children of the layer are laid out in this layer:
 - "row": The children are placed on a line horizontally
 - "column": The children are stacked vertically

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

<a name="Layout+alignment"></a>
### layout.alignment : <code>String</code>
Determines how the children are aligned inside the layer.

- When layout direction is `"row"`, `"min"` and `"max"` correspond to `"top"` and `"bottom"`.
- When layout direction is `"column"`, `"min"` and `"max"` correspond to `"left"` and `"right"`.
- Setting `"stretch"` will make the node `"stretch"` to fill the width of layers with `"column"` direction, or the height of layers with `"row"` direction.

**Kind**: instance property of [<code>Layout</code>](#Layout)
