# Sansui-AU-717-Rebuild
Consolidated documentation of a Sansui AU-717 integrated amplifier rebuild.  This is a non-code project focused on documentation, methods, tools, and parts needed to revitalize a Sansui AU-717. Documentation generated during my journey to rebuild this classic integrated amplifer with the help of the Audiokarma.org community and broader web resources.

# Repository Index
File | Description
---- | -----------
README.md | this file; contains references and general overview guide
audio.sansui.au-717.parts_list.ods | bill of materials and tracking of parts replaced, see [BOM](#bill-of-materials) below for more context
parts_replaced_readme.md | explains [audio.sansui.au-717.parts_list.ods](audio.sansui.au-717.parts_list.ods) worksheets
parts.md | general information about electrical parts (non-exhaustive) focused on audio quality
howto_reference_guide_notes.md | many reference notes mostly from audio karma threads, see [References](#references) below for descriptions
howto_general.md | <li>covers soldering, desoldering tips and issues.</li><li>Covers transistor replacement matching methods</li>
license.txt | legal stuff, rules for sharing

# Sansui AU-717 Rebuild General Information

## Preparation for Success
* Read and understand what you are doing before you start
* Document the process
  * Take pictures
    * of board number and multiple angles before disassembly
    * during disassembly with labels to help you understand orientation later
  * draw diagrams of screw locations and parts disassembled
  * use tape loops on paper to capture screws in an orientation similar to where they were originally, with diagrams or notes on the paper
  * attached labels to removed parts
  * mark wire colors on diagrams, and label wires if possible to get them confused with other connections
* Always use a dim bulb tester after each repair when applying power the first time
  * restricts current for short to ground
  * bulb wired in series to unit power
  * if bulb shines bright you have a short, if it dims over time you don't
  * Note: this may not work with non-incandescent (read non-resistive load) bulbs
  * References: 
    * [overview](https://antiqueradio.org/dimbulb.htm)
    * [instructable](https://www.instructables.com/Vintage-Dim-Bulb-Tester/)
    * [bulb wattage](https://audiokarma.org/forums/index.php?threads/dim-bulb-tester-what-watt-bulb.330103/)

## What you need for the job

### Replacement Parts and a Plan
* [See below for plan](#sansui-au-717-rebuild-plans-and-online-guides)
* [Parts list used](parts_replaced_readme.md)
* source of the parts list outlined in [Bill of Materials](#bill-of-materials) section below

### Tools
* wrap all but the tip of a small standard screwdriver with electrical tape to use to adjust amp offset and bias
* [dim build tester](https://antiqueradio.org/dimbulb.htm) to test for shorts after work
* phillips screwdrivers of different sizes and tips
* 12mm deep well socket for volume knob jam nut
* plastic body panel removal tools (optional) to pull stubborn knobs after set screw removal
* cut credit card = PCB safe scrapper
* gloves
* fan - use to extract/disperse fumes
* soldering iron
* solder sucker and/or copper mesh
* brass ball to clean solder tip
* good lighting and jewelers headset to review solder joints

### Chemicals/Materials
* water
* isopropyl alcohol
* non-acetone nail polish remover = ethyl acetate for glue removal
* thermal paste
* cotton balls
* small fuel line to replace tubing on leads of vibration susceptible parts
* heat shrink
* aluminum foil and cardboard scraps to protect heat sensitive parts
* solder
* solder flux

# Sansui AU-717 Rebuild Plans and Online Guides

## References
Many of the references are summarized in howto_reference_guide_notes.md

1. [LeeStereo Build Thread](https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-1)
   * Leestereo (his name is Ben) is _the reference build_
   * AudioKarma member build thread referenced by SuperNoob and many others
   * Ref: LeeStereo
3. SuperNoob Build Thread
   * AudioKarma member build thread
   * Thread includes replacement part numbers used and reference photographs
   * There are a number of typo errors, verify the parts 
   * Ref [SuperNoobA](https://audiokarma.org/forums/index.php?threads/project-sansui-au-717-restore-rebuild.893233/)
     * see summary: audio.sansui.amp_rebuild.au717.restore_via_audiokarma_supernoob-summary.docx
   * Ref [SuperNoobB](https://www.audiokarma.org/forums/index.php?threads/project-sansui-au-717-bks.896463/)
4. [MIJ_Pioneer](https://audiokarma.org/forums/index.php?threads/au-717-recap.903438/)
   * AudioKarma member build thread References LeeStereo and SuperNoob
   * Thread includes replacement part numbers used and reference photographs
   * Ref MIJ_Pioneer
6. [marantzhallo-fi Build Page](https://marantzhallo-fi.blogspot.com/2017/04/chris-justins-sansui-au-717-restoration.html)
   * Single webpage restoration overview with high-quality photos
   * Includes high-level descriptive operation and parts list content
   * Includes post rebuild noise performance measurements
   * Ref: marantzhallo-fi
7. Hallman Labs AU-517 Restoration
   * AU-517 focused, but the AU-517 and AU-717 are very similar
   * [newer content? Re-Cap Its Alive](https://hallmanlabs.com/2019/03/10/sansui-au-517-complete-re-cap-restoration-its-alive/)
   * [related or sub-thread: Complete Restoration](https://hallmanlabs.com/sansui-au-517-complete-restoration/)
8. AnalogueBen in AudioKarma: 883773 recommended parts list

## Manuals and Specifications References
* [http://www.hifiengine.com](http://www.hifiengine.com) is the best source for user and service manuals.
* [https://www.vintageshifi.com/repertoire-pdf/m-Sansui.php](https://www.vintageshifi.com/repertoire-pdf/m-Sansui.php) has transistor replacement table and [AU-717 Service Manual at VintageHifi](https://www.vintageshifi.com/repertoire-pdf/pdf/telecharge.php?pdf=Sansui-AU-517-AU-717-Service-Manual.pdf)

## Rebuild Plan Parts Suggestions

### Bill of Materials
I merged the bill of materials (BOM) lists listed here. The BOM I used and tracking of the parts I replaced is in file [audio.sansui.au-717.parts_list.ods](audio.sansui.au-717.parts_list.ods) with [parts_replaced_readme.md](parts_replaced_readme.md) serving as a descriptive readme of each worksheet.

History: Many lists and rebuild work are built off LeeStereo post. The BOMs listed below come from the references above.
* Ref SuperNoobA parts list 
* Ref LeeStereo thread Different BOM lists:
  * post 174 (jwjarch)
  * post 249 (toneriderMUC@Mouser named au717)
  * post 262 (daviddi922@Mouser named Sansui Au717)
  * post 382 newer build
* Parts: Run Tabula on audio.sansui.au-517_717_service_manual_en_imp_scan.pdf to pull out values from tables
  * this was a messy export
  * the data was then partially cleaned
  * honestly you get a better list by manually reviewing the schematic

### Transistor Swap Threads
I did not do significant transistor mods using different case format or change the power transistors. There is a lot of concern in the community about unobtanium parts if yours are bad, this content provided if you intend to investigate modern updates and avoid the perilious second-hand market full of fake parts. Some links refer to *trustworthy* sources but these references are often old or the sources are out of supply by now. *If* I had needed to do this I would have likely done the TO-3P format mod. Caveat emptor reigns and I am not responsible for damage you do if you follow these threads.

* [Sansui transistor substitution collection](https://audiokarma.org/forums/index.php?threads/once-more-sansui-transistor-substitutions.583009/)
* [Sansui AU-717 transistors](https://audiokarma.org/forums/index.php?threads/sansui-au-717-transistors.261681/)
* Both links above point to using lower MHz bandwidth TO-3 case chips
  * 2sa747 = Very nearly unobtanium - beware of counterfeits - suggested replacement MJ21193 = Digikey
  * 2sc1116 = Very nearly unobtanium - beware of counterfeits - suggested replacement MJ21194 = Digikey
  * [Others suggest this is a bad idea](https://audiokarma.org/forums/index.php?threads/replacement-for-2sc1116a-replacement-of-mj15011.904877/#post-13718073) because the feedback design expects higher bandwidth. Replacements 4MHz vs 10 and 15 MHz bandwidth. 
* Rather change to newer TO-3P format
  * [How to swap transistor type here](https://audiokarma.org/forums/index.php?threads/ba-f1-on-the-bench-first-look-here-we-go.880419/)
  * [updated transistor list](https://audiokarma.org/forums/index.php?threads/once-more-sansui-transistor-substitutions.583009/page-6#post-13449355)
    * Points to 2SA1695 and 2SC4468 which seem plausable replacements, digikey even if form factor is dumb
* 2SC945 (Q, P) Transistor is center collector
  * the KSC945CYTA is also center collector by on semiconductor
  * [per](https://audiokarma.org/forums/index.php?threads/sansui-au-717-transistors.261681/)
* [transistor equivalents](https://www.vintageshifi.com/sansui-au-717.php); saved as audio.sansui.amp_rebuild.au717.specifications_and_transistor_equivalents.odt

### Other Modifications
I did not do these:
* Binding Post Modification:
  * [Version 1 Requires Effort](https://www.stereo.net.au/forums/topic/48612-binding-post-modification-for-a-sansui-au717-amplifier/)
  * [Version 2 Easy-Button Parts Order](https://speaker-terminal.com/en/produkt/sansui-au-717-speaker-terminal/) as referenced by [Alex22](https://audiokarma.org/forums/index.php?threads/sansui-au-517-needs-recap.974218/page-2#post-15133376) for his [AU-517](https://speaker-terminal.com/en/produkt/sansui-au-517-speaker-terminal/)

Input Signal Level Modification For Vintage Sensitivity (due to high modern signal level):
* technically the -20 dB muting switch handles this and it is unclear if it would help the AU-717 but I investigated while trying to figure out why signal was fading in and out
* Per [JoseHH](https://audiokarma.org/forums/index.php?threads/1979-sansui-au-717-tu-717.967151/page-3#post-15048735) and [Multimode](https://audiokarma.org/forums/index.php?threads/cambridge-cxn-into-sansui-au-919.765205/#post-10442568) Audiokarma users
* -20 dB attentuators to lower modern 2VRMS signals to better match Sansui 150 mV input sensitivity and max signal level
* note looking at specs for post-CD era receivers shows around 200 mV input sensitivity
* when sensititivity is a problem symptoms:
  * "Although potentiometers work reasonably well over most of their operating range, they are notoriously problematic at extreme settings. The most obvious problem is channel imbalance - one channel will fade out (or fade in) quicker than the other, causing the stereo image to shift to one side - but on a more subtle level, the music may sound veiled and indistinct with the volume control turned down to the point where it is nearly off. Some people have tried to cure the problem by fitting a more expensive volume control only to find that it doesn't do much good." per [Rothwell Audio](http://www.rothwellaudioproducts.co.uk/html/attenuators.html)
* potential vendors (options):
  * UK: [Rothwell Audio Products](http://www.rothwellaudioproducts.co.uk/html/attenuators.html) page includes an overview explanation
  * [Russ Andrews](http://www.russandrews.com/what-is-attenuation/)
  * [Volume control](https://audiokarma.org/forums/index.php?threads/au-317-taming-the-volume.722517/#post-14494510)

## How To
Consolidation of specific how tos representative in whole (or part) of what I did, based on [reference content ](howto_reference_guide_notes.md) or other specific references as mentioned below.

* If you prefer videos over reading: Polish videos by Hifi Surgery cover major parts of the process
  * https://audiokarma.org/forums/index.php?threads/sansui-au-717-restoration.970989/page-2#post-15053101 
  * Part 1: https://www.youtube.com/watch?v=ZOxRPpDvTMA
  * Part 2: https://www.youtube.com/watch?v=5TagB6hAWHk 
* Pay attention to vibration and heat sensitive part instructions
  * polystyrene film capacitors are solvent and heat sensitive (solder with a heat sink attached to the leads).
  * I used 2 mm heatshrink on the leads with aluminum foil wrap to distribute the heat during heat gun application, then slide 3 mm fuel hose over that so the capacitor has longer leads for soldering and is supported to avoid vibration. Also necessary because could only find axial part to replace the original

### Cleaning 

#### General Cleaning
* Super dirty cleaning advice: https://audiokarma.org/forums/index.php?threads/new-member-really-dirty-au-717-need-advice.514913/
* Rebuild thread with photos: https://audiokarma.org/forums/index.php?threads/sansui-au-717-restoration-and-upgrade.875646/
  * remove, clean, and give new thermal compound for transistors

#### Glue Removal
* https://audiokarma.org/forums/index.php?threads/my-solution-for-easy-au-717-sansui-glue-removal.508267/#post-6602302
* solvent: Can use acetone, isopropyl alcohol, ethyl acetate
  * concerns about acetone being agressive, see [LeeStereo 351](https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-18#post-13740628), it affects some plastics
  * I used ethyl acetate - less aggressive solvent
* spread cotton balls out on/around glue (tucked in good around components)
* Saturate with 1-2 cap fulls of solvent
* Wait 15-20 minutes.
* Scrape off
  * used an old (or postal trash) credit card as a scraper (cut down to fit smaller spaces)
  * flat exacto knife blade but metal can scar the board

#### Thermal Grease
* Clean old dried thermal grease with alcohol and a soft cloth
* Note I used a old credit card or razor blade to spread new compound
* Should replace Mica insulators when you do this for power transistors. Some have used [Keystone 4636 TO3 Mica Insulator for transistors	Mouser Part 534-4636](https://www.mouser.ca/ProductDetail/Keystone-Electronics/4636?qs=%2Fha2pyFadujp6VwXBQ0HmAA8J2wSb1PbusiTW%2FV%2Fbu7g2AKaV%252BP6Hw==)

#### Control (Switch/Potentiometer) cleaning threads:
* What chemical?
  * I ended up just using DeOxit-F5 on potentiometers and switches (not yet)
  * **do not use Windex or WD40**
  * DeOxit-D5 vs DeOxit-F5
    * the core difference is F5 contains lubrication
    * when to use [public recommendation](https://audiokarma.org/forums/index.php?threads/speakers-cutting-in-and-out.967652/#post-15028481)
       * D5 for switches (metal / metal contacts)
       * F5 for potentiometers
    * Caig, DeOxit maker says F5 okay for some switches
  * DeOxit-D5
    * [ref](https://audiokarma.org/forums/index.php?threads/deoxit-d5.947097/#post-14504688)
    * skywatcher: But it is mainly for switches and not pots. I clean pots with D5, then use FaderLube (F5). He prefers CRC QD or MG Chemicals no-residue cleaners.  
* [Idiots Guide to Using DeOxit](https://audiokarma.org/forums/index.php?threads/the-idiots-guide-to-using-deoxit-revisited.207005/)
* Cleaning video: https://youtu.be/_3gSIeEzOZM 
* https://audiokarma.org/forums/index.php?threads/the-idiots-guide-to-using-deoxit-revisited.207005/
  * great thread with lots of info on disassembly and DeOxit use
  * DeOxit Red stuff clean
  * DeOxit ProLube or DeOxit GOLD, to lubricate and protect the switches. 
* clean/lubricate volume control:
  * [disassembly vs drilling and the question of what is really causing signal drop-out](https://audiokarma.org/forums/index.php?threads/au-717-volume-pot-accessing-cleaning.294270/)
    * try wiggling pre-amp connection switch
  * [no disassembly shaft soak method](https://audiokarma.org/forums/index.php?threads/sansui-au-717-517-919-sticking-volume-pot.754547/#post-11027014) [picture](https://audiokarma.org/forums/index.php?attachments/stem-lube-jpg.1045954/)
  * [partial disassembly method](https://audiokarma.org/forums/index.php?threads/sansui-au-717-volume-control-pot-maitenence-help-please.43185/#post-594781)
  * [complete disassembly repair method (avoid unless necessary)](https://audiokarma.org/forums/index.php?threads/au-517-volume-pot-repair.689529/)
  * [drill method (not recommended)](http://www.cdkands.com/AU717-7.html)
    * the drill method is controversial, others swear it is less likely to cause issues than partial disassembly
  * see [volume potentiometer](#volume-potentiometer) below
* Search Skywatcher #282 in [howto_reference_guide_notes.md](howto_reference_guide_notes.md) for suggestion on more extreme disassembly and cleaning using brush and water of parts

### Disassembly and Specific Actions

Preference is to work on the boards in situ whenever possible.

#### F-2663
* disassembly: F-2663: Power supply servicing tip per SuperNoob Reference
  1. desolder 6 power supply leads from the bottom of board (edit: had to remove many more wires than this to make everything accessible for cleaning!) 
  2. remove the mount brackets
  3. the board can be pulled forward for rebuilding
* even when disconnected so the board is free the relay will still catch on the chassis, you must careful rotate to remove
* remove the corrosive glue from this board

#### F-2721/F-2722
* mark wire color positions on schematic
* pull plastic wire tubes off contacts and disconnect multi-pin plastic connector
* remove 4 chassis mounting screws
* you can disconnect the PCB from the heatsink but you do not have to remove the wired transistor connection during PCB work if you are careful
* remove the corrosive glue from these boards
* manually test conductance of power transistor mica insulator pad [ref](https://audiokarma.org/forums/index.php?threads/sansui-au-517-needs-recap.974218/page-7#post-15162067)
  * Once the mica is installed under the transistor use a multimeter to test for a short from the transistor casing to the heatsink.  * 

#### F-2723
* https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-13#post-13122658
  * posts 257-260
  * board F-2723 (EQ) in my restoration and have trouble loosening it.
  * To work "in situ" on lower solder spots that are shielded by the chassis must lossen but not remove the board.
  * How do I disengange and remove the two switch shafts?
    * mark the plastic piece in line with the metal gear hole to remember the orientation
    * Remove the c-clips on each shaft (near the front of the unit) and then the shafts can be extended forward and out of the way.
      * C-clip = tiny metal clips on the backside of the front panel. When you remove them, you can pull out the shafts with knobs and everything else in its place. The knobs do not need to be removed
      * push down on both sides of the c-clip with 2 small screwdrivers to remove it
    * pull the knob out to slide the extension off the switch actuator
  * release the connectors (x3) on board, 1 off board at front
  * be careful of the stiff ribbon wire sets while you work on the board

#### F-2720
* no disassembly required, all work done in-situ

#### F-2670
* plastic push-in fasteners holding the 2670 board (pre-main switch PCB) to the rear panel.
* Advice on non-destructively removing the fastener? Or if it has to be destroyed, what do you use to fasten the board back to the rear panel? 
  * version 1: Remove the plastic push-in fasteners
    * https://www.audiokarma.org/forums/index.php?threads/au-717-recap.903438/page-4#post-14698794
    * you melt the glue on the back of the fastener with a little acetone on a cotton ball, you can press on the back of the pin with a small screwdriver to push it out without destroying anything. 
  * https://audiokarma.org/forums/index.php?threads/sansui-au-717-f2663-psu-protector-board-guidance.944593/#post-14503304
    * They're called plastic snap rivets, you can buy them, but your originals were re-usable if you had been more careful.
    * The original assemblers put varnish (or similar) on the back of the rivets which made them difficult i.e. not obvious how to remove them, all you had to do was push out the rivet shaft from the back, I found that putting IPA or even flux cleaner on the rivets loosened the varnish. Here is a link,
https://uk.farnell.com/tr-fastening...342242&searchref=searchlookahead&exaMfpn=true
    * You may know that Farnell are affiliated with Newark - https://www.newark.com/
  * [version 2](https://www.audiokarma.org/forums/index.php?threads/au-717-recap.903438/page-4#post-14698871): Don't remove the plastic push-in fasteners
    * With F-2721 and F-2722 driver boards removed
    * desolder the board from the RCA jacks. Then when done with the board, simply resolder RCA jacks
    * **Addendum: DO NOT DO THIS** yes you can but you are likely to break the RCA jack ground pins trying to unfold them
      * 3 of 4 of mine broke
      * Fixed with copper band tying the grounds together and soldering with amp on its back panel to pull solder down onto broken tabs to *retain* a connection at the PCB pad. Also added copper ties between each pin pad on top.

#### Controls and Panels
* note the control position at time of removal, most have clear detents but this helps you understand where to start when puttingn the knob back on
* put the knobs and switch covers on a piece of paper with each clearly marked to avoid confusion

##### knob removal tricks
1. 1.5 mm allen wrench to release knob
   * takes about a full turn
   * if knob does not remove it is safer to loosen more to make sure the set screw is not captured
2. pull out on knob along shaft to remove the knob
3. for stubborn knobs use either of the following to generate leverage under the knob while pulling:
   * a plastic body panel removal tool (what I did)
   * an old credit card with a notch cut in it (note not tested, may not be strong enough)
   * a t-shirt wrapped under and around the knob then twisted to give a leash to pull (I think I read this in a guitar service manel once)

##### volume potentiometer

1. remove the inner partial cover plate (4 screws)
2. use a 12 mm deep-well socket to remove the jam nut on the inner face plate panel
3. use a small phillips screwdriver to loosen the stack see [directions](https://audiokarma.org/forums/index.php?threads/sansui-au-717-volume-control-pot-maitenence-help-please.43185/#post-594781)
   * monitor the screw placement in the back nut to avoid complete separation
   * put tape over the back nut to hold it in place

##### source and copy selector shafts
* use c retention clips

##### switch covers
* pull these straight off the metal switch blade
