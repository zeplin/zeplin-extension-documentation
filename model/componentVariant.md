## ComponentVariant
**Kind**: global interface

<a name="ComponentVariant"></a>
* [ComponentVariant](#ComponentVariant)
    * [.name](#ComponentVariant+name) : <code>String</code>
    * [.propertyDescriptors](#ComponentVariant+propertyDescriptors) : [<code>Array&lt;ComponentPropertyDescriptor&gt;</code>](#ComponentPropertyDescriptor)
    * [.components](#ComponentVariant+components) : [<code>Array&lt;Component&gt;</code>](component.md)
    * [.findPropertyDescriptorById(propertyId)](#ComponentVariant+findPropertyDescriptorById) ⇒ [<code>ComponentPropertyDescriptor</code>](#ComponentPropertyDescriptor)
    * [.findPropertyDescriptorByName(name)](#ComponentVariant+findPropertyDescriptorByName) ⇒ [<code>ComponentPropertyDescriptor</code>](#ComponentPropertyDescriptor)

<a name="ComponentVariant+name"></a>
### componentVariant.name : <code>String</code>
Name of the component variants.

**Kind**: instance property of [<code>ComponentVariant</code>](#ComponentVariant)

<a name="ComponentVariant+propertyDescriptors"></a>
### componentVariant.propertyDescriptors : [<code>Array&lt;ComponentPropertyDescriptor&gt;</code>](#ComponentPropertyDescriptor)
Details of the properties that components in this variant can take.

**Kind**: instance property of [<code>ComponentVariant</code>](#ComponentVariant)

<a name="ComponentVariant+components"></a>
### componentVariant.components : [<code>Array&lt;Component&gt;</code>](component.md)
Components included in the variant.

**Kind**: instance property of [<code>ComponentVariant</code>](#ComponentVariant)


<a name="ComponentVariant+findPropertyDescriptorById"></a>
### compocomponentVariantnent.findPropertyDescriptorById(propertyId) ⇒ [<code>ComponentPropertyDescriptor?</code>](#ComponentPropertyDescriptor)
Finds property descriptor by unique identifier.

**Kind**: instance method of [<code>ComponentVariant</code>](#ComponentVariant)

| Param | Type |
| --- | --- |
| propertyId | <code>String</code> |


<a name="componentVariant+findPropertyDescriptorByName"></a>
### componentVariant.findPropertyDescriptorByName(name) ⇒ [<code>ComponentPropertyDescriptor?</code>](#ComponentPropertyDescriptor)
Finds property descriptor by name.

**Kind**: instance method of [<code>ComponentVariant</code>](#ComponentVariant)

| Param | Type |
| --- | --- |
| name | <code>String</code> |


<a name="ComponentPropertyDescriptor"></a>
## ComponentPropertyDescriptor : <code>Object</code>
**Kind**: global typedef

**Properties**

| Name | Type | Description |
| --- | --- | --- |
| id | <code>String</code> | Unique identifier of the variant property. |
| name | <code>String</code> | Name of the variant property. |
| values | <code>Array&lt;String&gt;</code> | Possible values for the variant property. |

### Related models

- [`Component`](component.md)
