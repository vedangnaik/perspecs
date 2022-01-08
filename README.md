# Perspecs

Perspecs is a 3D-printed frame for my spectacles. The name is a play on 'perspex', a type of plastic, and 'specs', a commonly-used shorthand for spectacles. Smart spectacles like the A.I. powered ones worn by Iron Man and Spiderman have always captured my imagination; this project was a way for me to explore that idea in real life. 

In this model, the custom nosepeice and temples allow for all sorts of interesting things to be encased within; for example, in the picture below, I've created a SD card holder in the right temple. With slight modifications, one could also embed small PCBs, batteries, and other doodads to enable all sorts of functionality.

![image](https://user-images.githubusercontent.com/25436568/148285251-99660357-a8ac-4891-93b0-0f7d8de47d6c.png)

*Note: These models have been custom-made for my prescription lenses. Do not expect them to work out of the box for yours. However, the models should make a good starting point for customization.*

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
