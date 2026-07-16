# z440-PSU-pinout
Pinout and tipps for those who wanna use standard ATX with z440 workstation. 

HP uses proprietary power connectors, 18pin + 12pin. Those are not compatible with ATX out of the box. Moreover, most of the power supplies use only black cables, what leaves no clue about the pinout.

There are ATX to z440 adapters available on the market. But if you wanna have a cheaper DIY solution, you can.

1) The 18pin connector is geometrically just a shorter version of the ATX 24pin connector, so you can cut the ATX connector to match HP. In addition, you need to repin every wire (see attachmnent). Search youtube for a DIY ATX pin extractor.
2) The 12pin connector is a 12V power connector and you can prepare it in a few ways, but the best is probably to use 8pin EPS connector + 4pin cpu connector and just plug them next to each other. No repin required. Alternatively, if you have a spare 24/24pin ATX connector, you can do the same as for the 18pin connector.
3) HP uses more 12V lines. Missing lines you can get from spare PCIe connectors, or make Y splits, which is the method used in the produced adapters. Of course, Y splits reduce the amount of power you can safely draw before you encounter system instability, because you effectively use fewer lines than HP assumed. 
