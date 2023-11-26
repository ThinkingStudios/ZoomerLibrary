# ZoomerLibrary

LibZoomer unofficial forge port.

A library that allows other mods to create zooms and custom spyglasses easily.

## Usage

**WARNING:** This API is still not finished and breaking changes may happen until a 1.0.0 release happens!

This library is available through Jitpack. If none of these options work, consider using local Maven on the source code of a released version.

ZoomerLibrary provides zooming through zoom instances, which contains three sub-instances: transition modes, mouse modifiers and zoom overlays. A zoom instance can be created with different subinstances, which can be either provided by the library or implemented by the mod itself. In order to a zoom instance to be functional, it must be registered by the ZoomRegistry. In order to make the instance zoom in, the instance's zoom state must be set to true, which can be done using the `setZoom` method, the vice-versa can be done by setting it to false.

A better guide will be written later, feel free to take a look on this mod's testmod if you want an example!

## Download

This mod is meant to be JiJ'd by mods, so you wouldn't need to download it at all in most cases. If you really need to download it, it's available in the following services:

- [GitHub Releases (alternative)](https://github.com/ThinkingStudios/ZoomerLibrary/releases)

## License

This mod is licensed under the MIT license. You can freely Jar-in-Jar this mod on any mod with no permission. Usage of this mod's code on other projects or derivatives of this mod is allowed as long as attribution is given.
