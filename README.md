# MotorizedGrabber
3d models, custom circuit board, design and parts list for a motorized grabber design

# Grabber Shopping List

2 mm outer thickness with 22 mm inner diameter alumuinum pipe, 2 meters 

3d printer and filament, carbon fiber PLA was used for this grabber but normal PLA should still work with possibly some tweaks to the models or maybe non at all as Carbon Fiber PLA and PLA have similar print characteristics
(Note that a sleve was used for fitting the adapter to the alumnium grabber pipe better after the lathe was used to trim the part till it fit with the alumium pipe, there is almost certainly another way to fit the aluminum pipe and the part together without such equipment. I would suggest tuning the fitting parts of the prints inner and outer diameter sizes till you can print a part that fits well with the aluminium pipe without any trim)

Drill Batterys and Charger https://www.amazon.com/dp/B07X2V5116/?coliid=I2IH57A649QSUQ&colid=3JNOTM74GBT0X&psc=1&ref_=list_c_wl_lv_ov_lig_dp_it

Round Head Machine Screw, 8-32-Inch x 1-Inch, 2 of them https://www.amazon.com/dp/B00843ER7W?ref_=cm_sw_r_cp_ud_dp_5XYYPG3079ASXCVBMPT5

Small Screws https://www.amazon.com/dp/B078ZVLFWY?_encoding=UTF8&ref=cm_sw_r_cp_ud_dp_73YYQMXGK250FDRDGENX&ref_=cm_sw_r_cp_ud_dp_73YYQMXGK250FDRDGENX&social_share=cm_sw_r_cp_ud_dp_73YYQMXGK250FDRDGENX&th=1

Micro Limit Switch	https://www.amazon.com/dp/B07X142VGC/?coliid=I23S51OHWOTIJK&colid=3JNOTM74GBT0X&psc=1&ref_=list_c_wl_lv_ov_lig_dp_it , I got the 10 pack of these but most limit switches will do as you only need one of them for the limiter

SPDT Push Button Switches https://www.digikey.com/en/products/detail/e-switch/700SP7B10M2QEH/502058 , I bought 4 when making it in case I messed up 2 but you only need 2 for the design

Custom Circuit Board for Grabber , The gerber files are in the repo, I used PCBWay for ordering the boards, you do have to mininum order 10 for 20 dollars but for this project it made soldering way easier and much more reliable then soldering directly to the pins.

A fair amount of 22 gage wire, I made an attempt at using quick connects to make the battery connection to the switches easier to disconnect but the current space issues make such things mildly difficult so you can just directly wire up the grabber and desolder for repairs. Annoying but with the space constraints it made sense at the time.

There are about 4 separate runs of wire you will have to run other then the wires built into the linear actuator
There are circuit diagrams that you can view from the photo section of the layout of the switch board or if you feel like not using it, it's going to tell you exactly how you have to run things.

Grabber 48"	https://www.amazon.com/dp/B000RUKZNU?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1 , this is the grabber that you need to basically need to cut and then combined with the other parts in this design
Or
Grabber 36" https://www.amazon.com/dp/B0000V0AGS/?coliid=I2SN9CFSNLCHWP&colid=3JNOTM74GBT0X&psc=1&ref_=list_c_wl_lv_ov_lig_dp_it , another grabber you can use if you want a shorter grabber for whatever reason, still works out the same for the most part

Battery Prongs	https://www.te.com/en/product-42214-2.html?te_bu=Cor&te_type=srch&te_campaign=ggl_usa_cor-ggl-usa-srch-fy23-smbmktg-pfm-emi-us_sma-2844_2&elqCampaignId=163125&gclid=Cj0KCQiAwJWdBhCYARIsAJc4idDtBZFJZNP_-SDxGzrRgCFeqgtEI1sV-STMod0eMnQQOVzPxxeOGPUaAlAhEALw_wcB , I bought 4 again also because I wanted backups but you only need 2\

Micro Linear Actuator https://www.amazon.com/dp/B0B9JPQDSV?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1, I bought 1 of these
(The gearing here is more aggressive then it needs to be on the 36" grabber but for the 48" it is required to get one of these as the gearing for a faster motor doesn't have enough static friction to keep the spring on the grabber from moving)





### An addendum on the PCB
You technically don't need this thing if your really determined but trust me when I say it really can be scuffed if you don't get this, if you are a beginner solderer I would recommend this and honestly even if your more experienced it just makes the whole circuit a lot neater. Having tiny 22 gage wires running inbetween the pins is messy, I rest my case. I have like 7 spares at this moment in time so if your really determined to not order a fresh batch you can attempt to reach out. The dupes also leave room for failures and they make for ok solder practice boards as well with the number of pins.

The spacing is also tiny there isn't a lot of room in the handle of the grabber so the board just made sense to keep things more neat

## Photos

![Switch Board Schematic](SwitchBoardSchematic.png)
![Switch Board PCB](SwitchBoardPCB.png)

(I used KiCAD for the board designing program)
[GerbersAndProductionFiles](SwitchBoard/pcbway_production)
Also use the settings listed in the [GrabberPCBSpecs](GrabberPCBSpecs.pdf)

