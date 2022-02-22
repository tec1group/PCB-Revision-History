# PCB Revision History
A brief history of TEC-1 PCBs and their design variations.

The TEC-1 PCB has undegone several revisions over time. Although the designs are all very similar and generally software bacwards-compatible (Same meomry map, IO port map, keyboard layout etc.), there are some subtle differences that may be of interest to collectors, programmers and the like.

This list will serve to attempt to document the evolution of the design both at TE, and post-TE time.

## PCB Basics and Production Runs

PCB's were generally made in batches of 100 at TE and typically changed colour each batch (but not always). Between the basic design revision and the colour, the age of the machine can thus be roughly dated.

No precise record was kept of manufacturing dates and boards were not serial-numbered, so this information is being 'reverse engineered' and is mainly educated guesswork on the part of TEC owners and former TE staff. It is not to be taken as absolute or 100% accurate.

In short, the following major design revisions exist:

## Design Revisions

- TEC-1 (Issue 10, original, 1983). 7805 regulator above PCB bottom left corner. 8212 display latch chips. No Shift key. MON-1 monitor ROM by John Hardy.

- TEC-1A (Issue 12). Issue 12 page 14 states "The regulator is mounted under the PC board so that it cannot be bent over and broken off, the 2,200uf electrolytic has been changed to 1,000uf and the output latches have been changed to 74LS273 (or 74LS 374 or 74LS377). In all other respects, the boards are identical."

- TEC-1B (Issue 13). Adds SHIFT key and MON-2 Monitor ROM by Ken Stone.

- TEC-1B Rev.1 (Just before issue 15, 1990). Minor improvements by Craig Hart including improved labelleing of IO & memory decoder outputs, CPU pin labelling, improved IO and memory map decoding, JMON resistor.

- TEC-1C (After Issue 15, 1991). CAD version by Craig Hart including mods for JMON resistor and better MON1/2 select switch, smaller speaker.

- TEC-1D Reproduction board by Ben Grimmett, 2018. Includes all mods to date.

- TEC-1E "MIT-Z" design by Ken Stone, 2020. significant design changes, improvements and expansions.

- TEC-1F Reproduction board by Craig Jones. 2021. Supports original 2k or alternate 8k ROM and RAM devices, keyboard buffer chip, bit banged serial IO port.

## Detailed Cronology

First "Z-80 computer" prototype. This was not actually called a TEC-1, and was unlike any that are shown in the photos. It was casually refered to as Orac. It has not survived. Built by John Hardy.

First TEC-1 prototype. No silk screen. Incorrect track work. It was scrapped and is presumed lost, possibly sold as part of a grab-bag. Built by Ken Stone. Last seen by Craig Hart in the scrap pile at TE, late 1980's.

Second TEC-1 prototype. Bare fibreglass. No silk screen. Cut-out on top left corner. First to work without corrections to the PCB track work. Built by Ken Stone. This unit was mounted in a small rack case and displayed a pseudo error message to demonstrate one of the possibilities of computerised portable trafic lights. The board was notched to clear the power transformer. The keypad was paralleld by a touch keyboard on the front of the case, likewise the LED display. The ROM is labeled "DYCO"

TEC-1 Batch 1. 1983. Red text white speaker on blue PCB. Issue 10 cover. Designed by Ken Stone and John Hardy. PCB Artwork by Ken Stone. Only 5 of this version exist, distributed to TE staff and John Hardy. The clock capacitor was marked as 220pf (Changed later to 100pf) and the speaker LED was hidden by the speaker and had to be moved.
TEC-1 Batch ?. White text blue speaker on green PCB. Issue 11 cover.
TEC-1 Batch ?. White text black speaker on green PCB.
TEC-1 Batch ?. Blue text and white speaker on green PCB.
TEC-1 Batch ?. Yellow text blue speaker on green PCB.

TEC-1A prototype. Bare fibreglass. No silk screen overlay. New disply latch validation design. (There is a single 1A with the regulator mounted above the PCB, but at right angles to its former location, and provision is made for bolding it to the PCB. This board is the prototype 1A made to test the new latches, and has no solder mask or overlays.)

Issue 12 page 13 claims that over 1000 TECs were sold by this point.

TEC-1A Issue 12 page 13 shows a 1A model in a monochrome photo featuring the diagonal stripes across the top left corner and the Retex case and with 7805 mounted under PCB.

TEC-1A Batch ?. 2 x (dark) diagonal stripes, white text on green??? PCB. (B&W photo reference issue 12, p13. single proto???)

TEC-1A Batch ?. White Text Yellow stripes on Blue PCB.

TEC-1B Issue 13 introduces the TEC-1B. Monochrome photo on page 9. It now features the SHIFT key and MON-2. Red with white speaker on green PCB with diagonal stripes. Ken stone and John Hardy names removed.

TEC-1B Batch ?. Red diagonal stripes, white text on green PCB.
TEC-1B Batch ?. Blue diagonal stripes, yellow text on green PCB.
TEC-1B Batch ?. Blue diagonal stripes, white text on green PCB.

TEC-1B Issue 14. April 1986. No PCB mods but the idea of the MON 1/2 switch (mod by cutting a link on the PCB top side and adding a switch) was introduced here.

TEC-1B Rev.1. 1989. PCB design mods by Craig Hart. Released just prior issue 15. Red text white speaker on green PCB. Added labels to the memory and I/O port pins denoting the address range and port number. Returned Ken Stone and John Hardy's names to solder mask.
I believe that a yellow on green 1B PCB exists but I can't locate photos just now.

TEC-1B CAD Prototype designed by Craig Hart. Early 990. Possibly a prototype but not made in production (as I recall -Craig).

TEC-1C 1991 PCB designed by Craig Hart. June 1990. All white on green PCB; no stripe. TEC 1C annotation on solder mask side. Added some mods to incorporate JMON requirements (e.g. 4k7 keyboard mod resistor), MON select switch, Mini PCB speaker. Coverted to Protel Autotrax PCB CAD package. Previous PCBs were all done by hand with traditional tape and stencil on vellum. The 1C may have been the last run produced by TE, as the company was all but out of business by the mid 90's. I believe that only one batch of 1C PCBs was ever produced -Craig. A 1C prototype was assembed to validate the CAD design worked; I did have this unit for a number of years but has been misplaced in various house moves over the years and is most likely destroyed.

TEC-1D 2018 Reproduction board by Ben Grimmett. White on green PCB. TEC 1D annotation on solder mask side. Revision information listed below the keyboard, component side. Made with Colin Mitchell's blessing.

TEC-1E 2020 "MIT-Z" design by Ken Stone. Many new features. Currently at prototype stage. Not 100% TEC-1 compatible. (Ken coments: actually, it is, if you copy an original EPROM to a larger EPROM, but plans were to change the location of the stack)

TEC-1F 2021 by Craig Jones. Many design improvements. 2k and 8k addressing modes. Bit bang serial. Keyboard buffer chip. Allows for differnt types of keyboasrd keyswitches. Attempt to modernize TEC to allow modern PC based software development and modern components, whilst staying true to the TECs origins.
