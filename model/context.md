## Context
**Kind**: global interface

<a name="Context"></a>
* [Context](#Context)
    * [.project](#Context+project) : [<code>Project</code>](project.md)
    * [.styleguide](#Context+styleguide) : [<code>Styleguide</code>](styleguide.md)
    * [.getOption(name)](#Context+getOption) ⇒ <code>Number</code> \| <code>Boolean</code> \| <code>String</code>

<a name="Context+project"></a>

### context.project : [<code>Project?</code>](project.md)
Project that the extension is running in.

<a name="Context+styleguide"></a>

### context.styleguide : [<code>Styleguide?</code>](styleguide.md)
Styleguide that the extension is running in.

**Kind**: instance property of [<code>Context</code>](#Context)
<a name="Context+getOption"></a>

### context.getOption(id) ⇒ <code>Number</code> \| <code>Boolean</code> \| <code>String</code>
Value of the option with id.

**Kind**: instance method of [<code>Context</code>](#Context)
**Returns**: <code>Number</code> \| <code>Boolean</code> \| <code>String</code> - Value of the option.

| Param | Type | Description |
| --- | --- | --- |
| name | <code>String</code> | Name of the option to be queried. |
