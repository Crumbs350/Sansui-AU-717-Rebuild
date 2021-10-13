
# Build Guide Notes

Notes extracted from very long threads. Below References there are part investigation notes

## Ref LeeStereo:
* Replace all power supply electrolytic capacitors with low ESR types (increasing capacity where appropriate and physically possible).
* Replace all of the signal path electrolytic capacitors with either "audio grade"/bi-polar electrolytic types or film types (whenever possible). 
* Upgrade original polyester film capacitors to polypropylene film types (as appropriate ie in signal path).
* Replace signal path ceramic capacitors with film or C0G types.
* Replace fuse resistors with metal film types; Fusible resistors post 171
* Replace VD1212 (dual diodes) with pair of 1N4148 diodes (in series).
* Replace any components damaged by the infamous corrosive board glue. 
* Capacitor selection general
  * IMO, the type of capacitor, i.e., polar, bi-polar, film, is more relevant than the actual brand/series (provided that the capacitors are from reputable manufacturers, e.g., Nichicon, Panasonic, UCC, CDE, Kemet, WIMA...etc… post #197
  * all film-type capacitors are bi-polar/non-polar by design choose 5% or less
  * For low ESR types, I typically use capacitors from (20150422):
    * Panasonic (FM and FR series), Nichicon (PW series) and United Chemi-con (KZE, KYA, and KYB series)
  * For signal path duties, I typically use (20150422):
    * larger electrolytic capacitors: Nichicon ES bi-polar types to replace 
    * for smaller sizes (e.g., <4.7µF) I will use Panasonic or WIMA stacked film types
    * For C0G capacitors, I will typically use AVX brand, rated at 100V. All of the components used in this thread are available from Mouser.
  * voltage rating: As a general rule, the signal path capacitors will be subjected to lower voltages than the power supply capacitors. The polyester stacked film capacitors are typically available rated at 50V or 63V. For the polypropylene capacitors, use the smallest capacitor that will fit the available board space (which is often the lowest voltage rating). For C0G capacitors you can use 50V or 100V rated ones.
  * 2X-3X increase is acceptable for most small capacity capacitors whose purpose is solely DC filtering
  * Page 52 is the picture of all replaced capacitors
* Match power supply resistors post 369
* The capacitors C05 and C06, on the RIAA equalization.
  * Should be no issues replacing polarized capacitors in the signal path with modern construction bi-polar types (i.e., dual anode foil), or film types.
  * Some older bi-polar capacitors actually consisted of two polarized capacitors in series within the same capsule and with this type it was not recommended that they be installed in positions with significant DC voltage. Note that in this particular case, there is very little, if any, DC voltage on C05 and C06. 
* F-2663 board contains 2 independent regulated 35V power supplies (one for each channel).
  * Increase electrolytic capacitor size significantly
  * Match lead spacing: 5mm lead spacing for the 10mm and 12.5mm diameter capacitors: I chose 10mm capacitors to replace the original 12.5mm capacitors on the power board to provide better air cooling. 
* Identify issues
  * capacitors with "shrunken" sleeves (mostly from the F-2663 regulated power supply board) is indicative of internal over-heating and failure. Even many of the F-2663 capacitors that looked fine were found to be defective, often measuring <10% of the stated capacitance.
* Cleaning
  * Clean switches post 281, post 363 (also post 7 of https://audiokarma.org/forums/index.php?threads/sansui-au-717-no-signal-in-right-channel-pre-stage-and-distortion-on-the-same-channel-in-power-stag.961060/ )
    * post 284: why switches make noise
    * some say don’t clean pots
        * MIJ_Pioneer: Deoxit D5 for metal / metal contacts; Deoxit F5 for potentiometers (safe for carbon)
        * Skywatcher: Pre-Out switch, it rarely gets used so it will be needing a thorough cleaning and DeOxit Gold applied to keep the contacts protected from oxidizing. balance, tone and other unused POTS same happens if not used.
        * Skywatcher #282: ere are a couple of examples of some switches out of a Sansui 9090 using the silver cleaner method. The only *very light* "scrubbing" done was with warm soapy water and a soft bristle toothbrush to remove any remaining cleaning solution and flushed well in very warm water before blow drying. Contacts are silver plated and you do not want to damage it with wire brushing, sanding, or harsh cleaners. Only use a mild cleaning solution specifically for silver. 
        * See also https://audiokarma.org/forums/index.php?threads/speakers-cutting-in-and-out.967652/#post-15028481 about D5 vs F5 points to Idiots guide to DeOxit: https://audiokarma.org/forums/index.php?threads/the-idiots-guide-to-using-deoxit-revisited.207005/ 
    * don’t take apart push-button switches: http://www.cdkands.com/AU717-7.html
    * if volume bad then: http://www.cdkands.com/AU717-7.html
        * You only need to drill access holes in the second and third layers from the front
        * Don't over-shoot the hole when the drill breaks through.
        * 4th and 5th levels can be accessed from the bottom.
  * Cleaning on: http://www.cdkands.com/AU717-6.html
    * Clean old dried thermal grease with alcohol and a soft cloth
    * Transistors were polished with a fine water based polish (designed for use on plastics). 
  * Issue with the glue post 186
  * Says nail polish with acetone removes glue countered in post 351 suggesting isopropyl alcohol
    * counter 352: glue is found on the F-2663, F-2721 and F-2722 boards.
    * acetone may adversely affect some plastics 
    * preference is to use a less aggressive solvent e.g., ethyl acetate (commonly found in non-acetone nail polish remover) for glue removal. 
    * Soaked ceramic insulators in ethyl acetate in a closed pill container, then rinsed with water, soaked on paper towel, blew out with a yoga ball pump and let dry
    * scraped with cut down throw away credit card (comes in mail), great non-sharp scraper
* Disassembly and Repair General
  * My preference is to work on the boards in situ whenever possible; the only boards in the AU-717 which were removed during the restoration/upgrade were the driver boards and the pre-main switch board (the plastic fasteners are coated with a sealant that can be dissolved with an ethyl acetate solution e.g., non-acetone nail polish remover). 
  * Disassembly post 168 and 207 (http://www.cdkands.com/AU717-1.html), 259 shafts
  * Several places mention 1.5 mm allen wrench to remove knobs
* Reassembly
  * polystyrene film capacitors are solvent and heat sensitive (solder with a heat sink attached to the leads). 
  * I used 2 mm heatshrink on the leads with aluminum foil wrap to distribute the heat during heat gun application, then slide 3 mm fuel hose over that so the capacitor has longer leads for soldering and is supported to avoid vibration. Also necessary because could only find axial part to replace with
* Testing and Review
  * Measurements in post 162
  * Testing in post 267
  * Page 54 sound impressions
* Service Manual Parts lists often wrong: Post 235. “sometimes they are wrong, and sometimes very wrong. Just look at the schematic - which generally is very close to correct”
* #379: stock configuration, the film capacitor at C20 is a by-pass for the electrolytic capacitor at C22. Since the original posting, subsequent AU-717 restorations have incorporated upgrades to the stock 0.047µF polyester film by-passes to 0.1µF WIMA polypropylene types, as detailed in post no. 210  Here is a picture of the installed WIMA MKP by-passes on F-2720.
* F-2720 C31, C32 are removed because they are no longer needed; see https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-17#post-13473487 for why this is done.

## AudioKarma Recommendations per audio.sansui.amp_rebuild.txt (sorry didn't save the source for this): 

* All Electrolytic Caps (including the four main filter caps) 
  were replaced 
* all VD1212 were replaced with 1N4148 In series 
* all 'black flag' caps were replaced (does he mean stryol??) 
* All Inter-Stage coupling and filter capacitors replaced 
  with HQ [high quality?] equivalents. 
* All controls were thoroughly cleaned and noise free. 
* Biased Current and DC output voltage were adjusted to within 
  specification. 

## Ref marantzhallo-fi:
* electrolytic were replaced with high temp (105C) long life FC Panasonic and Nichicon PW capacitors with an increase in operating voltages.
* The Bipolars and .47 coupled electrolytic were replaced with Nichicon VP and high grade WIMA MKP film capacitors.
* All of the diode bridge 10D1 and 2473 were replaced with Fairchild 4148 and Ultra-Fast UF400# type diodes, all VD1212 type epoxy diodes were replaced with series Fairchild 4148 diodes.
* TO-220 voltage regulators which tend to show signs of excessive heat are replaced with heavy duty OnSemi MJE TO-220 devices and thermal compound applied.
* The relay was replaced with a heavy duty low noise type Omron MY4 relay.
* Due to excessive glue damage about 15 carbon film resistors were replaced with KOA carbon film resistors.
* The solder joints due to excessive heat were reflowed as well.
* large vertical axial electrolytic capacitors were affixed to the PCB using a glue
  * glue used on large capacitor has become caustic and oxidized
  * oxidized material also become conductive
  * capacitors resulting in what can be expected as systemic random failures in Sansui’s
* Fusible resistor which exhibit two odd characteristics
  * the insulation of the resistive body lends to premature drift in high heat environments 
  * the failure mode of the substrate tends to fuse rather than open the circuit which leads to excise current consumption of the stage and cascade failures throughout the driver stage etc.
* By board is below
  * High Temp(105C) low ESR Cornell type 15,000MFD/100V capacitors were installed with high grade MKP Solen 2.2MFD film capacitors to bypass.
  * F-2721 and F-2722 boards
    * electrolytics: high temp (105C) Nichicon PW’s and audio grade KT with an increase in operating voltages
    * MFD was replaced with a high grade WIMA polypropylene film capacitor.
    * The 22V zener’s were replaced with a Fairchild axial diode and the 150 ohm fusible resistors were replaced with a KOA carbon film 1/2W.
    * Replacing transistors: tier differential NPN stage and problematic 2SA750 transistors were replaced with a low noise TO-92 Fairchild transistors Beta matched within 1%. The complimentary pre-drivers were replaced with low noise robust TO-126 Fairchild transistors
        * the 2SA750 is listed as bad due to shot-noise
        * pre-drivers are TR05 and TR07 per manual 2C1P4. Ie 2SA899 and 2SC1904
  * F-2720 board
    * electrolytic capacitors replaced with low impedance long life Nichicon PW and audio grade Nichicon KT capacitors with an increase in operating voltages.
    * .33 and .47 films were replaced with high grade WIMA polypropylene and Solen MKP polypropylene film capacitors.
    * The 82ohm fusible resistors were replaced with KOA carbon film 1/2W resistors along with the VD1212 epoxy diodes to Fairchild 4148 series axial diodes. All of the low signal BJT were replaced with Fairchild TO-92 low noise transistors with the PNP gain stage to a 1% matched BETA.
  * RIAA EQ F-2723
    * The input coupling films were replaced with high grade Solen MKP polypropylene film capacitors.
    * Remaining electrolytics were replaced with a low impedance Nichicon PW and audio grade KT with an increase in operating voltages.
    * 82 ohm fusible were replaced with a KOA carbon film 1/2W resistors along with the VD1212 epoxy diodes to Fairchild 4148 series axial diodes
    * The differential gain stage and problematic 2SA726 (7## series) were all replaced with a low noise TO-92 Fairchild transistors with the differentials matched to a 1% BETA. 


**Diode replacement**: audio.sansui.amp_rebuild.au717.diode_replacement.odt
* Not recommended to replace power supply diodes except zener and VD1212 diodes
* ZD01/02 replace with BZX79-B13, ZD601 1N5232B and ZD602 1N5234C
* For the VD1212 diodes use two 1N4148's in series for each.



# Part replacement Investigations
##  general notes
Power caps 12000 uF 63 V electrolytic capacitor (original part) but others indicate  15,000 uF
* 40.2 mm x roughly 3.5 inches tall
* Mouser Nichicon 15000 uF 63 V 20% $20.85 x 4: LKG1J153MKNF	 KN means 35|40 mm
* Mouser Nichicon 22000 uF 63 V 20% $34.20 x 4: LKG1J223MKZ 	 KZ means 50-76 mm
  * 80V $36.20 x 4: LKG1K223MKZF
* The parts ending in S are better, F is lowest, other middle grade: [datasheet](https://www.mouser.com/datasheet/2/293/e-lkg-875808.pdf)
  * all S are KZ so too big in diameter. 
  * LKG1J153MKN  - type II middle grade, 15000 uF, 40mm x100mm, 63 V	$26.00
  * LKG1K153MKNF – type 1, 15000uF, 40x100 mm, 80 V, $26.51
  * LKG1J223MKNF – type 1, 22000 uF, 40 x 100 mm, 63 V, must buy in 100, $24.91
* warning: increase capacitance increases intake current and could create sonic noise/transformer damage
* Note that Outlaw Audio 2200 uses 13,600μF capacitance for HP Rails; 6,600μF for LP Rail
* Others using Kemet ALT22A153DE063 because long-life, shorter, also cheaper, $15.68 each

Lights get from Parts-Express.com for TU-717: [part 070-121 LED 8 volt fuse](https://www.parts-express.com/led-fuse-lamp-for-marantz-sansui-kenwood-yamaha-sony-warm-white-8-volt-5-pack--070-121) 


[Rebuild Kit by hifiaudio](https://www.ebay.com/i/153892666802?chn=ps&norover=1&mkevt=1&mkrid=711-213727-13078-0&mkcid=2&itemid=153892666802&targetid=4580153133025496&device=c&mktype=&googleloc=&poi=&campaignid=403206344&mkgroupid=1224856168411792&rlsatarget=pla-4580153133025496&abcId=9300372&merchantid=51291&msclkid=c598181b3983154a6ec1477b19f73f66) on Ebay:
Power / Filter stage caps are those large silver cans mounted on top of the chassis and sometimes underneath.  This restoration pack will make a huge difference in the sound quality. All the parts are of high quality Japanese Nichicon / Panasonic / IC  / United Chemi capacitors. 

Included in this kit:
1. Power/Filter stage capacitors (Nichicon / Panasonic / United Chemi)  electrolytic capacitors. 
2. Detailed instruction with colorful images, schematics, manuals (all of these are in electronic form, I consider these much better than printed version due to zoom availability).
3. Schematics
4. Complete audio path upgrade with high quality US made (IC) or Panasonic audio grade film capacitors.
5. Parts for compete recap of all the electrolytic capacitors. 
6.  Complete recap of all PCBs.
7. Some other parts if your unit requires it.   
8. fuse/s 
9. Instructions on how to clean the chassis.
10. Instructions on how to clean the faceplate
11. Instructions on how to polish and clean the knobs.
12. Support/help to a reasonable extend in case you need it.  (This is what makes us different from other sellers.)


