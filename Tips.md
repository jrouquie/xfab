## Organisation

Don't forget your USB key when leaving X-Fab.

## Dimensions

There is a high chance for the final dimensions to differ slightly from the one defined in the CAD software. In order to correct those it is recommanded to model parametrically.

* laser: the cut has non-zero width, this is called burn factor or kerf. Depending on the power the laser will scrape more or less material.
* 3D printer: this depends on the calibration of the machine.


## Laser tips

Opening an svg file in Corel Draw to send to the laser cutter: make sure there is no opacity/blur. Prefer plain svg to Inkscape svg format.

Trotec: In jobControl, it's often impossible to select a job on the plate when it's only a thin line. One solution is in corel print options (before sending the job to jobControl): uncheck «minimize to job size».

Burn marks on lasercut wood: masking tape may help. Also the orange soap could clean them afterwards.

Make sure the dimension in Corel are the one of the laser working surface (Epilog: 304.8 x 609.6 mm) otherwise your cuts will be shifted.
Lines of width 0.01 to 0.07 inch are cut, larger lines are engraved. Safe settings to have lines cut are 0.1mm or "thin line".

Color mapping: it's safer to set the laser power to 0 in the default tab, so that unmapped colors won't fire the laser. In case of problems, see https://sawmillcreek.org/showthread.php?211156-Color-Mapping-Not-Overriding .

Very large pixels for raster engraving (like terrible resolution of 6 DPI). For me the solution was to edit the bitmap image in Gimp (not Corel) to remove color profile, remove transparency, convert to grayscale (not rgb) (not sure which one of the three are really needed). Also, if you need to rotate the bitmap, do it ouside of Corel, the resolution loss isn't as pronounced but still unacceptable.


## Ultimaker

Clean after yourself (support, extrusion test spirals) and make sure no plastic part falls under the plate.

## Upbox tips

Those 3D printers are highly delicate, they decalibrate and get clogged really easily.
Before launching your print make sure the plate temperature reached 80°. Center your model as much as possible. Be gentle to the plate.
Sometimes Fast/Turbo prints work better.

## Builder

The printing heads are costly, this is why no print can be launched without the validation of the FabManager.
Once launched the extruder ratio needs to be put to 50 so that both spools are used.

## Stratasys

The prints are expensive, this is why no print can be launched without the validation of the FabManager.
Printing in glossy consumes less material.
The support is slightly toxic so use nitrile gloves to manipulate them, wash your hands with cold water if you touched them without.
The prints need to be cleaned with high pressure water.

## Polysher

The polishing is restricted to the pieces which were printed with a PolySmooth filament and those who can be inserted in the machine.

## Flex printing

The Ultimaker 2 is usually loaded with NinjaFlex filament. Parameters need to be tuned to print successfully.
Select Custm3  and tune the following parameters:
- no ventilation
- 40% filling
- 239°C filament temperature
- 60°C plate
- speed 16%
- material flow 140%
- printing speed 30 mm/s
- displacemnt speed 60 mm/s

## Glass fiber

 [Polypropylene loaded with glassfiber](http://www.ocvreinforcements.com/pdf/library/XSTRAND_3D_Range_product_sheet_Rev2_January_2018.pdf) was successfully printed with an UpBox

## Markforged
Turbo support worked for me and is slightly cheaper in material.
If printing threads: if possible, prefer to print the hole rather than the screw. If you use support, it will add support between ridges, which needs to be removed with a die (or tediously, with a box cutter).


## Wood-loaded PLA printing

## CIF CNC

This machine is delicate, users should be trained individually before operating it. The Z is done using the multimeter. Use double sided tape to fix your sheet. Make sure the sheet is horizontal (no overlaping tape). If the paths are not well isolated, do not hesitate to mill several times with the Magnetoscope option.

## Charly CNC

A damaged mesh could result in vibrations. Use plexi, double sided adhesive tape and wood spacer to block your material. Don't forget to switch the pressure arrival off when stopping. Select Avalant to mill the borders. 
