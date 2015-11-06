# mods_ingest
mods ingest for Islandora 

This site is to track development of a mods ingest form for Islandora.

151102: changes made to Mform_100.xml to correct problem with identifier element.

The development will be guided by:
 1.  http://www.loc.gov/standards/mods/mods-outline-3-5.html (mods 3.5 standard)
 2.  https://wiki.lib.utk.edu/display/DLP/Trace+Metadata+Application+Profile (from Christina Harlowe)
 3. https://wiki.lib.utk.edu/pages/viewpage.action?pageId=2556374 (The UTK MODS/
Islandora Display Working Doc by Christina Harlowe)
 4.  http://diglib.lib.utk.edu/~cdeane/w2009/MODS/training3v6/training3v6_GET.php (MODS WORKBOOK no database version)

This site will be organized as follows:

  1. Mform_100.xml (the ingest form)
  2. Mmods_100.xml (the mods datastream created by Islandora using Mform_100.xml)
  
To test this file in your own vagrant islandora site:

Basic Image:
create identifier: 0012_003299_00207_0001
     ingest image: 0012_003299_00207_0001.jpg 

1. Copy Mform_100.xml to vagrant/drupal_home/sites/all/modules/islandora_solution_pack_image//xml/islandora_basic_image_form_mods.xml
2. Ingest 0012_003299_00207_0001
3. View datastream MODS


Large Image:
create identifier: 0012_003299_00207_0001
     ingest image: 0012_003299_00207_0001.tif

1. Copy Mform_100.xml to vagrant/drupal_home/sites/all/modules/islandora_solution_pack_large_image//xml/islandora_basic_image_form_mods.xml
2. Ingest 0012_003299_00207_0001
3. View datastream MODS


Changes will be tracked in the wiki at:

https://wiki.lib.utk.edu/display/DLP/Islandora+Form+to+Ingest+MODS+for+Small+and+Large+Image+Content+Types
