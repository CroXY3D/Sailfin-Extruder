# Sailfin-Extruder
A lightweight compact extruder with 5:1 gearing using BMG dual drive.   It is capable of pushing up to 48mm^3/s through a 0.4 nozzle.

Footprint is a very compact 41x45mm and weighs 107g (with steel fasteners).

Regular and mirrored version.   STEP files provided.  

There also is a version of the middle body which is compatible with toolheads designed for the Sherpa extruder.

This is a BETA release.  An official release will be made when it has been tested further.

Special thanks to Anlin over at Annex Engineering and his Sherpa mini extruder for inspiring the creation of Sailfin.

![Sailfin](https://github.com/CroXY3D/Sailfin-Extruder/blob/main/images/sailfin_large.png)

![Sailfin Scale](https://github.com/CroXY3D/Sailfin-Extruder/blob/main/images/sailfin_scale.jpg)


# BOM
* [LDO 17mm Nema14 Stepper with gear LDO-36STH17-1004AHG](https://www.printedsolid.com/products/ldo-nema-14-motor-ldo-36sth17-1004ahg?variant=32690500370517) or 20mm version LDO-36STH20-0504AHG which has more torque.
* [Bondtech BMG or clone internals.  Triangle Lab preferred](https://www.aliexpress.com/item/4000021186440.html)
* 1x M3x25 BHCS (SHCS may be used as well for all BHCS)
* 2x M3x14 BHCS
* 2x M3x10 BHCS
* 5x M3 Heatserts [McMaster](https://www.mcmaster.com/94459A130/) [AliExpress M3xD4.6x4](https://www.aliexpress.com/item/4000232858343.html)
* Short length 2mm ID, 4mm OD PTFE tube.
* Optional [Nema14 heatsink](https://www.filastruder.com/products/heatsink-for-pg35l-geared-stepper-motor?_pos=5&_sid=4f2b94743&_ss=r).  Enables higher motor current and more torque.  The motor is same diam as other 540 size RC motors so there are other heatsinks available from RC shops.
* Optional [Thermal tape for the heatsink](https://smile.amazon.com/Thermal-Adhesive-Performance-Heatsink-Computer/dp/B085CLXM7J/ref=sr_1_3?dchild=1&keywords=thermal+tape&qid=1617072316&sr=8-3)

# ASSEMBLY
Assembly is fairly straightforward.  

There are two parts with small membranes in holes to make printing a solid bridge.  Drill with 3mm drill bit the membrane on the lever and the membrane on the rear piece.

You may need to either push the white gear down 1-2 mm if it rubs on the Nema 14 motor.  Alternatively you may carefully grind off 1-2mm of the shaft.  Be careful of heat so you don't melt the nylon gear.

The cut guide helper is intended to help you cut the PTFE tube.   Place the PTFE tube in your toolhead and position the cut guide above it.  Use a razor blade to cut the tube.  It's helpful to countersink the top end of the tube with a chamfer bit or a conical deburring tool.

# TOOLHEADS

Toolheads are available for the following:
* Tiny-M V3 Gantry Dragon Toolhead
* Tiny-M V4 Gantry Toolhead (on Tiny-M GitHub)
* Voron V0 Dragon
* Voron V0 V6 Screw Mount

There is a version of the middle body that should be compatible with most Sherpa toolheads.  The motor sits a couple mm lower on the Sailfin, so you may also need a 2mm thick printed spacer to raise the Sailfin.

If you design a toolhead around it, let me know and i'll link or post STLs here.

There will be a Sailfin toolhead for CroXY soon.   

[Nice V0 toolhead that supports Sailfin](https://github.com/KurioHonoo/Mini-AfterSherpa/)

# MODS

None yet other than the version with Sherpa toolhead footprint.  But have at it!  Let me know what you did and I'll post a link or STLs here.

![Tiny-M Toolhead](https://github.com/CroXY3D/Sailfin-Extruder/blob/main/images/tiny_m_dragon.png)

