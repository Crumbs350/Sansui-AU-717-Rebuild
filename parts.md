Capacitors 
-------

Per [link](https://electronics.stackexchange.com/questions/69919/ceramic-vs-film-capacitor-which-one-is-preferred-in-audio-circuits). 

Film Capacitor 
* typically denotes polyester or polymer film as the dielectric 
* metallized film capacitors are the same thing: metallic coating 
  being applied to an extremely thin polymer film, to create 
  the conducting electrodes of the capacitor. 


Ceramic capacitors 
* somewhat non-linear in their frequency and voltage responses, 
  compared to film capacitors. 
* tend to behave as microphones, thus picking up ambient sound 
  and modulating the voltage across them accordingly. 


Identifying capacitors: [https://studyelectrical.com/2016/12/different-types-classification-of-capacitors.html](https://studyelectrical.com/2016/12/different-types-classification-of-capacitors.html) 

* non-polarized capacitors: Ceramic and Film capacitors 
* polarized capacitors: Electrolytic and Super Capacitors 
* longer lead generally +

![Capacitor Overview](https://2.bp.blogspot.com/-3DwRXQd95Uo/WFLEIma9X7I/AAAAAAAACKg/Jf-3lqeSDD4vsvlkFh-g1GIeRlZBeof5wCLcB/s1600/Fixed_capacitors_overview.svg.png)



Resistors
-------

* Metal film less noisy than carbon film 

* smaller PPM means smaller temperature change per degree C 



Diodes 
-------

* audio.sansui.amp_rebuild.au717.diode_replacement.odt 

* Toshiba 1S1588 = ROHM 1S2473 
  * [source datasheetarchive](https://www.datasheetarchive.com/pdf/download.php?id=d518826479d16ab94592bc8828fd3bdd39be44&type=P&term=1S2473%2520DIODE)
  * saved: ../data/hardware/audio/sansui_au-tu_717/rebuild_mod_references/diode_cross_reference.pdf
  * 35 V reverse, 110 mA
* 1S2227 = international rectifier 10D2 
  * [source alldatasheet.com](https://html.alldatasheet.com/html-pdf/114651/IRF/10D2/51/1/10D2.html)
  * 1.6 A, 200V which matches reference https://www.audiokarma.org/forums/index.php?threads/reviving-au3900.910028/#post-13705338 that it is 1.5 A 200 V and can use 1N5393
  * the saved thread suggests a 1N4003 but I think this is too low a current
* IR 10D1 = 10D1 (1S2226) 1A 
  * [https://www.vintageshifi.com/sansui-G9000.php](https://www.vintageshifi.com/sansui-G9000.php) suggests 1N4002, NTE116
  * others used 1N4004 higher voltage
