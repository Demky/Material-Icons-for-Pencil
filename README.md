# Material Icons for Pencil

----

## ⚠️ No longer actively developed
Other commitments and the fact I no longer use Pencil mean this repo is no longer being actively worked on.
Pull-requests with new features/fixes are still welcome, as are new issues, but my responses might not be the speediest 🙂

----

All 1000+ icons from [Material Design Icons](https://materialdesignicons.com/) as a [Pencil](https://github.com/prikhi/pencil) stencil collection.

Based on the 24px version of the icons, however everything is in vector format, so can be scaled to any size.

*Check out my other stencil collections for Pencil at [nathanielw.github.io/pencil-stencils](http://nathanielw.github.io/pencil-stencils/)*

## Installation
- Download the [latest release](https://github.com/nathanielw/Material-Icons-for-Pencil/releases/latest) zip file.
- Install the collection in Pencil by going to *Tools > Install new collection* and selecting the zip.
- Enjoy!

### Updating
Right-click on the collection in Pencil's sidebar and choose _Uninstall this collection_ before repeating the installation steps.

## Generating the Collection
- Clone this repo with the `--recursive` flag to include submodules. (or just clone it normally then `git submodule init` and `git submodule update`)
- Run the `generate-xml.py` script (tested with Python 3.4).

This will generate the stencil definition XML and png thumbnails and place them in the `gen/` folder.

Everything **inside** the `gen/` folder can then be zip'd and installed in Pencil.

Windows users wanting to **generate** the collection: see [this comment](https://github.com/nathanielw/Material-Icons-for-Pencil/issues/2#issuecomment-108849198).

## License
From the [Material Design Icons README](https://github.com/Templarian/MaterialDesign):

>Community Icons - [SIL Open Font License 1.1](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web)
>
>Google Material Design Icons - [Attribution 4.0 International](https://github.com/google/material-design-icons/blob/master/LICENSE)

All source code/scripts used to generate the Pencil stencil are released under the [MIT License](http://opensource.org/licenses/mit-license.php).
