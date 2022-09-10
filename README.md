View Readme as github page: https://dbuschhue.github.io/rdb_ser_data/

# A Relational Database for Research Data Science Education Research Data

## Objective of Project
Build a relational database for typical quantitative science education research data with a high generalisability for other studies so that it can be used and further developed by different researchers. 
In this way, we aim to make research more efficient and improve data quality internally and for FAIR use of data (Wilkinson et al., 2016).

Link to research Poster (German): https://www.uni-potsdam.de/de/physikdidaktik/mitarbeiter/davidbuschhueter/gdcp-jahrestagung-2022-in-aachen


## Purposes of Data Base
1. Archiving research data
2. Data entry
3. Data deletion
4. Enabling secondary analysis

## Current Stage of the project
1. A conceptual model has been built
2. A logical model built
  - setting attributes   
4. A (partial) physical model has been built:
  - Adding bridge tables
  - Data types
  - Relationship setting
      - choices for primary keys
      - secondary keys (which relationships are mandatory)
      - adding bridge tables

**Note**: The database currently serves the purpose of communicating a data model (most of the settings are default settings in MySQLWorkbench 8.0). The database cannot be implemented at this stage and is not tested.

## Enhanced Entity Relationship Diagram
![alt text](img/EER.png?raw=true)

## References
Wilkinson, M. D., Dumontier, M., Aalbersberg, Ij. J., Appleton, G., Axton, M., Baak, A. et al. (2016). Comment: The FAIR Guiding Principles for scientific data management and stewardship. Scientific Data, 3, 1–9. https://doi.org/10.1038/sdata.2016.18














