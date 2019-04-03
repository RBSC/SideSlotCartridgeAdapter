--------------------------------------------
Side Slot Cartridge Adapter Module v1.1
Copyright (c) 2019 RBSC
--------------------------------------------

WARNING! To avoid damage to the adapter and your MSX computer never insert or remove the adapter when a computer is powered on!

WARNING! Do not connect more than one cartridge to the adapter! The adapter is not designed to supply the power to more than
one cartridge. Besides, the slot expander connected to the adapter will not work correctly and may create a power surge risk.

IMPORTANT! It is highly recommended to secure the adapter in the slot with the long screw, that the original module was secured
with. Otherwise there's a risk of pulling the adapter out of its slot when trying to pull out a cartridge. Before installing
the screw, please make sure that the flat ribbon cable is carefully split in two and that the screw will not damage the cable
when inserted. Please do not tighten the center screw too much. Once the bottom cover starts to move down with the screw, it's
enough to hold the module in place. If you tighten the screw too much, you risk to damage the bottom cover.


About
-----

The device is the simple 60 to 50 pin adapter that is used in the side slot of certain MSX computers. It can be used with Yamaha
MSX YIS503, CX5M, CX5MII and similar MSX machines. The main idea behind the project was to introduce the possibility to have 3
available slots for cartridges instead of just one (or two).

The adapter has 1-to-1 connections between the 60 pin and the 50 pin slots. The wiring is done with the flat ribbon cable that
is used for IDE and floppy cables. The device has a very limited amount of parts that makes it really affordable. The 3D models
for the case, the cover and the pin are provided. The cables are assembled using the 50-pin male IDC connectors and the IDC
crimping tool with the special adapter for male connectors. See the partslist.txt file and the 'Tools' section below for more
info.


Case
----

The model of the case and the cover must be printed with 0.2mm layer height and with their open sides facing upwards. The pin
is printed vertically and then glued to the main case. Brim is recommended for all models. Supports must be at 15-20%. The
infill must be not lower than 25%.

The module's cover is attached to the case with 4 conical head screws (3.0mm x 20.0mm) that can be bought in any hardware
store.


Tools
-----

The following IDC crimping tool should be used to make the internal cable:
https://www.aliexpress.com/item/Flat-Ribbon-Cable-Connector-Fixture-IDC-Crimping-Tool-DIY/32792508854.html

The tool requires the special adapter for male IDC connectors:
https://www.ebay.de/itm/2pc-Adaptor-for-IDC-DIP-Plug-Crimping-tool-HT-214D-Crimper-Width-0-1-0-3-0-6/131173729141

Or you can print the adapter yourself:
https://www.thingiverse.com/thing:3504332


Notes
-----

In many MSX machines with the side slot capability, this slot is expanded by default. If a cartridge that is capable of expanding
its own slot is used with the adapter, then only the first device of the cartridge will be available in the corresponding
subslot by default. 

For example if Carnivore2 cartridge with the default configuration (Flash/SCC+RAM+IDE+FMPAC) is inserted into the adapter on a
YIS503III or similar machine, only the Flash/SCC will be available. You can, however, configure Carnivore2 to work as either a RAM
expansion, as FMPAC sound card or an IDE device. But the combination of those will not be possible.


IMPORTANT!
----------

The RBSC provides all the files and information for free, without any liability (see the disclaimer.txt file). The provided information,
software or hardware must not be used for commercial purposes unless permitted by the RBSC. Producing a small amount of bare boards for
personal projects and selling the rest of the batch is allowed without the permission of RBSC.

When the sources of the tools are used to create alternative projects, please always mention the original source and the copyright!


Contact information
-------------------

The members of RBSC group Wierzbowsky, Tnt23, Ptero, Pencioner and DJS3000 can be contacted via the MSX.ORG or ZX-PK.RU forums. Just
send a personal message and state your business.

The RBSC repository can be found here:

https://github.com/rbsc

The MSX-related 3D models published by RBSC can be found here:

https://www.thingiverse.com/groups/rbsc/things


-= ! MSX FOREVER ! =-
