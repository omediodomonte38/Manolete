# Manolete
Manolete: Combat robot created for the OSHDEM 2025 Antweight 1lb combat competition.

Created by:


[PHOTO here]

## Introduction

The design of Manolete 2025 is an iteration of Manolete 2024. The robot is a beater-bar type. Due to the weight of the 2024 model, for 2025 we decided to start from scratch and, instead of using 3D printing, we used CNC-cut or manually cut parts in order to reduce weight and increase strength. The weapon has been changed from plastic to aluminum to increase its destructive capacity.

## Parts
- [Wheel Motors (400rpm)](https://a.aliexpress.com/_EvYxx0i)
- [Weapon Motor (1200KV)](https://a.aliexpress.com/_EvVvyQE)
- [Screws (m2 y m3)](https://a.aliexpress.com/_EGK4m7c)
- [Heat-Inserts](https://a.aliexpress.com/_EweGZSe)
- [Belt (s3m-165-55T)](https://a.aliexpress.com/_EwXwIhg)
- [Pulley (s3m-15T)](https://es.aliexpress.com/item/1005007624969629.html)
- [Carbon fibre (1.5mm) — 10x11cm sheets](https://a.aliexpress.com/_Ey8keHu)
- [7075 aluminium (3.7 x 8 x 1.5 cm hollow piece)](https://www.randrade.com/recortes/1454-chapa-aluminio-en-aw-7075-t6-de-espesor-recortes.html)
- [Polycarbonate 5mm](https://www.randrade.com/recortes/1817-chapa-policarbonato-incoloro-espesor-recortes.html)
- [Countersunk screws M4 of 1.5cm](https://rayteyper.es/)
- [Wheels (1/10 RC Car)](https://es.aliexpress.com/item/1005009454745832.html)
- O-rings, for shock absorption, graciously donated by Mateo's grandpa

## Manufacturing

### Sides a.k.a. "tenedores"/"forks"
Manolete's sides, colloquially known as the forks, are fundamental to the robot's strength. They are made from Lexan (polycarbonate), cut with the CNC milling machine [eshapeoko from bricolabs](https://www.bricolabs.cc/wiki/herramientas/eshapeoko). The STL can be found [here](3D/Side_Support_5mm.stl). The bottom part, much like the sides, is also made from polycarbonate

### Top and bottom plates
Manufactored from carbon fiber of 1.5mm of thickness, these plates confer the robot most of its rigidness. They have been manually measured and cut by us, using an axle grinder (Silicosis warning)

### Weapon
The weapon, the most relevant part of the robot, has been created from Aluminium 7075 for added hardness. From a solid block, we machined the shape using the [HBM BF 28 Profi Vario milling machine from bricolabs](https://www.bricolabs.cc/wiki/herramientas/fresadora_hbm_bf_28_profi_vario) in conjunction with a vertical drill, also from bricolabs. The weapon includes several screws to focus the hits and add reach to the weapon.

## Assembly

The sides and top plates are assembled using wood screws, threaded onto the polycabronate. For added shock absorption we added o-rings. The weapon motor is threaded, in the same way (wood screws) to an inner wall made of plycarbonate, placed in the middle of the robot chasis. The motor connects to the weapon using a s3m pulley with 3D printed gears, threaded onto the weapon. The weapon axle is a screw, fixed to the sides using nuts.

## Electronics

The robot is driven through a simple receiver with brushed motors (and corresponding esc) and brushless motor for the weapon (also with corresponding esc). 










