# Functions

## Argument Types

* float
* texture
* vec4

## Functions

### Color

#### posterize

#### Args
* bins :: float
* gamma :: float

#### shift

#### Args
* r :: float
* g :: float
* b :: float
* a :: float

#### invert

No Args

#### contrast

No Args

#### brightness

No Args

#### luma

#### Args
* threshold :: float
* tolerance :: float

#### thresh

#### Args
* threshold :: float
* tolerance :: float

#### color

#### Args
* r :: float
* g :: float
* b :: float
* a :: float

#### saturate

No Args

#### hue

No Args

#### colorama

No Args


### Combine

#### add

#### Args
* texture :: vec4
* amount :: float

#### layer

No Args

#### blend

#### Args
* texture :: vec4
* amount :: float

#### mult

#### Args
* texture :: vec4
* amount :: float

#### diff

No Args

#### mask

No Args


### CombineCoord

#### modulateRepeat

#### Args
* texture :: vec4
* repeatX :: float
* repeatY :: float
* offsetX :: float
* offsetY :: float

#### modulateRepeatX

#### Args
* texture :: vec4
* reps :: float
* offset :: float

#### modulateRepeatY

#### Args
* texture :: vec4
* reps :: float
* offset :: float

#### modulateKaleid

#### Args
* texture :: vec4
* nSides :: float

#### modulateScrollX

#### Args
* texture :: vec4
* scrollX :: float
* speed :: float

#### modulateScrollY

#### Args
* texture :: vec4
* scrollY :: float
* speed :: float

#### modulate

#### Args
* texture :: vec4
* amount :: float

#### modulateScale

#### Args
* texture :: vec4
* multiple :: float
* offset :: float

#### modulatePixelate

#### Args
* texture :: vec4
* multiple :: float
* offset :: float

#### modulateRotate

#### Args
* texture :: vec4
* multiple :: float
* offset :: float

#### modulateHue

#### Args
* texture :: vec4
* amount :: float


### Coord

#### rotate

#### Args
* angle :: float
* speed :: float

#### scale

#### Args
* amount :: float
* xMult :: float
* yMult :: float
* offsetX :: float
* offsetY :: float

#### pixelate

#### Args
* pixelX :: float
* pixelY :: float

#### repeat

#### Args
* repeatX :: float
* repeatY :: float
* offsetX :: float
* offsetY :: float

#### repeatX

#### Args
* reps :: float
* offset :: float

#### repeatY

#### Args
* reps :: float
* offset :: float

#### kaleid

No Args

#### scrollX

#### Args
* scrollX :: float
* speed :: float

#### scrollY

#### Args
* scrollY :: float
* speed :: float


### Src

#### noise

#### Args
* scale :: float
* offset :: float

#### voronoi

#### Args
* scale :: float
* speed :: float
* blending :: float

#### osc

#### Args
* frequency :: float
* sync :: float
* offset :: float

#### shape

#### Args
* sides :: float
* radius :: float
* smoothing :: float

#### gradient

No Args

#### src

No Args

#### solid

#### Args
* r :: float
* g :: float
* b :: float
* a :: float


### Util

#### _noise

No Args

#### luminance

No Args

#### _rgbToHsv

No Args

#### _hsvToRgb

No Args



