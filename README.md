# Supernova Shipyard Source
 Blend files for Supernova-Shipyard: [Github](https://github.com/NebulaTank/Supernova-Shipyard), [Sketchfab](https://sketchfab.com/NebulaTank/collections), [Deviantart](https://www.deviantart.com/NebulaTank/gallery/75126808/spaceship-showcase)
 
# Blend files

[Ship template](https://github.com/NebulaTank/Supernova-Shipyard-Source/blob/main/Blends-%20Ships/Ship%20Template.blend)

# Photoshop actions

## LASIK
### Unsharp Mask
* Amount: 315%
* Radius: 1 pixels
* Threshold: 0

### Image Size
* Width: 50%
* With Scale Styles
* With Contstrain Proportions
* Interpolation: Automatic

## Half Size
### Image Size
* Width: 50%
* With Scale Styles
* With Contstrain Proportions
* Interpolation: Automatic

## Make Mask
### Make adjustment layer
* Using: adjustment layer
* Type: hue/saturation
* Preset Kind: Default
* Without Colorize

### Set current adjustment layer
* Hue: 0
* Saturation: -100
* Lightness: 0

### Make adjustment layer
* Using: adjustment layer
* Type: brightness/constrast
* With Use Legacy

### Set current adjustment layer
* Brightness: 100
* Contrast: 100

## Make Engine 10-5 (for info pictures)
### Duplicate current layer

### Set current layer
* To: layer
* Mode: Screen
* Convert to smart object

### Gaussian Blur
* Radius: 5 pixels

### Duplicate current layer

### Set filter effects 1 of current layer
* filter params: Gaussian Blur
* Radius: 10 pixels

### Make fill layer
* Using: fill layer
* Type: solid color
* Slot color: RGB color
* Red: 255
* Green: 143.998
* Blue: 0

### Set current layer
* To: layer
* Mode: soft light

### Duplicate current layer

### Set current fill layer
* To: solid color
* Slot Color: RGB color
* Red: 255
* Green: 95.999
* Blue: 0

### Move current layer
* To: layer 2
* Without adjust selection

## Make Engine 4-2 (for rleDs)
Same as above but with 4/2 as the radius for the gaussian blurs

## Make Weapon
### Duplicate current layer

### Set current layer
* To: layer
* Mode: screen
* Convert to smart object

### Gaussian Blur
* Radius: 2 pixels

### Duplicate current layer

### Set filter effects 1 of current layer
* filter params: Gaussian Blur
* Radius: 4 pixels

## Make lights
### Set current layer
* To: layer
* Opacity: 75%

### Duplicate current layer
* Convert to smart object

### Set current layer
* To: layer
* Mode: screen

### Gaussian blur
* Radius: 4 pixels

### Duplicate current layer

### Make layer

### Fill
* Using: background color
* Opacity: 100%
* Mode: normal

### Move current layer
* To: layer 0
* Without Adjust Slection

## Remove Black
### Duplicate current layer

### Make adjustment layer
* Using: adjustment layer
* Type: Black and White
* Preset Kind: Default
* Red: 40
* Yellow: 60
* Green: 40
* Blue: 20
* Magenta: 80
* Without tinting
* tint color: RPG color
* Red: 225
* Green: 211
* Blue: 179

### Make adjustment layer
* Using: adjustment layer
* Type: curves
* Preset kind: default

### Set current adjustment layer
* To: curves
* Preset kind: custom
* Adjustment: curves adjustment list curves adjustment
* Channel: composite channel
* Curve: point list
* Point: 10, 0
* Point: 66, 255

### Select layer "Layer 1 copy"
* Modification: Add Continuous
* Without Make Visible

### Merge Layers

### Set Selection
* To: all

### Copy

### Delecte current layer

### Make
* New: channel
* At: mask channel
* Using: reveal selection

### Select current channel
* With Make Visible

### Paste
* Anti-alias: none
* As: pixel

### Select current channel
* Without Make Visible
