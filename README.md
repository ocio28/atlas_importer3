# Atlas Import
Este es un fork del plugin de https://github.com/vichui/atlas_importer3 que intenta corregir
un bug en el tamaño de los atlas al realizar el import

Este plugin es para  https://godotengine.org y te ayuda a importar distintos
atlas de texturas creados con otras herramientas.

#### Formatos de atlas soportado
- TexturePacker : Generic XML
- TexturePacker : JSON hash
- [Attila](https://github.com/r-lyeh/attila) : JSON
- Kenney Spritesheet : Atlas from [Kenney assets](http://kenney.nl/assets)
- LibGDX: (Atlas from LibGDX Framework, which has a nice GUI tools - GDX Texture Packer (https://github.com/crashinvaders/gdx-texture-packer-gui))

Como godot no soporta atlas rotados, no rotes tus sprites cuando generes los atlas o tendras que rotarlos devuelta.

## Bugs
Debido a un bug usando AtlasTexure en el editor, este plugin solo funciona desde la version 3.0.3-rc1