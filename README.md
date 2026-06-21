# Tonys-Gear-Box-Display
A harmonic, cycloidal, and planetary gearbox driven on one motor



<p align="center"><img width="630" height="893" alt="image" src="https://github.com/user-attachments/assets/9c66326a-a961-4d1e-b5a1-bde53ed95b59" />
  
Hi! to whoever is reading this, I made this project becuase I wanted to have a better undersanding of common and uncommon ways to produce gear reduction, and every since finding out about cycloidal gearboxes I've been fascinated by the way they move and how to generate so much power without teeth. 

  
# CAD

- Onshape link: https://cad.onshape.com/documents/11a15da13425e31e4c0edb3a/w/1d53f7d84e63cf7b32fcd030/e/eb923a8e6ac061088489cd3c?renderMode=0&uiState=6a339ba31d4e4c91f8b38977

<img width="4196" height="2547" alt="Harmonic Gearbox Assembly" src="https://github.com/user-attachments/assets/578f5726-86e8-48a6-91f0-caca032875f2" />
(Inside of Harmonic GearBox Assembly)

<img width="4196" height="2547" alt="Cycloidal Gear Box" src="https://github.com/user-attachments/assets/ac1c4324-6093-4f33-a778-29ded3f189a2" />
(Inside of Cycloidal GearBox Assembly)



<img width="4196" height="2547" alt="Stages 1 2" src="https://github.com/user-attachments/assets/37b2a913-f1be-4063-a0b2-ca38112ce8fd" />
(Inside of Planetary GearBox Assembly)


<img width="4196" height="2547" alt="Gearbox Display back view" src="https://github.com/user-attachments/assets/fff3085c-f3da-4e6b-b556-40bc1eefb2ef" />
(Full GearBox Assembly From the Back)


<img width="4196" height="2547" alt="Gearbox Display Front View" src="https://github.com/user-attachments/assets/e024eb90-fb3c-4c50-bfc5-897def5eb01c" />
(Full GearBox Assembly From the Front)

-------

Here I'd like to give thanks to GrabCad for hosting this model of the motor I'm Using for this project and this reddit thread that allowed me to skip doing all the math for the cycloidal gearbox

- https://www.reddit.com/r/Onshape/comments/1mckmf0/whats_the_easiest_way_to_make_a_cycloidal_drive/

- https://grabcad.com/library/jgb37-3530-geared-motor-1

-------

# Assembly

* Cycloidal

The Cycloidal Gear box has the most Hardwawre that is needed to assemble out of all three gear box types. 

Step one is to prepare and gather the needed materials for all three gear boxes, while doing so try and also make sure all 3d printed parts have had there M3 heated inserts heat pressed into them

Then you can start off by assembling the drive shaft and add the bearings

Afetr that Insert the bottom half of the output shaft and start stacking cycloidal disks (keep in mind that one of the three disks is different from the other two, that disk should be sandwiched in between the other two durring and after assembly)

When all disks are inserted you may now assemble the top half of the case and when everything fits into place, secure everything by using the screws. 

Make sure the drive shaft on the back of the Gearbox is properly installed and secure to the case

* Harmonic

Mount the wave generator to the drive Shaft

Then insert the drive shaft into the base, and make sure it is flush with the bottom

You can then insert the TPU gear and bend it around the wave generator

After that you can then take the top cover and secure the assembly with screws

* Planetary

Assemble the sun gears and planet gears by dropping in the planet gears into the triangles with gears at the top of them onto the rods they have on the bottom of them, and then clipping them in with the snap on clips 

After that you msy assemble each Stage by fitting the planet gears into the housing

on the front and back cover there are extrusions that allow pins to be places for mounting to the base, make sure the pins are installed before installing the front and back of the case

Then assemble the stages in reverse order from output to input allowing you to put on the driving planet gear and then the back cover of the case


* Full

Make sure you install the switch to the front cover of the base and the motor to the back, wire it so that the battery wire goes through the slot in the back into the battery tray, and leave right side up

You may now clip in the gear boxes, the planetary on top, the cycloidal to the right, and the harmonic to the left

Now place the pulleys on the driving shafts of each gearbox, after placing the pulleys  please install the belt

Now that everything is assembled the last thing to do is wire the battery and turn it on :)


<img width="741" height="877" alt="image" src="https://github.com/user-attachments/assets/38f511ea-b765-4a2e-99f2-482328b725ef" />
(wiring diagram)

--------

#BOM


| Index | Vendor      | Description          | Quantity | Unit Price($) | Extended Price($) | Product Link                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------|-------------|----------------------|----------|---------------|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | LCSC        | hanxia HX KCD11-2P-R | 5        | $0.16         | $0.78             | https://www.lcsc.com/product-detail/C6917318.html?spm=wm.fly.bg.1.xh___wm.fly.tp.18.ml&lcsc_vid=RAJZAVxQQFUIA11TQFBZV1YAQFlWBVNTE1cLAlICQ1cxVlNeRlZeX1xfT1ZbUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| 2     | Amazon      | M3 Heated Inserts    | 100      | $0.05         | $4.99             | https://www.amazon.com/gp/product/B0FM45X5TD/ref=ewc_pr_img_3?smid=AIMQC13A5VC4X                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 3     | EBAY        | 160T GT2 Belt        | 1        | $6.56         | $6.56             | https://www.ebay.com/itm/135168642404                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| 4     | Ali Express | DC Motor             | 1        | $10.37        | $10.37            | https://www.aliexpress.us/item/3256807873958725.html?spm=a2g0o.detail.pcDetailBottomMoreOtherSeller.1.7282vcgvvcgv1U&gps-id=pcDetailBottomMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=8c64ee22-13b4-4d73-9796-b5d693dfc2da&_t=gps-id%3ApcDetailBottomMoreOtherSeller%2Cscm-url%3A1007.40050.354490.0%2Cpvid%3A8c64ee22-13b4-4d73-9796-b5d693dfc2da%2Ctpp_buckets%3A668%232846%238113%231998&pdp_ext_f=%7B%22order%22%3A%22138%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%2C%22fromPage%22%3A%22recommend%22%7D&pdp_npi=6%40dis%21USD%2118.31%210.99%21%21%21123.06%216.66%21%402101e2b017817198635171806ef30d%2112000043493532314%21rec%21US%216805647519%21ABXZ%211%210%21n_tag%3A-29910%3Bd%3A3a14889%3Bm03_new_user%3A-29895%3BpisId%3A5000000209510139&utparam-url=scene%3ApcDetailBottomMoreOtherSeller%7Cquery_from%3A%7Cx_object_id%3A1005008060273477%7C_p_origin_prod%3A |
| 5     | Amazon      | Screws               | 321      | $0.03         | $8.99             | https://www.amazon.com/Washers-Machine-Assortment-Threaded-Furniture/dp/B0FGD91M1N/ref=sr_1_9?sr=8-9                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 6     | EBAY        | Wire                 | 1        | $5.99         | $5.99             | https://www.ebay.com/itm/192206619575?_skw=wire&itmmeta=01KVBCY2CC9QJQX3SHR8Z5FKMP&hash=item2cc06843b7:g:BBMAAOSw9HxlzuUm&itmprp=enc%3AAQALAAAAwGfYFPkwiKCW4ZNSs2u11xDHp2ABtFhnO%2BngdQ37zHUuoe2wqQoC4M8Mxa1rxbTr5didp32kPEAgVgVt5AKbUDcQDCTGrJ62J3%2FbND9cTfb%2FQ88BZYrxxiTdZbRXxonTg4k%2Bj%2FnQL6YryqSvblVxq%2BGV52TRMeKBudoKzGh%2BaLQxrZ5KeVu7BaOEPsdd5NHIOdSZ6v95I3ef4m%2BMMIf1maHkBj8Le5ITUHJPjcylGD%2Fj011WJGXz0D5YP84w%2FlMYhg%3D%3D%7Ctkp%3ABk9SR9am-OzaZw                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 7     | Amazon      | A23 Batteries        | 2        | $1.45         | $2.89             | https://www.amazon.com/Energizer-Mercury-Alkaline-Batteries-Packaging/dp/B00004YK10/ref=sr_1_3?sr=8-3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| 8     | REV         | Bearings             | 4        | $3.25         | $13.00            | https://www.revrobotics.com/ION-Bearings/                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|       |             |                      |          | Total =       | $53.57            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
