> **Note**: this runtime is a work in progress. Please follow this issue to get alerted once the runtime is deemed complete. https://github.com/EsotericSoftware/spine-runtimes/issues/2249

# spine-haxe

The spine-haxe runtime provides functionality to load, manipulate and render [Spine](http://esotericsoftware.com) skeletal animation data using [Haxe](https://haxe.org/) in combination with [OpenFL](https://www.openfl.org/) and [Lime](https://lime.openfl.org/).

## Licensing

You are welcome to evaluate the Spine Runtimes and the examples we provide in this repository free of charge.

You can integrate the Spine Runtimes into your software free of charge, but users of your software must have their own [Spine license](https://esotericsoftware.com/spine-purchase). Please make your users aware of this requirement! This option is often chosen by those making development tools, such as an SDK, game toolkit, or software library.

In order to distribute your software containing the Spine Runtimes to others that don't have a Spine license, you need a [Spine license](https://esotericsoftware.com/spine-purchase) at the time of integration. Then you can distribute your software containing the Spine Runtimes however you like, provided others don't modify it or use it to create new software. If others want to do that, they'll need their own Spine license.

For the official legal terms governing the Spine Runtimes, please read the [Spine Runtimes License Agreement](http://esotericsoftware.com/spine-runtimes-license) and Section 2 of the [Spine Editor License Agreement](http://esotericsoftware.com/spine-editor-license#s2).

## Spine version

spine-haxe works with data exported from Spine 4.2.xx.

spine-haxe supports all Spine features except premultiplied alpha atlases and two color tinting.

## Setup

TBD

## Example

TBD

## Development

To setup the development environment install the following:

1. [Haxe](https://haxe.org/download/), ensure it's available on the command line through your `PATH` if you use the binaries instead of the installer.
2. On the command line, run:
   ```
   haxelib setup
   haxelib install openfl
   haxelib run openfl setup
   haxelib install starling
   ```
3. Clone the `spine-runtimes` repository, and use `haxelib` to setup a dev library:
   ```
   git clone https://github.com/esotericsoftware/spine-runtimes
   cd spine-runtimes
   haxelib dev spine-haxe .
   ```

As an IDE, we recommend [Visual Studio Code](https://code.visualstudio.com/) with the following extension:

1. [Haxe extension](https://marketplace.visualstudio.com/items?itemName=nadako.vshaxe)
2. [HXCPP debugger extension](https://marketplace.visualstudio.com/items?itemName=vshaxe.hxcpp-debugger)
3. [Lime extension](https://marketplace.visualstudio.com/items?itemName=openfl.lime-vscode-extension)

The extensions provide IDE features like auto-completion, debugging, and build support.

To debug a build, set the corresponding Lime target in the status bar at the bottom of VS Code to e.g. `HTML5 / Debug`. Run the `lime` run configuration by pressing `F5`.
