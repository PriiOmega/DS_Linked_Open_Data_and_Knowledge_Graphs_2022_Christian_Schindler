# DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Christian_Schindler

Project: Import information about DFG-Projects into Wikidata

Used Methods/Tools:
  - Python 3
  - BeautifulSoup Python Library
  - OpenRefine

This project consists of three parts:

1. Extract Information (from catalogue: https://gepris.dfg.de/gepris/OCTOPUS?task=showKatalog)
   - The data was screenscraped with the python library beautifulsoup and python. The code can be found in the jupyter-notebook file dfg_project_screenscraping.ipynb
2. Clean and Format data
   - The data was cleaned and formatted with OpenRefine
3. Reconcile and upload
   - The data was reconciled and uploaded with OpenRefine
   - An Example of a Wikidata-Item can be found here: https://www.wikidata.org/wiki/Q116084028
