![](addons/inspector-gadget/icon.png)

# Inspector Gadget

A general-purpose GDScript UI for building editor functionality inside Godot.

## Overview

Inspector gadget is a set of GDScript UI controls designed to read and write object properties at runtime. It extends the standard `get_indexed()` function from the `Node` class with support for arrays and dictionaries, allowing for fully-recursive property visualization and editing using `NodePath` subnames.

## Features

- Inspect and edit the properties of any object from inside your Godot game
- Address any property with string-based subnames
  - Example: `SomeNode:resource_property:dictionary_property:[values]:3`
- Selectively hide properties via blacklist
- Visualize custom `Resource` subclasses with your own controls
- Type-hint typeless structures like `Array` and `Dictionary` for full control over UI
- Easily filter built-in properties, leaving only custom script data

## Example Content

`example.tscn` in the `scenes` folder contains a visual example of the Inspector Gadget UI, and includes visualization and editing for each of Godot's built-in basic types.

## Inspector Gadget Elsewhere

[Discord](https://discord.gg/c72WBuG)

[Shifty's Twitter](https://twitter.com/ShiftyAxel)

## Support

If you'd like to support the ongoing development of Inspector Gadget, a Patreon page is available here:

[Shifty Studio - Patreon](https://www.patreon.com/shifty_studio)

Donations via PayPal are also accepted:

[![Donate with PayPal button](https://www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=D8FJ3RX3WSQJS&source=url)
