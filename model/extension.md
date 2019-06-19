## Extension
**Kind**: global interface

<a name="Extension"></a>
* [Extension](#Extension)
    * [.layer(context, selectedLayer)](#Extension+layer) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.screen(context, selectedVersion, selectedScreen)](#Extension+screen) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.component(context, selectedVersion, selectedComponent)](#Extension+component) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.colors(context)](#Extension+colors) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.textStyles(context)](#Extension+textStyles) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.exportColors(context)](#Extension+exportColors) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) \| [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
    * [.exportTextStyles(context)](#Extension+exportTextStyles) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) \| [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
    * [.styleguideColors(context, colors)](#Extension+styleguideColors) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.styleguideTextStyles(context, textStyles)](#Extension+styleguideTextStyles) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
    * [.comment(context, text)](#Extension+comment) ⇒ <code>String</code>
    * [.exportStyleguideColors(context, colors)](#Extension+exportStyleguideColors) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) \| [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
    * [.exportStyleguideTextStyles(context, textStyles)](#Extension+exportStyleguideTextStyles) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) \| [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)

<a name="Extension+layer"></a>
### extension.layer(context, selectedLayer) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from the selected layer.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| selectedLayer | <code>[Layer](layer.md)</code> |

<a name="Extension+screen"></a>
### extension.screen(context, selectedVersion, selectedScreen) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from the selected version of a screen.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| selectedVersion | <code>[Version](version.md)</code> |
| selectedScreen | <code>[Screen](screen.md)</code> |

<a name="Extension+component"></a>
### extension.component(context, selectedVersion, selectedComponent) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from the selected version of a component, currently limited to the latest version.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| selectedVersion | <code>[Version](version.md)</code> |
| selectedComponent | <code>[Component](component.md)</code> |

<a name="Extension+colors"></a>
### extension.colors(context) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from colors in a project or styleguide.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |

<a name="Extension+textStyles"></a>
### extension.textStyles(context) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
Generates string or code object from text styles in a project or styleguide..

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |

<a name="Extension+exportColors"></a>
### extension.exportColors(context) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) |  [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
Generates code export objects from colors in a project or styleguide.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |

<a name="Extension+exportTextStyles"></a>
### extension.exportTextStyles(context) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) |  [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
Generates code export objects from text styles in a project or styleguide.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |

<a name="Extension+styleguideColors"></a>
### extension.styleguideColors(context, colors) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
*DEPRECATED* - See <code>[Extension.colors](#Extension+colors)</code>.<br>Generates string or code object from Styleguide colors.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| colors | [<code>Array.&lt;Color&gt;</code>](color.md) |

<a name="Extension+styleguideTextStyles"></a>
### extension.styleguideTextStyles(context, textStyles) ⇒ <code>String</code> \| [<code>CodeObject</code>](#CodeObject)
*DEPRECATED* - See <code>[Extension.textStyles](#Extension+textStyles)</code>.<br>Generates string or code object from Styleguide text styles.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| textStyles | [<code>Array.&lt;TextStyle&gt;</code>](textStyle.md) |

<a name="Extension+comment"></a>
### extension.comment(context, text) ⇒ <code>String</code>
*DEPRECATED* - Generates comment string from the text, in extension's target language, displayed alongside of Styleguide colors and text styles.

**Kind**: instance method of [<code>Extension</code>](#Extension)

**Returns**: <code>String</code> - Generated comment from the text, in extension's target language.

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| text | <code>String</code> |

<a name="Extension+exportStyleguideColors"></a>
### extension.exportStyleguideColors(context, colors) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) |  [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
*DEPRECATED* - See <code>[Extension.exportColors](#Extension+exportColors)</code>.<br>Generates code export objects from Styleguide colors.

**Kind**: instance method of [<code>Extension</code>](#Extension)

| Param | Type |
| --- | --- |
| context | <code>[Context](context.md)</code> |
| colors | [<code>Array.&lt;Color&gt;</code>](color.md) |

<a name="Extension+exportStyleguideTextStyles"></a>
### extension.exportStyleguideTextStyles(context, textStyles) ⇒ [<code>CodeExportObject</code>](#CodeExportObject) |  [<code>Array.&lt;CodeExportObject&gt;</code>](#CodeExportObject)
*DEPRECATED* - See <code>[Extension.exportTextStyles](#Extension+exportTextStyles)</code>.<br>Generates code export objects from Styleguide text styles.

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
| language | <code>String</code> | Language for the generated snippet, e.g. `javascript`, `swift`. |


<a name="CodeExportObject"></a>
## CodeExportObject : <code>Object</code>
**Kind**: global typedef

**Properties**

| Name | Type | Description |
| --- | --- | --- |
| code | <code>String</code> | Content of the file. |
| language | <code>String</code> | Language for the generated snippet, e.g. `javascript`, `swift`. |
| filename | String | Name of the file. |
