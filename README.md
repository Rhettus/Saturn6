# Saturn 6 
Saturn 6: a compact 10” minilab that hosts 5xRaspberry Pi's and an ARM based NAS.

## Printed parts

All chassis parts were printed in PETG

All faceplates were printed in PLA

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license.

You are free to:  
- **Share**: Copy and redistribute the material in any medium or format.  
- **Adapt**: Remix, transform, and build upon the material.  

Under the following terms:  
- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made.  
- **NonCommercial**: You may not use the material for commercial purposes.  
- **No Additional Restrictions**: You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.  

A copy of the full license text can be found [here](https://creativecommons.org/licenses/by-nc/4.0/legalcode).

If you use or remix these files, I'd love to hear about it! Feel free to share your projects or modifications.

## BOM
BOM for Saturn 6 project

Parts for build
 - [Slim Cat6 patch cables](https://a.co/d/a7xnncM)
 - [140mm fan for exhaust](https://a.co/d/3VLQnNa)
 - [Threaded M4 rods](https://a.co/d/84yPzoR) to hold the Pi cluster together. These will need to be cut down.
 - M4 Nuts
 - [2x 2.5Gbe PoE switches](https://a.co/d/4PgA6Y8) with SFP+
	[0.3m DAC cable](https://a.co/d/iWrGbuD)
 - [2020 corner joints](https://a.co/d/eAyFSsW)
 - [Din rails](https://a.co/d/hCQvD7X)
 - [38mm Compressor feet](https://a.co/d/a7xnncM)
 - [600mm 2020 Extrusion](https://a.co/d/5f3lkJL) 4x400mm and 8x214mm
 - [6 outlet PDU](https://www.aliexpress.us/item/3256805777681738.html?spm=a2g0o.order_list.order_list_main.5.21ef194d0AyTGm&gatewayAdapt=glo2usa)
 - [QuickPort F-Type Adapter](https://a.co/d/gwulnIx) - for rear skirt internet connection
 - M5 screws - button head for the front
 - [M5 T-nuts](https://a.co/d/aCP52xv) (lots)
 - M3 screws for top panel clips, panel clips and the switch chassis ears
 - M3 Heat set inserts for switch ears and DIN brackets
 - 17x Cat 6a keystone jacks 

Printed parts not included
 - 16x[ Voron panel clips](https://www.printables.com/model/702768-kit-for-removable-panelsdoors-for-voron-v2trident-/files). 
 - 4x[Bottom Corner Bracket](https://www.printables.com/model/702768-kit-for-removable-panelsdoors-for-voron-v2trident-/files) - 1mm Foam Tape - Use for top panel
 - 4x[Compact ZeroG Bracket Mod](https://www.printables.com/model/519670-compact-zerog-din-bracket-mod)

## Known issues:

- The RPi holders that fit the PoE & NVMe hat block off USB power port. Not an issue for me
- The width of the RPi holders is too wide to fit the threaded screw between the extrusions. Need to trim a couple of mm off each holder and redo the ears. I assembled in the rack.


Work in progress


## Attributions
Thanks to the wonderful creators and licensing under CC. These are the 3D files I either used, or remixed for Saturn 6 which were not my own                                                                                                 
| Part                    | Creator                                                                             | Link                                                                                                                       | Modifications                                                                                                                              |
| ----------------------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Fan cover               | [StoniXX](https://www.thingiverse.com/StoniXX)                                      | https://www.thingiverse.com/thing:5488632                                                                                  | Removed bottom bracket                                                                                                                     |
| 2020 Handles            | [Andreas_34203](https://www.printables.com/@Andreas_34203)                          | https://www.printables.com/model/10745-handle-for-2020-aluminum-extrusion                                                  | -                                                                                                                                          |
| Patch panel - front     | [Weinachten](https://www.thingiverse.com/Weinachten)                                | https://www.thingiverse.com/thing:5992963/files                                                                            | Removed some of the strengthening and changed to standard front plate design                                                               |
| Patch panel - rear      | [Weinachten](https://www.thingiverse.com/Weinachten)                                | https://www.thingiverse.com/thing:5992963/files                                                                            | Reduce to 7 ports to give room for PDU                                                                                                     |
| RPI cluster             | [russross](https://www.thingiverse.com/russross)                                    | https://www.thingiverse.com/thing:4078710                                                                                  | Made wider to accomodate the PoE Hat (with GPIO pins)                                                                                      |
| Voron panel latches     | [Victor Mateus Oliveira](https://www.printables.com/@VictorMateusO_607762)          | https://www.printables.com/model/702768-kit-for-removable-panelsdoors-for-voron-v2trident-/files                           | -                                                                                                                                          |
| Voron top panel corners | [Victor Mateus Oliveira](https://www.printables.com/@VictorMateusO_607762)          | https://www.printables.com/model/702768-kit-for-removable-panelsdoors-for-voron-v2trident-/files                           | -                                                                                                                                          |
| Keystone jack           | [PR1NT3D](https://www.thingiverse.com/PR1NT3D)                                      | https://www.thingiverse.com/thing:5902371                                                                                  | Integrated into NAS front panel and and rear skirt                                                                                         |
| CM3588 NAS case         | [@Fuzzler_1944079](https://www.printables.com/@Fuzzler_1944079)                     | https://www.printables.com/model/826870-friendlyelec-cm3588-nas-case-for-10-rack                                           | Flipped the mount, added led light holes, keystone for rj45, room to install the keystone jack. Replace front panel with Saturn 6 standard |
| Unifi USG               | [dewenni](https://www.thingiverse.com/dewenni)                                      | https://www.thingiverse.com/thing:6145449                                                                                  | -                                                                                                                                          |
| Din drop downs          | [----------------------------------------](https://www.printables.com/@_172228)     | https://www.printables.com/model/519670-compact-zerog-din-bracket-mod                                                      | Extended 5mm lower to have room for xfinity router                                                                                         |
| Mercury One 38mm Feet   | [ZeroGDesign](https://github.com/ZeroGDesign/docs/commits?author=ZeroGDesign) | https://github.com/ZeroGDesign/docs/blob/gh-pages/docs/assets/stl/electronics_enclosure/skirt/SK_FT_38mm_PowerSW.stl       | -                                                                                                                                          |
| 7 ethernet cable holder | [luon45](https://www.thingiverse.com/Gluon45)                                       | https://www.thingiverse.com/thing:4159459/files                                                                            | Printed at 110% to support CAT6a                                                                                                           |
| USB plug for Pi labels  | [mfischer79](https://www.printables.com/@mfischer79)                                | https://www.printables.com/model/404578-usb-a-dust-coverplugcap                                                            |                                                                                                                                            |
| Ethernet cable labels   | [flol3622](https://www.printables.com/@flol3622)                                    | [https://www.printables.com/model/72401-ethernet-cable-label](https://www.printables.com/model/72401-ethernet-cable-label) | Printed at 110%                                                                                                                            |
