## Layer
**Kind**: global interface

<a name="Layer"></a>
* [Layer](#Layer)
    * [.type](#Layer+type) : <code>String</code>
    * [.name](#Layer+name) : <code>String</code>
    * [.sourceId](#Layer+sourceId) : <code>String</code>
    * [.componentSourceId](#Layer+componentSourceId) : <code>String</code>
    * [.rect](#Layer+rect) : <code>Object</code>
    * [.layout](#Layer+layout) : [<code>Layout</code>](layout.md)
    * [.fills](#Layer+fills) : [<code>Array&lt;Fill&gt;</code>](fill.md)
    * [.borders](#Layer+borders) : [<code>Array&lt;Border&gt;</code>](border.md)
    * [.shadows](#Layer+shadows) : [<code>Array&lt;Shadow&gt;</code>](shadow.md)
    * [.blur](#Layer+blur) : [<code>Blur</code>](blur.md)
    * [.opacity](#Layer+opacity) : <code>Number</code>
    * [.blendMode](#Layer+blendMode) : [<code>Fill.BLEND_MODES</code>](fill.md)
    * [.borderRadius](#Layer+borderRadius) : <code>Number</code>
    * [.rotation](#Layer+rotation) : <code>Number</code>
    * [.exportable](#Layer+exportable) : <code>Boolean</code>
    * [.assets](#Layer+assets) : <code>Array&lt;Object&gt;</code>
    * [.parent](#Layer+parent) : [<code>Layer</code>](#Layer)
    * [.version](#Layer+version) : [<code>Version</code>](version.md)
    * [.content](#Layer+content) : <code>String</code>
    * [.textStyles](#Layer+textStyles) : <code>Array&lt;Object&gt;</code>
    * [.layers](#Layer+layers) : [<code>Array&lt;Layer&gt;</code>](layer.md)
    * [.componentName](#Layer+componentName) : <code>String</code>
    * [.inspectable](#Layer+inspectable) : <code>Boolean</code>
    * [.cornerRadius](#Layer+cornerRadius) : [<code>CornerRadius</code>](cornerRadius.md)

<a name="Layer+type"></a>
### layer.type : <code>String</code>
Type of the layer, `text`, `shape` or `group`.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+name"></a>
### layer.name : <code>String</code>
Name of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+sourceId"></a>
### layer.sourceId : <code>String</code>
Id of the layer in the source design document.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+componentSourceId"></a>
### layer.componentSourceId : <code>String</code>
Id of the related component in the source design document.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+rect"></a>
### layer.rect : <code>Object</code>
Bounding rectangle of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

**Properties**

| Name | Type |
| --- | --- |
| x | <code>Number</code> |
| y | <code>Number</code> |
| width | <code>Number</code> |
| height | <code>Number</code> |

<a name="Layer+layout"></a>
### layer.layout : [<code>Layout</code>](layout.md)
Layout properties of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+fills"></a>
### layer.fills : [<code>Array&lt;Fill&gt;</code>](fill.md)
Fills applied to the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+borders"></a>
### layer.borders : [<code>Array&lt;Border&gt;</code>](border.md)
Borders of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+shadows"></a>
### layer.shadows : [<code>Array&lt;Shadow&gt;</code>](shadow.md)
Shadows applied to the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+blur"></a>
### layer.blur : [<code>Blur</code>](blur.md)
Blur applied to the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+opacity"></a>
### layer.opacity : <code>Number</code>
Opacity of the layer, [0, 1].

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+blendMode"></a>
### layer.blendMode : <code>Fill.BLEND_MODES</code>
Blend mode of the layer, defined in [Fill.BLEND_MODES](fill.md).

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+borderRadius"></a>
### layer.borderRadius : <code>Number</code>
Border radius of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+rotation"></a>
### layer.rotation : <code>Number</code>
Rotation of to the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+exportable"></a>
### layer.exportable : <code>Boolean</code>
Indicates whether the layer has assets or not.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+assets"></a>
### layer.assets : <code>Array&lt;Object&gt;</code>
Assets of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

**Properties**

| Name | Type |
| --- | --- |
| density | <code>string</code> |
| format | <code>string</code> |

<a name="Layer+parent"></a>
### layer.parent : [<code>Layer</code>](#Layer)
Parent layer of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+version"></a>
### layer.version : [<code>Version</code>](version.md)
Version of the screen or component containing the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+content"></a>
### layer.content : <code>String</code>
Text of the text layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+textStyles"></a>
### layer.textStyles : <code>Array&lt;Object&gt;</code>
Text styles of the text layer, with ranges.

**Kind**: instance property of [<code>Layer</code>](#Layer)

**Properties**

| Name | Type |
| --- | --- |
| range | <code>Object</code> |
| range.start | <code>Number</code> |
| range.end | <code>Number</code> |
| textStyle | [<code>TextStyle</code>](textStyle.md) |

<a name="Layer+layers"></a>
### layer.layers : [<code>Array&lt;Layer&gt;</code>](layer.md)
Child layers of the group layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+componentName"></a>
### layer.componentName : <code>String</code>
Name of the component the group layer is referencing.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+inspectable"></a>
### layer.inspectable : <code>Boolean</code>
Whether the layer is inspectable in Zeplin.

**Kind**: instance property of [<code>Layer</code>](#Layer)

<a name="Layer+cornerRadius"></a>
### layer.cornerRadius : [<code>CornerRadius</code>](cornerRadius.md)
Corner radius of the layer.

**Kind**: instance property of [<code>Layer</code>](#Layer)
