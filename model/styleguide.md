## Styleguide
**Kind**: global interface

<a name="Styleguide"></a>
* [Styleguide](#Styleguide)
    * [.type](#Styleguide+type) : <code>String</code>
    * [.name](#Styleguide+name) : <code>String</code>
    * [.parent](#Styleguide+parent) : <code>Styleguide</code>
    * [.textStyles](#Styleguide+textStyles) : [<code>Array&lt;TextStyle&gt;</code>](textStyle.md)
    * [.colors](#Styleguide+colors) : [<code>Array&lt;Color&gt;</code>](color.md)
    * [.spacingSections](#Styleguide+spacingSections) : [<code>Array&lt;SpacingSection&gt;</code>](spacingSection.md)
    * [.components](#Project+components) : [<code>Array&lt;Component&gt;</code>](component.md)
    * [.density](#Styleguide+density) : <code>String</code>
    * [.densityDivisor](#Styleguide+densityDivisor) : <code>Number</code>
    * [.lengthUnit](#Styleguide+lengthUnit) : <code>String</code>
    * [.textLengthUnit](#Styleguide+textLengthUnit) : <code>String</code>
    * [.remPreferences](#Project+remPreferences) : [<code>RemPreferences?</code>](remPreferences.md)
    * [.findTextStyleByName(name, useParentStyleguides = true)](#Styleguide+findTextStyleByName) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findTextStyleEqual(textStyle, useParentStyleguides = true)](#Styleguide+findTextStyleEqual) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findBestConformingTextStyle(textStyle, useParentStyleguides = true)](#Styleguide+findBestConformingTextStyle) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findColorByName(name, useParentStyleguides = true)](#Styleguide+findColorByName) ⇒ [<code>Color</code>](color.md)
    * [.findColorEqual(color, useParentStyleguides = true)](#Styleguide+findColorEqual) ⇒ [<code>Color</code>](color.md)
    * [.findColorByHexAndAlpha(values, useParentStyleguides = true)](#Styleguide+findColorByHexAndAlpha) ⇒ [<code>Color</code>](color.md)
    * [.findSpacingTokenByValue(value, useParentStyleguides = true)](#Styleguide+findSpacingTokenByValue) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
    * [.findSpacingTokenByName(name, useParentStyleguides = true)](#Styleguide+findSpacingTokenByName) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
    * [.findComponentByName(name, useLinkedStyleguides = true)](#Project+findComponentByName) ⇒ [<code>Component?</code>](component.md)
    * [.findComponentBySourceId(sourceId, useLinkedStyleguides = true)](#Project+findComponentBySourceId) ⇒ [<code>Component?</code>](component.md)


<a name="Styleguide+type"></a>
### styleguide.type : <code>String</code>
Type of the styleguide, `base`, `web`, `android`, `ios` or `osx`.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+name"></a>
### styleguide.name : <code>String</code>
Name of the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+parent"></a>
### styleguide.parent : [<code>Styleguide?</code>](styleguide.md)
Parent styleguide of the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+textStyles"></a>
### styleguide.textStyles : [<code>Array&lt;TextStyle&gt;</code>](textStyle.md)
Text styles in the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+colors"></a>
### styleguide.colors : [<code>Array&lt;Color&gt;</code>](color.md)
Colors in the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+spacingSections"></a>
### styleguide.spacingSections : [<code>Array&lt;SpacingSection&gt;</code>](spacingSection.md)
Spacing sections in the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Project+components"></a>
### project.components : [<code>Array&lt;Component&gt;</code>](component.md)
components in the project.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Styleguide+density"></a>
### styleguide.density : <code>String</code>
Pixel density of the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+densityDivisor"></a>
### styleguide.densityDivisor : <code>Number</code>
Divisor corresponding to the density, used to obtain actual values from unit values.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+lengthUnit"></a>
### styleguide.lengthUnit : <code>String</code>
Length unit of the styleguide, based on the type, e.g. `px` for Web, `pt` for iOS.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+textLengthUnit"></a>
### styleguide.textLengthUnit : <code>String</code>
Text length unit of the styleguide, based on the type, e.g. `dp` for Android.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+remPreferences"></a>
### Styleguide.remPreferences : [<code>RemPreferences?</code>](remPreferences.md)
rem preferences of the styleguide (web styleguides only). This property exists only if rem is enabled for the styleguide.

**Kind**: instance property of [<code>Styleguide</code>](#Styleguide)


<a name="Styleguide+findTextStyleByName"></a>
### styleguide.findTextStyleByName(name, useParentStyleguides = true) ⇒ [<code>TextStyle?</code>](textStyle.md)
Finds text style in the styleguide or in the parent styleguides (if useParentStyleguides is true) by name.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findTextStyleEqual"></a>
### styleguide.findTextStyleEqual(textStyle, useParentStyleguides = true) ⇒ [<code>TextStyle?</code>](textStyle.md)
Finds text style in the styleguide or in the parent styleguides (if useParentStyleguides is true) equal to another text style.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| textStyle | <code>TextStyle</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findBestConformingTextStyle"></a>
### styleguide.findBestConformingTextStyle(textStyle, useParentStyleguides = true) ⇒ [<code>TextStyle?</code>](textStyle.md)
Finds best conforming text style in the styleguide or in the parent styleguides (if useParentStyleguides is true).

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| textStyle | <code>TextStyle</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findColorByName"></a>
### styleguide.findColorByName(name, useParentStyleguides = true) ⇒ [<code>Color?</code>](color.md)
Finds color in the styleguide or in the parent styleguides (if useParentStyleguides is true) by name.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findColorEqual"></a>
### styleguide.findColorEqual(color, useParentStyleguides = true) ⇒ [<code>Color?</code>](color.md)
Finds color in the styleguide or in the parent styleguides (if useParentStyleguides is true) equal to another color.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| color | <code>Color</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findColorByHexAndAlpha"></a>
### styleguide.findColorByHexAndAlpha(values, useParentStyleguides = true) ⇒ [<code>Color?</code>](color.md)
Finds color in the styleguide or in the parent styleguides (if useParentStyleguides is true) by hex and alpha values.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| values | <code>Object</code> |  |
| values.hex | <code>String</code> | Hex string for RGB components of the color, e.g. `rrggbb`. |
| values.alpha | <code>String</code> | Alpha value of the color. |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findSpacingTokenByValue"></a>
### styleguide.findSpacingTokenByValue(value, useParentStyleguides = true) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
Finds spacing token in the styleguide or in the parent styleguides (if useParentStyleguides is true) by value.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| value | <code>Number</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findSpacingTokenByName"></a>
### styleguide.findSpacingTokenByName(name, useParentStyleguides = true) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
Finds spacing token in the styleguide or in the parent styleguides (if useParentStyleguides is true) by name.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useParentStyleguides | <code>Boolean</code> | Whether parent styleguides should be included in the search. Defaults to `true`. |

<a name="Styleguide+findComponentByName"></a>
### styleguide.findComponentByName(name, useLinkedStyleguides = true) ⇒ [<code>Component?</code>](component.md)
Finds a component in the styleguide or in the linked styleguides (if useLinkedStyleguides is true) by name.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Styleguide+findComponentBySourceId"></a>
### styleguide.findComponentBySourceId(name, useLinkedStyleguides = true) ⇒ [<code>Component?</code>](component.md)
Finds a component in the styleguide or in the linked styleguides (if useLinkedStyleguides is true) by id in the source design document.

**Kind**: instance method of [<code>Styleguide</code>](#Styleguide)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |
