# On-campus job (OCJ) for Open Science Promotion Section (OSPS)
This repository stores all codes that have been used for COJ-OSPS of Atmosphere and Ocean Research Institute (AORI), University of Tokyo.

# Tasks of OCJ-OSPS
There were several tasks to be completed: 
1) re-organize all CTD data into one list, breaking down key information such as instrument type and measurement dates.
2) list up user information from "船舶使用願い(Application for Research Vessel)", and assign contact information to the list
3) read scanned copies of STD (old CTD data) and turn into data file (i.e., CSV file)
For achieving 1-3, several Python codes were implemented for each purpose. Below descirbes key functions of each source code.

# Description
CTD_main: generating metadata file by reading and processing >8000 CTD data.

contact_main: compile all excel files and merge contacts into one list.

update_observationLog: update ObservationLog using information in "contact.xlsx".

Hand-written_OCR.ipynb: retrieve information from scanned hand-written PDF files

STD_main: similar to Hand-written_OCR, retrieve information from scanned STD PDF files 

# Note
- Hand written Japanese is recognized by Google Vision API, which requires account token.