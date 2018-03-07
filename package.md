# `package.json`

npm's `package.json` defines everything you, and Zeplin, need to know about an extension, along with its dependencies.

## Zeplin-specific properties

Zeplin-specific properties are stored under `package.json`'s `zeplin` property.

```json
{
    "name": "my-extension",
    "description": …,
    "version": …,
    "zeplin": {
        "displayName": "My Extension",
        "options": …
    },
    …
}
```

### displayName : `String`

Display name is optional but encouraged, as this is how the extension will be listed in the apps.

ProTip: Try to avoid the word "zeplin" in the display name, as it's assumed.

### options : `Array.<Option>`

Extensions can define options that are stored locally in Zeplin, per client.

Currently, three types of options are supported:

- **Switch:** On and off checkbox, `Boolean` value type.
- **Picker:** Drop-down list of options, `String` value type.
- **Text:** Text field, `String` value type.

#### Option : <code>Object</code>

##### Properties

| Name | Type | Description |
| --- | --- | --- |
| name | `String` | Display name of the option. |
| type | `String` | `switch`, `picker` or `text` |
| id | `String` | Identifier that Zeplin stores the preference with. |
| default | `Boolean` or `String` | Default value of the option, based on the type. |
| options | `Array.<PickerOption>` | Options, only for the picker type option. |

#### PickerOption : <code>Object</code>

##### Properties

| Name | Type | Description |
| --- | --- | --- |
| name | <code>String</code> | Display name of the picker option. |
| value | <code>String</code> | Value of the picker option. |

Here's a sample options property:

```json
[{
    "name": "Prefix",
    "type": "text",
    "id": "prefix",
    "default": ""
}, {
    "name": "Swift version",
    "type": "picker",
    "id": "swiftVersion",
    "options": [{
        "name": "3.0",
        "value": "3"
    }, {
        "name": "4.0",
        "value": "4"
    }],
    "default": "4"
}, {
    "name": "Default attributes",
    "type": "switch",
    "id": "defaultAttributes",
    "default": true
}]
```

## Key properties

Zeplin makes use of some key `package.json` properties.

### name : `String`

Uniquely defines the package for `npm`. Zeplin prefers  `displayName` Zeplin-specific property as the name listed in the apps.

### description : `String`

A short sentence describing what the extension does, e.g. “Generates CSS snippets from colors, text styles and layers.”

Description field is required, as it helps users quickly find the extension they're looking for.

### version : `String`

Version of the extension.

Changes to your module should come along with changes to the version as well.

### moduleURL : `String`

Relative or absolute path to the JavaScript document of the extension.

### author : `Author`

Author is an optional field, representing the person or the team working on the extension.

#### Author : <code>Object</code>

##### Properties

| Name | Type | Description |
| --- | --- | --- |
| name | `String` | Name of the author. |
| email | `String` | Email of the author, optional. |
| url | `String` | URL of the author, optional. |

### repository : `String`

If your extension is open source, repository URL is an optional URL field pointing to where your extension code lives. This is helpful for people who want to contribute.
