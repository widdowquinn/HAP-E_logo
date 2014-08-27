# README.md - HAP-E_logo

## Overview

The [James Hutton Institute](http://www.hutton.ac.uk) hosts the Centre for Human and Animal Pathogens in the Environment, a consortium of scientists with interests in that area ([website](http://www.hutton.ac.uk/research/themes/controlling-weeds-pests-and-diseases/hape)).

The aim here is to illustrate modification of the agreed HAP-E logo, so that we have a colour version, and a comparable black-and white version.

## Original versions

The original, version 3, looks good but the horizontal colour bands are difficult to distinguish in greyscale:

![Agreed colour logo](jpeg/HAP-E_logo_v3_colour_change.jpg?raw=True =250x)
![Default greyscale filter](jpeg/HAP-E_logo_v3_greyscale.jpg?raw=True =250x)

## Modifications

The difficulty in distinguishing greyscale values derives from the broadly equivalent luminance/brightness of the colour spots in the logo. That uniform luminance makes the logo easy on the eye, and is not a bad thing in graphic design (though it can be problematic in data visualisation, e.g. [Points of view: Color coding](http://www.nature.com/nmeth/journal/v7/n8/full/nmeth0810-573.html)). It does however make greyscale representations difficult to distinguish.

Two approaches to greyscale manipulation are possible:

1. Modify the graphic specifically for greyscale
2. Modify the colour graphic to also be distinguishable in greyscale

I did this by individual modifications to the blue, green and brown hue/saturation and brightness/contrast values in Photoshop. Other methods are possible.

### 1. Specific greyscale modification

This approach retains the original colour graphic, but proposes a new greyscale rendering to accompany it, that is not just a default greyscale conversion of the original colour graphic. I did this by modifying the blue, green and brown colour brightnesses so that they had values of 33, 139 and 99, respectively on a 256-point greyscale.

![Greyscale modification](jpeg/HAP-E_logo_vBW.jpg?raw=True =250x)

This renders three distinguishable bands, though the corresponding colour graphic is not attractive. Other combinations of brightness for each colour are possible.

### 2. Colour graphic modification

An alternative approach is to modify the colour graphic so that it remains presentable, but has distinguishable spots when converted to default greyscale. This is more challenging, as the original colour graphic (with uniform luminance/brightness) looks good as it is, and deviations from those colours are  unlikely to be as impressive.

The approach taken here involves modification of the hue/saturation and luminance/brightness of the three colours so that overall luminance/brightness is separated well enough that the greyscale shows three distinguishable shades of grey. Two attempts are shown below.

Although these variants produce greyscale renderings with distinguishable spot bands, the colour logos also separate out bands by brightness, which I find unattractive, compared to the original logo.

#### Version 5:

![v5 colour logo](jpeg/HAP-E_logo_v5.jpg?raw=True =250x)
![v5 greyscale logo](jpeg/HAP-E_logo_v5_bw.jpg?raw=True =250x)

#### Version 6:

![v6 colour logo](jpeg/HAP-E_logo_v6.jpg?raw=True =250x)
![v6 greyscale logo](jpeg/HAP-E_logo_v6_bw.jpg?raw=True =250x)

## Conclusion

The original logo (HAP-E_logo_v3_colour_change) looks good, to me. Having colours of equal luminance/brightness is a good thing in colour logos, as it doesn't lead the eye in any particular way, and gives the whole design a cohesion that is lacking in the later alternatives whose colours are of differing brightness.

My suggestion is that we retain the original colour logo, and adopt one of the alternative greyscale logos for specific circumstances where the document will be known to be produced in monchrome.

# Files

* `jpeg`: directory containing `.jpg` renderings of logos
* `psd`: directory containing Photoshop `.psd` files for each logo rendering

```
$ tree .
.
├── README.md
├── jpeg
│   ├── HAP-E_logo_v3_colour_change.jpg
│   ├── HAP-E_logo_v3_greyscale.jpg
│   ├── HAP-E_logo_v4.jpg
│   ├── HAP-E_logo_v4_bw.jpg
│   ├── HAP-E_logo_v5.jpg
│   ├── HAP-E_logo_v5_bw.jpg
│   ├── HAP-E_logo_v6.jpg
│   ├── HAP-E_logo_v6_bw.jpg
│   └── HAP-E_logo_vBW.jpg
└── psd
    ├── HAP-E_logo_v4.psd
    ├── HAP-E_logo_v5.psd
    ├── HAP-E_logo_v6.psd
    └── HAP-E_logo_vBW.psd
```