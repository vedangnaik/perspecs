# Perspecs

Perspecs is a 3D-printed frame for my spectacles. The name is a play on 'perspex', a type of plastic, and 'specs', a commonly-used shorthand for spectacles. This is a personal project, custom-modelled for my prescription lenses. Do not expect them to work out of the box for yours. However, the models should make a good starting point for customization. Plese use SolidWorks 2020 or for best compatibility with these models.

## Parts
1. 3D-printer-ready PLA plastic
2. Replacement spectacle nose pads

## Tools
1. Solidworks 2020
2. Cura
3. AnyCubic Chiron
4. Sandpaper and scissors
5. Hot glue gun

## Cura Settings
The settings below produced decent results on the Chiron I used. The base template was the default Cura `0.1` template, with the following changes made for each part. All parts were printed with only walls and 0% infill.
* `bridge.SLDPRT`:
  - Print speed: 15 mm/s
  - Build plate adhesion: Brim
  - Wall count: 12
* `left_temple.SLDPRT` and `right_temple.SLDPRT`:
  - Print speed: 25 mm/s
  - Build plate adhesion: Skirt, 4 layers
  - Wall count: 6
