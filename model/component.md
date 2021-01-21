## Component
**Kind**: global interface

<a name="Component"></a>
* [Component](#Component)
    * [.name](#Component+name) : <code>String</code>
    * [.description](#Component+description) : <code>String</code>
    * [.latestVersion](#Component+latestVersion) : [<code>Version</code>](version.md)
    * [.properties](#Component+properties) : [<code>Array&lt;ComponentProperty&gt;</code>](#ComponentProperty)
    * [.variant](#Component+variant) : [<code>ComponentVariant</code>](componentVariant.md)
    * [.findPropertyById(propertyId)](#Component+findPropertyById) ⇒ [<code>ComponentProperty</code>](#ComponentProperty)
    * [.findPropertyByName(name)](#Component+findPropertyByName) ⇒ [<code>ComponentProperty</code>](#ComponentProperty)

See [`Version`](version.md) for properties of a component that change over time, like `layers`, `image` and so on.

<a name="Component+name"></a>
### component.name : <code>String</code>
Name of the component.

**Kind**: instance property of [<code>Component</code>](#Component)

<a name="Component+description"></a>
### component.description : <code>String</code>
Description of the component.

**Kind**: instance property of [<code>Component</code>](#Component)

<a name="Component+latestVersion"></a>
### component.latestVersion : [<code>Version</code>](version.md)
Latest version of the component.

**Kind**: instance property of [<code>Component</code>](#Component)

<a name="Component+properties"></a>
### component.properties : [<code>Array&lt;ComponentProperty&gt;</code>](#ComponentProperty)
Variant properties of the component.

**Kind**: instance property of [<code>Component</code>](#Component)

<a name="Component+variant"></a>
### component.variant : [<code>ComponentVariant</code>](componentVariant.md)
Variant that the component is part of.

**Kind**: instance property of [<code>Component</code>](#Component)


<a name="Component+findPropertyById"></a>
### component.findPropertyById(propertyId) ⇒ [<code>ComponentProperty?</code>](#ComponentProperty)
Finds property by unique identifier.

**Kind**: instance method of [<code>Component</code>](#Component)

| Param | Type |
| --- | --- |
| propertyId | <code>String</code> |


<a name="Component+findPropertyByName"></a>
### component.findPropertyByName(name) ⇒ [<code>ComponentProperty?</code>](#ComponentProperty)
Finds property by name.

**Kind**: instance method of [<code>Component</code>](#Component)

| Param | Type |
| --- | --- |
| name | <code>String</code> |


<a name="ComponentProperty"></a>
## ComponentProperty : <code>Object</code>
**Kind**: global typedef

**Properties**

| Name | Type | Description |
| --- | --- | --- |
| id | <code>String</code> | Unique identifier of the variant property. |
| name | <code>String</code> | Name of the variant property. |
| value | <code>String</code> | Value for the variant property. |

### Related models

- [`Version`](version.md)
- [`ComponentVariant`](componentVariant.md)
