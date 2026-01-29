# Carveoff

Carveoff is a toolhead based off of [Takeoff Toolhead](https://github.com/Kizime123/Takeoff-Toolhead) designed to be milled rather than printed with SLM.

![Carveoff](Images/Carveoff.jpg)

## Features

* Removable belt clips that make pretensioning a breeze

  <img src="Images/Belt_Clip_1.jpg" height="300px"><img src="Images/Belt_Clip_2.jpg" height="300px"><img src="Images/Belt_Clip_3.jpg" height="300px">
* Ability to attach and detach the toolhead without disassembly
  * Attach
    
    <img src="Images/Attach.gif" height="300px">
  * Detach
  
    <img src="Images/Detach.gif" height="300px">
* Alignment feature that mates with the linear rail carriage to ensure the toolhead is installed straight

  <img src="Images/Alignment.jpg" height="300px">
## Requirements


* 9mm inverted belt path with 4mm spacing ([Monolith](https://github.com/Monolith3D/Monolith_Gantry) belt path)
* [Tricorn hotend](https://github.com/tricornhotend/tricornhotend.com)
* [LGX Lite Pro extruder](https://www.bondtech.se/product/lgx-lite-pro-extruder)
* [Beacon H](https://beacon3d.com/product/beacon-h/)
* SLM or printed ducts from Takeoff toolhead

## Considerations

Carveoff was designed to be milled on a hobbyist desktop CNC mill, specifically a Carvera. As such:

* The deepest pocket is 12.5mm.
* There are a number of blind M3 threads, maximum 6mm deep.
  * These can be tapped by hand or with a thread mill.
* All parts can be made with a traditional 3-axis mill.
  * The carriage may be easier to mill with a 4th axis.
* Recommended tools:
  * 1/8" or 3mm x 15mm endmill
  * 2mm x 8mm endmill
  * 1mm x 3mm endmill
  * 45&deg; chamfer mill
* All dimensions are nominal.
  * Adjust for tolerances as needed.
* CAM is left as an exercise to the reader.

## License

Carveoff is licensed under the [GNU General Public License v3.0](LICENSE).

## Acknowledgements

* Burgo for the name "Carveoff"
