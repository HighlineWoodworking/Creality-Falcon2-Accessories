# Creality Falcon2 Base

Provides a secure foundation for a [Creality Falcon2 Laser Frame](https://www.creality.com/products/creality-falcon2-22w) and supports precise, repeatable positioning of work pieces.

<img src="images/base_top_view.png" alt="Falcon2 base 3d rendering." width="50%" />

## Tools and Materials

* CNC machine capable of machining a 26 x 30 inch piece
* 1/2 inch MDF 650 x 744mm which leaves a 20mm margin on each edge for hold-down clamps
* 1/4 inch end-mill, only absolutely required bit, good examples:
  * [Cadence Manufacturing "The Jenny"](https://www.cadencemfgdesign.com/product-page/the-jenny-bit-8675309)
  * [Woodpeckers US2102C](https://www.woodpeck.com/ultra-shear-quarter-inch-spiral-compression-bits.html)
* 90 deg v-bit
  * [Amana RC-45711](https://www.amazon.com/Amana-RC-45711-Insert-Carbide-Groove/dp/B003DCMDRU)
* 4mm up-cut
  * [Woodpeckers US204MU](https://www.woodpeck.com/ultra-shear-metric-mortising-bits-for-domino-tenons.html)
* 4mm alignment pins
  * [Amazon Asamuyu stainless steel pins](https://www.amazon.com/Stainless-Shelves-Hardware-Support-Fastener/dp/B0D1VHPK3Y?th=1) - very tight fit
  * [Amazon uxcell 4mm wooden dowels](https://www.amazon.com/uxcell-Beveled-Hardwood-Woodworking-Furniture/dp/B0BJTX5PRV/ref=sr_1_40)
  
## Machining

### 90deg V-bit

* softens edges, makes feet easier to insert, adds label
* machine along the vectors
* layers ```Outlines and Feet Insets``` final depth 1mm
* layer ```Highline Woodworking``` 0.2mm (skip entirely if you don't want the text label or change to your own)

### 4mm Up-Cut

* 5mm spaced holes for 4mm alignment pins
* layer ```Alignment Holes``` final depth 5mm
* drill peck holes

### 1/4 inch End-Mill

* cuts insets for feet and the final outline for the piece
* layer ```Feet Insets``` area clear inside the circles, final depth 8mm
* layer ```Outlines``` cut outside the vectors, 13.1mm final depth
  * add bridges or other supports
  * example bridges: 8 x 30mm long x 1mm thick
 
### Reference Grid

See [Engraving the Reference Grid](reference_grid.md)

## Files

* base_v01.art = [Carveco Maker](https://carveco.com/carveco-software-range/carveco-maker/) source file
* base_v01.dxf = [DXF](https://en.wikipedia.org/wiki/AutoCAD_DXF) exported source file
* base_v01.dwg = AutoCad drawing file created with [Siemens Solid Edge 2D](https://resources.sw.siemens.com/en-US/download-free-2d-cad-software/)
* laser_grid.nc = [G-code](https://en.wikipedia.org/wiki/G-code) file to burn a reference grid into the completed MDF base

## Dimensions

<img src="images/main_dimensions.png" alt="Main dimensions." width="50%" />

<img src="images/alignment_hole_dimensions.png" alt="Alignment hole dimensions." width="50%" />

## Images

<img src="images/installed_base_with_grid.png" alt="Installed base." width="50%" />

<img src="images/base_feet.png" alt="Base feet." width="50%" />

<img src="images/alignment_pins.png" alt="Alignment pins." width="50%" />

## Versions

* v01 | 10-Feb-2025 | inital post






