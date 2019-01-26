ead_process.py is a script to select data from two different XML sources, and populate a Google Sheet to review individual elements from both side by side. This was developed as a pre-migration QC process for CUL migration of legacy finding aids into ArchivesSpace.

Dependencies:

* GoogleSheetAPITools - https://github.com/dwhodges2/googlesheet_tools
* lxml
* re

Optionally, a "secrets" file can be used to privately store the id of a Google Sheet to interact with.

