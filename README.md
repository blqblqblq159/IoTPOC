# IoTPOC
proof of concept of the semantic enrichment of sensor data

## base ontology
Base ontology used is the SOSA ontology (https://www.w3.org/TR/vocab-ssn/). To import the ontology, in protege, go to file > Open from URL and insert "http://www.w3.org/ns/sosa/"

## add individuals
We add some individuals in this ontology from spreadsheets. This is done with Tools > Create Axioms from Excel Workbook
- The first spreadsheet onto.xlsx has the accompanying rules onto_rules.json. This imports the sensor information.
- The second spreadsheet temp_data.xlsx has the rules data_loader.json. This imports the data from the sensor reading.

## full ontology
The full ontology with the sosa base and the imported individuals is located in sosa_with_data.owl