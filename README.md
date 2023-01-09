# DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Christian_Schindler

Project: Import information about DFG-Projects into Wikidata

Used Methods/Tools:
  - Python 3
  - BeautifulSoup Python Library
  - OpenRefine

This project consists of three parts:

1. Extract Information (from catalogue: https://gepris.dfg.de/gepris/OCTOPUS?task=showKatalog)
   - The data was screenscraped with the python library beautifulsoup and python. 
   - The corresponding Jupyter Notebook with the code can be found in the root directory (dfg_project_screenscraping.ipynb)
   - The scraped data can be found in the root directory (gepris_project_data_scraped.csv)
2. Clean and Format data
   - The data was cleaned and formatted with OpenRefine
   - The cleaned data can be found in the root directory (gepris_project_data_cleaned.csv)
3. Reconcile and upload
   - The data was reconciled and uploaded with OpenRefine
   ~ 6900 Wikidata items of DFG-Projects were successfully created and linked with other data
   - An Example of a Wikidata-Item can be found here: https://www.wikidata.org/wiki/Q116084028
