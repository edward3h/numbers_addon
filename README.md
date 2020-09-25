# Number Blocks Addon for Minecraft Bedrock

Adds number blocks and 100 charts to Minecraft to help kids practice counting. Supports Minecraft Bedrock Edition (AKA MCBE, MCPE) 1.16.0 and up.

![Screenshot Vertical Grid](doc/verticalFar.png | width=300)
![Screenshot Horizontal Grid](doc/horizontalBuried.png | width=300)

# How to Use

Download the `mcpack` files from the [latest release](releases/latest) page. There are two files, for behavior and resource packs.

On most systems Minecraft can now install the packs as soon as you download them or open them. If that doesn't work, check installation instructions at MCPEDL: [Android](https://mcpedl.com/how-to-install-minecraft-pe-mods-for-android/) | [iOs](https://mcpedl.com/how-to-install-minecraft-pe-mods-for-ios/) | [Windows 10](https://mcpedl.com/how-to-install-addons-for-windows-10/).

Create a world in Minecraft and make sure you add both the Numbers behavior pack and the Numbers resource pack.

## In Game

Currently you can only obtain the number blocks by using commands. (This is related to [Minecraft bug MCPE-63121](https://bugs.mojang.com/browse/MCPE-63121) )

Example:

```
/give @s numbers:number25 10
```

will give yourself 10 of the "25" block.

### Functions

You can also use the included functions to draw a 1-100 counting grid.

```
/function grid100
```

will draw a horizontal grid starting at your location.

```
/function grid100vertical
```

will draw a vertical grid.

# Acknowledgements

The font used is the beautiful [JetBrains Mono](https://www.jetbrains.com/lp/mono/). It is freely available.

# Contributing

See the [Contributing](CONTRIBUTING.md) page.

# License

This project is licensed under the [GNU GPL](LICENSE).

# Changelog

* 1.0.0
  * Initial release.
  * Number blocks 1 - 100
  * Functions grid100, grid100vertical

