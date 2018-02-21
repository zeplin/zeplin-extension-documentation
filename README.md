# Zeplin Extension Documentation ⚗️📚

Zeplin extensions are JavaScript modules that generate code snippets from various design elements. All code snippets you interact with in Zeplin are generated using extensions and they're curated at [extensions.zeplin.io](https://extensions.zeplin.io).

If you're interested in developing your own Zeplin extension, this documentation covers the basics of building one along with a tutorial and discusses their capabilities.

Ping us at [extensions@zeplin.io](mailto:extensions@zeplin.io) if you'd like us to publish your extension at [extensions.zeplin.io](https://extensions.zeplin.io) or if you have any questions—we'd love to hear what you're building!

If you just want to try out extensions and ended up here by mistake, head to [extensions.zeplin.io](https://extensions.zeplin.io) to browse them.

☝️ _Friendly reminder: This documentation will likely change as we polish things during the beta._

## What is an extension?

![CSS extension](img/cssExtension.png)

Extensions are JavaScript modules that implement various functions to generate code snippets from models.

In the example above, Zeplin invokes the `layer` function of the extension, passing the selected layer object as a parameter. Returned value is then displayed. Code highlighting is performed by Zeplin, extensions only communicate the preferred language.

Extensions contain at least two files:

#### Manifest

JSON document that defines everything you need to know about an extension.

- Defines basic information like the name, description and author.
- Defines the location of the module file.
- Defines options.

[See manifest documentation](manifest.md) for details.

#### Module

JavaScript document that implements functions that correspond to different actions, to name a few:

- `styleguideColors`: Generates snippets from Styleguide colors.
- `layer`: Generates snippets from layers.

[See `Extension` documentation](model/extension.md) for all the functions and their details.

## Your first extension

We've prepared a [tutorial](tutorial.md) to guide you through your first Zeplin extension, dive in!

## Model documentation

Quickly jump to a particular model to learn more about it.

- [`Extension`](model/extension.md)
- [`Context`](model/context.md)
- [`Project`](model/project.md)
- [`Color`](model/color.md)
- [`Gradient`](model/gradient.md)
- [`ColorStop`](model/colorStop.md)
- [`TextStyle`](model/textStyle.md)
- [`Layer`](model/layer.md)
- [`Fill`](model/fill.md)
- [`Border`](model/border.md)
- [`Shadow`](model/shadow.md)
- [`Blur`](model/blur.md)

## Example extensions

_Check back in a few days for example extensions. The plan is to open source our existing extensions, like React Native and Attributed Strings, to provide full-fledged examples used by thousands of developers everyday._
