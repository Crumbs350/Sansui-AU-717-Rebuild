# Sansui-AU-717-Rebuild
Consolidated documentation of Sansui AU-717 Rebuild.  This is a non-code project focused on documentation, methods, tools, and parts needed to revitalize a Sansui AU-717. Documentation generated during my journey to rebuild this classic integrated amplifer with the help of the Audiokarma.org community and broader web resources.

Repository Index
===========================
Parts.md = general information about electrical parts



Sansui AU-717 Rebuild Plans
===========================

How To 

How To: Desolder: [http://www.bestsoldering.com/learn-how-to-desolder-beginners-guide/](http://www.bestsoldering.com/learn-how-to-desolder-beginners-guide/) 

* heat and pull vs heat and push with bull-nose plier then pull/leverage 
  as heat 

* heat and push lead gently with bull-nose plier, then can pull 
  more easily 



How To: Solder: [http://www.bestsoldering.com/learn-how-to-solder-beginners-guide/](http://www.bestsoldering.com/learn-how-to-solder-beginners-guide/) 

* use cut offs leads to help clear stubborn holes. Hold with pliers 
  using very short lead to push 

* release solder then run tip of soldering iron up lead as release 
  to draw heat away a little slower 

* use alligator clips to hold other lead in place to pull part 
  tight against board 

* put small amount of flux on the lead using a toothpick or small 
  brush 



How To: transistor beta match: [http://www.bestsoldering.com/transistor-matching/](http://www.bestsoldering.com/transistor-matching/) 

Transistor comparison: [http://users.tpg.com.au/gerskine/greg/driver%20transistors.htm](http://users.tpg.com.au/gerskine/greg/driver%20transistors.htm) 

Fix damaged trace cover: [https://forum.allaboutcircuits.com/threads/how-to-insulate-a-circuit-board.11371/](https://forum.allaboutcircuits.com/threads/how-to-insulate-a-circuit-board.11371/) 
use epoxy, RTX, etc but must dry first completely 

Transistor Swap Package: [https://audiokarma.org/forums/index.php?threads/to-66-to-to-220-etc-ways-to-replace.476734/](https://audiokarma.org/forums/index.php?threads/to-66-to-to-220-etc-ways-to-replace.476734/) 

Process
-------

Take pictures of board number and multiple angles before disassembly 

Capacitors 

Per [link](https://electronics.stackexchange.com/questions/69919/ceramic-vs-film-capacitor-which-one-is-preferred-in-audio-circuits). 

Film Capacitor 

* typically denotes polyester or polymer film as the dielectric 

* metallized film capacitors are the same thing: metallic coating 
  being applied to an extremely thin polymer film, to create 
  the conducting electrodes of the capacitor. 


Rebuild Plan Parts Suggestions 
-------

parts list [https://audiokarma.org/forums/index.php?threads/project-sansui-au-717-restore-rebuild.893233/](https://audiokarma.org/forums/index.php?threads/project-sansui-au-717-restore-rebuild.893233/) 
references supernoob build 

transistor swap thread: 

* old links: 

* Both point to using lower MHz bandwidth TO-3 case chips 

* Suggested this is a bad idea: [https://audiokarma.org/forums/index.php?threads/replacement-for-2sc1116a-replacement-of-mj15011.904877/#post-13718073](https://audiokarma.org/forums/index.php?threads/replacement-for-2sc1116a-replacement-of-mj15011.904877/#post-13718073) 
  because the feedback design expects higher bandwidth. Replacements 
  4MHz vs 10 and 15 MHz bandwidth. 

* Rather change to newer TO-3P format 

* {text:soft-page-break} 2SC945 (Q, P) Transistor is center 
  collector 



AnalogueBen in AudioKarma: 883773 recommended parts list: 

* [https://www.vintageshifi.com/repertoire-pdf/m-Sansui.php](https://www.vintageshifi.com/repertoire-pdf/m-Sansui.php) 
  points to: 

* transistor equivalents: [https://www.vintageshifi.com/sansui-au-717.php](https://www.vintageshifi.com/sansui-au-717.php) 
  saved as audio.sansui.amp_rebuild.au717.specifications_and_transistor_equivalents.odt 

* service manual: points to [https://www.vintageshifi.com/repertoire-pdf/pdf/telecharge.php?pdf=Sansui-AU-517-AU-717-Service-Manual.pdf](https://www.vintageshifi.com/repertoire-pdf/pdf/telecharge.php?pdf=Sansui-AU-517-AU-717-Service-Manual.pdf) 



AudioKarma Recommendations per lock.audio.sansui.amp_rebuild.au717.restore_via_audiokarma_supernoob-summary.docx 

* there are a number of typo errors, verify the parts 

* disassembly: F-2663: Power supply servicing tip - desolder 
  6 power supply leads from the bottom of board, remove the mount 
  brackets, and the board can be pulled forward for rebuilding. 
  (edit: had to remove many more wires than this!) 



AudioKarma Recommendations per audio.sansui.amp_rebuild.txt: 

* All Electrolytic Caps (including the four main filter caps) 
  were replaced 

* all VD1212 were replaced with 1N4148 In series 

* all 'black flag' caps were replaced (does he mean stryol??) 



* All Inter-Stage coupling and filter capacitors replaced 
  with HQ [high quality?] equivalents. 

* All controls were thoroughly cleaned and noise free. 

* Biased Current and DC output voltage were adjusted to within 
  specification. 



audio.sansui.amp_rebuild.au717.restore_via_audiokarma_leestereo.odt 

* Bible build is Leestereo (his name is Ben) build also referenced 
  by supernoob 

* Replace all power supply electrolytic capacitors with low 
  ESR types (increasing capacity where appropriate and physically 
  possible). 

* Replace all of the signal path electrolytic capacitors with 
  either "audio grade"/bi-polar electrolytic types or film 
  types (whenever possible). 

* Upgrade original polyester film capacitors to polypropylene 
  film types (as appropriate ie in signal path). 

* Replace signal path ceramic capacitors with film or C0G types. 

* Replace fuse resistors with metal film types; Fusible resistors 
  post 171 

* Replace VD1212 (dual diodes) with pair of 1N4148 diodes (in 
  series). 

* Replace any components damaged by the infamous corrosive 
  board glue. 

* Capacitor selection general 

* Match power supply resistors post 369 

* The capacitors C05 and C06, on the RIAA equalization. 

* F-2663 board contains 2 independent regulated 35V power supplies 
  (one for each channel). 

* Identify issues 

* Cleaning 

* Disassembly and Repair General 

* Reassembly 

* Testing and Review 

* Service Manual Parts lists often wrong: Post 235. “sometimes 
  they are wrong, and sometimes very wrong. Just look at the schematic 
  - which generally is very close to correct” 

* #379: stock configuration, the film capacitor at C20 is a by-pass 
  for the electrolytic capacitor at C22. Since the original 
  posting, subsequent AU-717 restorations have incorporated 
  upgrades to the stock 0.047µF polyester film by-passes to 
  0.1µF WIMA polypropylene types, as detailed in [post no. 210](https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-11#post-12690109) 
  Here is a picture of the installed WIMA MKP by-passes on F-2720. 

* F-2720 C31, C32 are removed because they are no longer needed; 
  see [https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-17#post-13473487](https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-17#post-13473487) 
  for why this is done. 



audio.sansui.amp_rebuild.au717.restore_via_marantzhallo-fi.odt 

* electrolytic were replaced with high temp (105C) long life 
  FC Panasonic and Nichicon PW capacitors with an increase in 
  operating voltages. 

* The Bipolars and .47 coupled electrolytic were replaced with 
  Nichicon VP and high grade WIMA MKP film capacitors. 

* All of the diode bridge 10D1 and 2473 were replaced with Fairchild 
  4148 and Ultra-Fast UF400# type diodes, all VD1212 type epoxy 
  diodes were replaced with series Fairchild 4148 diodes. 

* TO-220 voltage regulators which tend to show signs of excessive 
  heat are replaced with heavy duty OnSemi MJE TO-220 devices 
  and thermal compound applied. 

* The relay was replaced with a heavy duty low noise type Omron 
  MY4 relay. 

* Due to excessive glue damage about 15 carbon film resistors 
  were replaced with KOA carbon film resistors. 

* The solder joints due to excessive heat were reflowed as well. 

* large vertical axial electrolytic capacitors were affixed 
  to the PCB using a glue 

* Fusible resistor which exhibit two odd characteristics 

* By board is below 



Glue removal 

* [https://audiokarma.org/forums/index.php?threads/my-solution-for-easy-au-717-sansui-glue-removal.508267/#post-6602302](https://audiokarma.org/forums/index.php?threads/my-solution-for-easy-au-717-sansui-glue-removal.508267/#post-6602302) 

* spread cotton balls out on/around glue (tucked in good around 
  components) 

* saturate with 1-2 cap fulls of acetone 

* wait 15-20 minutes. 

* I found using an old credit card as a scraper or a flat exacto 
  knife blade but can scar the board 



Rebuild thread with photos: [https://audiokarma.org/forums/index.php?threads/sansui-au-717-restoration-and-upgrade.875646/](https://audiokarma.org/forums/index.php?threads/sansui-au-717-restoration-and-upgrade.875646/) 

* remove, clean, and give new thermal compound for transistors 



Diode replacement: audio.sansui.amp_rebuild.au717.diode_replacement.odt 

* Not recommended to replace power supply diodes except zener 
  and VD1212 diodes 

* ZD01/02 replace with BZX79-B13, ZD601 1N5232B and ZD602 1N5234C 

* For the VD1212 diodes use two 1N4148's in series for each. 



Super dirty cleaning advice: [https://audiokarma.org/forums/index.php?threads/new-member-really-dirty-au-717-need-advice.514913/](https://audiokarma.org/forums/index.php?threads/new-member-really-dirty-au-717-need-advice.514913/) 

Switch cleaning threads: 

* do not use Windex or WD40 

* {text:soft-page-break} [https://audiokarma.org/forums/index.php?threads/sansui-au-717-volume-control-pot-maitenence-help-please.43185/#post-594781](https://audiokarma.org/forums/index.php?threads/sansui-au-717-volume-control-pot-maitenence-help-please.43185/#post-594781) 

* [https://audiokarma.org/forums/index.php?threads/deoxit-d5.947097/#post-14504688](https://audiokarma.org/forums/index.php?threads/deoxit-d5.947097/#post-14504688) 

* [https://audiokarma.org/forums/index.php?threads/the-idiots-guide-to-using-deoxit-revisited.207005/](https://audiokarma.org/forums/index.php?threads/the-idiots-guide-to-using-deoxit-revisited.207005/) 



Polish videos by Hifi Surgery 

* [https://audiokarma.org/forums/index.php?threads/sansui-au-717-restoration.970989/page-2#post-15053101](https://audiokarma.org/forums/index.php?threads/sansui-au-717-restoration.970989/page-2#post-15053101) 

* Part 1: [https://www.youtube.com/watch?v=ZOxRPpDvTMA](https://www.youtube.com/watch?v=ZOxRPpDvTMA) 

* Part 2: [https://www.youtube.com/watch?v=5TagB6hAWHk](https://www.youtube.com/watch?v=5TagB6hAWHk) 



F-2723 Removal 

* [https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-13#post-13122658](https://audiokarma.org/forums/index.php?threads/leestereos-restoration-upgrade-of-a-sansui-au-717.641945/page-13#post-13122658) 



F-2670 Removal 

* {text:list-item} {text:list-item} {text:list-item} {text:list-item} 
  {text:list-item} 



Parts:
------

Run Tabula on audio.sansui.au-517_717_service_manual_en_imp_scan.pdf 
to pull out values 

Power caps 12000 uF 63 V electrolytic capacitor (original part) 
but others indicate 15,000 uF 

* 40.2 mm x roughly 3.5 inches tall 

* Mouser Nichicon 15000 uF 63 V 20% $20.85 x 4: LKG1J153MKNF KN 
  means 35|40 mm 

* Mouser Nichicon 22000 uF 63 V 20% $34.20 x 4: LKG1J223MKZ KZ 
  means 50-76 mm 

* The parts ending in S are better, F is lowest, other middle grade: 
  [datasheet](https://www.mouser.com/datasheet/2/293/e-lkg-875808.pdf) 

* warning: increase capacitance increases intake current 
  and could create sonic noise/transformer damage 

* Note that Outlaw Audio 2200 uses 13,600μF capacitance for 
  HP Rails; 6,600μF for LP Rail 

* Others using Kemet {text:bookmark} ALT22A153DE063 because 
  long-life, shorter, also cheaper, $15.68 each 



Lights get from Parts-Express.com for TU-717: [part 070-121 
LED 8 volt fuse](https://www.parts-express.com/led-fuse-lamp-for-marantz-sansui-kenwood-yamaha-sony-warm-white-8-volt-5-pack--070-121): 

{text:soft-page-break} [Rebuild Kit by hifiaudio](https://www.ebay.com/i/153892666802?chn=ps&norover=1&mkevt=1&mkrid=711-213727-13078-0&mkcid=2&itemid=153892666802&targetid=4580153133025496&device=c&mktype=&googleloc=&poi=&campaignid=403206344&mkgroupid=1224856168411792&rlsatarget=pla-4580153133025496&abcId=9300372&merchantid=51291&msclkid=c598181b3983154a6ec1477b19f73f66) 
on Ebay: 

> Power / Filter stage caps are those large silver cans mounted 
> on top of the chassis and sometimes underneath. This restoration 
> pack will make a huge difference in the sound quality. All the 
> parts are of high quality Japanese Nichicon / Panasonic / IC / 
> United Chemi capacitors. 

> 

> Included in this kit: 

> 1. Power/Filter stage capacitors (Nichicon / Panasonic / United 
> Chemi) electrolytic capacitors. 

> 2. Detailed instruction with colorful images, schematics, 
> manuals (all of these are in electronic form, I consider these 
> much better than printed version due to zoom availability). 

> 3. Schematics 

> 4. Complete audio path upgrade with high quality US made (IC) 
> or Panasonic audio grade film capacitors. 

> 5. Parts for compete recap of all the electrolytic capacitors. 

> 6. Complete recap of all PCBs. 

> 7. Some other parts if your unit requires it. 

> 8. fuse/s 

> 9. Instructions on how to clean the chassis. 

> 10. Instructions on how to clean the faceplate 

> 11. Instructions on how to polish and clean the knobs. 

> 12. Support/help to a reasonable extend in case you need it. (This 
> is what makes us different from other sellers.) 
