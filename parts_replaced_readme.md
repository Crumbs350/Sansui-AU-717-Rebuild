# Sansui AU-717 Replacement Parts List Cross-Reference
This page describes the worksheets and logic that went into merging the different published part bill of materials, and tracking the replacement of parts.

The bill of materials I used and tracking of the parts I replaced is in [audio.sansui.au-717.parts_list.ods](audio.sansui.au-717.parts_list.ods) with worksheets defined as:

worksheet | description
--------- | -----------
part_translation | maps abbreviations and board codes to descriptive names
original_tabula_export | tabula export of tables in the service manual; first attempt to extract part information
parts_list | a manual clean up and refinement of the original_tabula_export of part information
parts_list_mods | merges part list, LeeStereo, SuperNoob, and other BOMs to cross-reference what parts different people used.
bom_reduced | a quantity vs part reduction of parts_list_mods; can't remember when I created this
parts_list_replace_track | <li>built from parts_list_mods reduced to only ordered/modified parts</li><li>**part_procured** column lists the part number</li><li>**Mouser part** column lists the procured mouser order part number</li><li>**Part I need** marks quantity</li><li>**position** is the PCB position on the board, mostly correct</li><li>**Location** = PCB name</li><li>**Parts No.** = part number in schematic</li><li>**Removed Left/Right** and **Replaced Left/Right** allow me to track what was done, with numbers generally representing the recorded values measured for that part.</li>
