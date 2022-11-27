# SMTif-patch
An IPS patch that adds more resistance info to the Devil Analyze screen in Shin Megami Tensei If. Though this was the first game in the series to give the player any information at all on demon resistances, this information was a general text description rather than the detailed blow-by-blow readout you may be used to in more modern games. I decided to correct this. Devil Analyze now tells you demons' affinity with every element (physical, gun, exorcism, curse, fire, ice, electric, force, nerve, bind, magic, and tech). Due to space constraints I couldn't display exact values; everything is one of the standard Rs (resist), Nu (null), Dr (drain), Rf (reflect), or Wk (weak) codes.

Demon types that correspond to a "Cannot analyze" message have their resistances replaced with question marks.

Tech resistance has been condensed into one marker for space considerations. It's rare that granular tech resistance matters and it's not like you can tell what type each tech is unless you look up a guide anyway, so I don't think this is a huge loss. I took a few liberties with this; for instance, demons that slightly resist one tech type but not others will be marked as neutral overall towards tech damage. For demons that do have weird resistances (such as being immune to one type but weak to another), I've flagged their tech resistance as "Mx", for "Mixed".

Almighty resistance is still hidden. This is intentional.

Additionally, the patch adds text to the human status screen telling you how to view the equipment and guardian screens. I did this because I didn't know there was a guardian screen until I saw a guide mention it; thanks, Atlus.

## Installation
To use, apply the IPS patch to a Shin Megami Tensei if... ROM. (For legal reasons, ROMs cannot be distributed, so please do not ask for one.) This is based on the Aeon Genesis fan translation patch, so apply that first.

Patch with Lunar IPS: https://www.romhacking.net/utilities/240/

## Example Images


## Known Issues
I am missing data for type codes 09, 0C, 20, 2E, 30, and 32. Demons with these types will only print their type code into the first slot and leave the rest blank. 0C and 30 are exclusive to Isora and Black Ooze, respectively, but the SMT wiki doesn't have resistance information for them, so I'm in the dark unless I manually test them. The other four I cannot find anywhere even after scouring the entire demon database in the ROM.