# CharlieDaniel
Charlie Daniel Phases 1 + 2

Data dictionary (for phase 1 migration and phase 2 creation/remediation) : 
Data review (this is just for review and so it is locked, if you find errors, wait til ingested in Islandora and we will edit there) : https://docs.google.com/spreadsheets/d/1znfLDvNVFZJkH9NmldlfU4Jez0H9t95riImFIBD8Npo/edit?usp=sharing

MODS/XML records for both phases are in All_Cleaned > modsxml subdirectory.

Data changes:
- URIs, normalized forms of names, places, subjects, forms, repositories were pulled
- subjects parsed into topical, name, geographic
- abstract made into name following phase 1 work and replacing lack of descriptive titles
- subcollections moved to shelf_locator element and then duplicated as subject_local - as these ternms serve both an organizational purpose as well as a descriptive/aboutness purpose
- collection name normalized against SCOUT, collection identifier pulled in
- additional fields added or corrected: file type, form, genre, digital origin, cataloging source, language, language of cataloging

Note on filenames/identifiers:
Phase 2 data does **not** use admindb styled identifiers for the filenames, but instead a locally formed version. However, for Phase 1 data, both kinds of possible filenames exist. For the phase 1 data, I used the AdminDb form for the filename and added the local form as a second identifier. 

