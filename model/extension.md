## Extension
**Kind**: global interface

<a name="Extension"></a>
* [Extension](#Extension)
    * [.styleguideColors(context, colors)](#Extension+styleguideColors) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.styleguideTextStyles(context, textStyles)](#Extension+styleguideTextStyles) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.layer(context, selectedLayer)](#Extension+layer) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.comment(context, selectedLayer)](#Extension+comment) ⇒ <code>String</code>
    * [.exportStyleguideColors(context, colors)](#Extension+exportStyleguideColors) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) \| [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
    * [.exportStyleguideTextStyles(context, textStyles)](#Extension+exportStyleguideTextStyles) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) \| [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)

<a name="Extension+styleguideColors"></a>

### extension.styleguideColors(context, colors) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from Styleguide colors.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| colors | [<code>Array.&lt;Color&gt;</code>](color.md) |

<a name="Extension+styleguideTextStyles"></a>

### extension.styleguideTextStyles(context, textStyles) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from Styleguide text styles.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| textStyles | [<code>Array.&lt;TextStyle&gt;</code>](textStyle.md) |

<a name="Extension+layer"></a>

### extension.layer(context, selectedLayer) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from selected layer.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| selectedLayer | <code>[Layer](layer.md)</code> |

<a name="Extension+comment"></a>

### extension.comment(context, text) ⇒ <code>String</code>
Generates comment from the text, in extension's target language.

**Kind**: instance method of [<code>Extension</code>](#Extension)

**Returns**: <code>String</code> - Generated comment from the text, in extension's target language.

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| text | <code>String</code> |

<a name="Extension+exportStyleguideColors"></a>

### extension.exportStyleguideColors(context, colors) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) |  [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
Generates code export objects from Styleguide colors.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| colors | [<code>Array.&lt;Color&gt;</code>](color.md) |

<a name="Extension+exportStyleguideTextStyles"></a>

### extension.exportStyleguideTextStyles(context, textStyles) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) |  [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
Generates code export objects from Styleguide text styles.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| textStyles | [<code>Array.&lt;TextStyle&gt;</code>](textStyle.md) |

<a name="CodeObject"></a>

## CodeObject : <code>Object</code>
**Kind**: global typedef

**Properties**

| Name | Type | Description |
| --- | --- | --- |
| code | <code>String</code> | Generated snippet. |
| mode | <code>String</code> | Language for the generated snippet, e.g. `javascript`, `swift`. |


<a name="CodeExportObject"></a>

## CodeExportObject : <code>Object</code>
**Kind**: global typedef

**Properties**

| Name | Type | Description |
| --- | --- | --- |
| code | <code>String</code> | Content of the file. |
| mode | <code>String</code> | Language for the generated snippet, e.g. `javascript`, `swift`. |
| filename | String | Name of the file. |
