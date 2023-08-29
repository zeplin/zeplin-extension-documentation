## LayerConstraint
**Kind**: global interface

<a name="LayerConstraint"></a>
* [LayerConstraint](#LayerConstraint)
    * _instance_
        * [.min](#LayerConstraint+min) : <code>Boolean</code>
        * [.max](#LayerConstraint+max) : <code>Boolean</code>        
        * [.sizingMode](#LayerConstraint+sizingMode) : [<code>SIZING_MODE</code>](#LayerConstraint.SIZING_MODE)        
    * _static_
        * [.SIZING_MODE](#LayerConstraint.SIZING_MODE) : <code>enum</code>

<a name="LayerConstraint+min"></a>
### layerConstraint.min : <code>Boolean</code>
Determines if there is a fixed distance to starting edge (top for vertical, left for horizontal).

**Kind**: instance property of [<code>LayerConstraint</code>](#LayerConstraint)

<a name="LayerConstraint+max"></a>
### layerConstraint.max : <code>Boolean</code>
Determines if there is a fixed distance to ending edge (bottom for vertical, right for horizontal).

**Kind**: instance property of [<code>LayerConstraint</code>](#LayerConstraint)

<a name="LayerConstraint+sizingMode"></a>
### layerConstraint.sizingMode : <code>String</code>
Sizing mode of the layer.

**Kind**: instance property of [<code>LayerConstraint</code>](#LayerConstraint)

<a name="LayerConstraint.SIZING_MODE"></a>
### LayerConstraint.SIZING_MODE : <code>enum</code>
Sizing mode for a layer constraint.

**Kind**: static enum of [<code>LayerConstraint</code>](#LayerConstraint)
**Properties**

| Name | Type | Default |
| --- | --- | --- |
| FIXED | <code>String</code> | <code>fixed</code> |
| STRETCH | <code>String</code> | <code>stretch</code> |
| HUG_CONTENTS | <code>String</code> | <code>hug-contents</code> |
