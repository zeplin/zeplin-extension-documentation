## Project
**Kind**: global interface

<a name="Project"></a>
* [Project](#Project)
    * [.type](#Project+type) : <code>String</code>
    * [.name](#Project+name) : <code>String</code>
    * [.textStyles](#Project+textStyles) : [<code>Array&lt;TextStyle&gt;</code>](textStyle.md)
    * [.colors](#Project+colors) : [<code>Array&lt;Color&gt;</code>](color.md)
    * [.spacingSections](#Project+spacingSections) : [<code>Array&lt;SpacingSection&gt;</code>](spacingSection.md)
    * [.density](#Project+density) : <code>String</code>
    * [.densityDivisor](#Project+densityDivisor) : <code>Number</code>
    * [.lengthUnit](#Project+lengthUnit) : <code>String</code>
    * [.textLengthUnit](#Project+textLengthUnit) : <code>String</code>
    * [.linkedStyleguide](#Project+linkedStyleguide) : <code>Styleguide?</code>
    * [.remPreferences](#Project+remPreferences) : [<code>RemPreferences?</code>](remPreferences.md)
    * [.findTextStyleByName(name, useLinkedStyleguides = true)](#Project+findTextStyleByName) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findTextStyleEqual(textStyle, useLinkedStyleguides = true)](#Project+findTextStyleEqual) ⇒ [<code>TextStyle</code>](textStyle.md)
    * [.findColorByName(name, useLinkedStyleguides = true)](#Project+findColorByName) ⇒ [<code>Color</code>](color.md)
    * [.findColorEqual(color, useLinkedStyleguides = true)](#Project+findColorEqual) ⇒ [<code>Color</code>](color.md)
    * [.findColorByHexAndAlpha(values, useLinkedStyleguides = true)](#Project+findColorByHexAndAlpha) ⇒ [<code>Color</code>](color.md)
    * [.findSpacingTokenByValue(value, useLinkedStyleguides = true)](#Project+findSpacingTokenByValue) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
    * [.findSpacingTokenByName(name, useLinkedStyleguides = true)](#Project+findSpacingTokenByName) ⇒ [<code>SpacingToken?</code>](spacingToken.md)


<a name="Project+type"></a>
### project.type : <code>String</code>
Type of the project, `web`, `android`, `ios` or `osx`.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+name"></a>
### project.name : <code>String</code>
Name of the project.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+textStyles"></a>
### project.textStyles : [<code>Array&lt;TextStyle&gt;</code>](textStyle.md)
Text styles in the project.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+colors"></a>
### project.colors : [<code>Array&lt;Color&gt;</code>](color.md)
Colors in the project.

**Kind**: instance property of [<code>Project</code>](#Project)



<a name="Project+spacingSections"></a>
### project.spacingSections : [<code>Array&lt;SpacingSection&gt;</code>](spacingSection.md)
Spacing sections in the project.

**Kind**: instance property of [<code>Project</code>](#Project)

<a name="Project+density"></a>
### project.density : <code>String</code>
Pixel density of the project.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+densityDivisor"></a>
### project.densityDivisor : <code>Number</code>
Divisor corresponding to the density, used to obtain actual values from unit values.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+lengthUnit"></a>
### project.lengthUnit : <code>String</code>
Length unit of the project, based on the type, e.g. `px` for Web, `pt` for iOS.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+textLengthUnit"></a>
### project.textLengthUnit : <code>String</code>
Text length unit of the project, based on the type, e.g. `dp` for Android.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+linkedStyleguide"></a>
### project.linkedStyleguide : [<code>Styleguide?</code>](styleguide.md)
Styleguide linked to the project.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+remPreferences"></a>
### project.remPreferences : [<code>RemPreferences?</code>](remPreferences.md)
Rem preferences of the project. If the rem is disabled the value is `undefined`.

**Kind**: instance property of [<code>Project</code>](#Project)


<a name="Project+findTextStyleByName"></a>
### project.findTextStyleByName(name, useLinkedStyleguides = true) ⇒ [<code>TextStyle?</code>](textStyle.md)
Finds text style in the project or in the linked styleguides (if useLinkedStyleguides is true) by name.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Project+findTextStyleEqual"></a>
### project.findTextStyleEqual(textStyle, useLinkedStyleguides = true) ⇒ [<code>TextStyle?</code>](textStyle.md)
Finds text style in the project or in the linked styleguides (if useLinkedStyleguides is true) equal to another text style.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| textStyle | <code>TextStyle</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Project+findColorByName"></a>
### project.findColorByName(name, useLinkedStyleguides = true) ⇒ [<code>Color?</code>](color.md)
Finds color in the project or in the linked styleguides (if useLinkedStyleguides is true) by name.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Project+findColorEqual"></a>
### project.findColorEqual(color, useLinkedStyleguides = true) ⇒ [<code>Color?</code>](color.md)
Finds color in the project or in the linked styleguides (if useLinkedStyleguides is true) equal to another color.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| color | <code>Color</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Project+findColorByHexAndAlpha"></a>
### project.findColorByHexAndAlpha(values, useLinkedStyleguides = true) ⇒ [<code>Color?</code>](color.md)
Finds color in the project or in the linked styleguides (if useLinkedStyleguides is true) by hex and alpha values.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| values | <code>Object</code> |  |
| values.hex | <code>String</code> | Hex string for RGB components of the color, e.g. `rrggbb`. |
| values.alpha | <code>String</code> | Alpha value of the color. |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Project+findSpacingTokenByValue"></a>
### project.findSpacingTokenByValue(value, useLinkedStyleguides = true) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
Finds spacing token in the project or in the linked styleguides (if useLinkedStyleguides is true) by value.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| value | <code>Number</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |


<a name="Project+findSpacingTokenByName"></a>
### project.findSpacingTokenByName(name, useLinkedStyleguides = true) ⇒ [<code>SpacingToken?</code>](spacingToken.md)
Finds spacing token in the project or in the linked styleguides (if useLinkedStyleguides is true) by name.

**Kind**: instance method of [<code>Project</code>](#Project)

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> |  |
| useLinkedStyleguides | <code>Boolean</code> | Whether linked styleguides should be included in the search. Defaults to `true`. |
