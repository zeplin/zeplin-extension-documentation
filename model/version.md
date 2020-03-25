## Version
**Kind**: global interface

<a name="Version"></a>
* [Version](#Version)
    * [.source](#Version+source) : <code>String</code>
    * [.image](#Version+image) : <code>Object</code>
    * [.backgroundColor](#Version+backgroundColor) : [<code>Color</code>](color.md)
    * [.layers](#Version+layers) : [<code>Array&lt;Layer&gt;</code>](layer.md)
    * [.links](#Version+links) : <code>Array&lt;Object&gt;</code>
    * [.grid](#Version+grid) : <code>Object</code>
    * [.componentNames](#Version+componentNames) : <code>Array&lt;String&gt;</code>

<a name="Version+source"></a>
### version.source : <code>String</code>
Source application of the version, `sketch`, `xd`, `figma`, `psd` or `bitmap`.

**Kind**: instance property of [<code>Version</code>](#Version)

<a name="Version+image"></a>
### version.image : <code>Object</code>
Image of the version.

**Kind**: instance property of [<code>Version</code>](#Version)

**Properties**

| Name | Type |
| --- | --- |
| url | <code>String</code> |
| width | <code>Number</code> |
| height | <code>Number</code> |

<a name="Version+backgroundColor"></a>
### version.backgroundColor : [<code>Color</code>](color.md)
Background color of the version.

**Kind**: instance property of [<code>Version</code>](#Version)

<a name="Version+layers"></a>
### version.layers : [<code>Array&lt;Layer&gt;</code>](layer.md)
Layers of the version.

**Kind**: instance property of [<code>Version</code>](#Version)

<a name="Version+links"></a>
### version.links : <code>Array&lt;Object&gt;</code>
Links to other screens in the version.

**Kind**: instance property of [<code>Version</code>](#Version)

**Properties**

| Name | Type | Description |
| --- | --- | --- |
| rect | <code>Object</code> | Bounding rectangle of the link. |
| destination | <code>Object</code> | Destination of the link. |
| rect.x | <code>Number</code> | — |
| rect.y | <code>Number</code> | — |
| rect.width | <code>Number</code> | — |
| rect.height | <code>Number</code> | — |
| destination.name | <code>String</code> | Name of the screen destination. |
| destination.type | <code>String</code> | Type of the destination, `screen` or `previous`. |

<a name="Version+grid"></a>
### version.grid : <code>Object</code>
Grid (i.e. layout) of the version.

**Kind**: instance property of [<code>Version</code>](#Version)

**Properties**

| Name | Type |
| --- | --- |
| horizontalOffset | <code>Number</code> |
| vertical | <code>Object</code> |
| horizontal | <code>Object</code> |
| vertical.gutterWidth | <code>Number</code> |
| vertical.columnWidth | <code>Number</code> |
| vertical.numberOfCols | <code>Number</code> |
| vertical.guttersOnOutside | <code>Boolean</code> |
| horizontal.gutterHeight | <code>Number</code> |
| horizontal.rowHeight | <code>Number</code> |

<a name="Version+componentNames"></a>
### version.componentNames : <code>Array&lt;String&gt;</code>
Names of components used in the version.

**Kind**: instance property of [<code>Version</code>](#Version)

### Related models

- [`Screen`](screen.md)
- [`Component`](component.md)
