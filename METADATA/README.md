# Ants of the State of Pará, Brazil.

## Raw data for the research approach on Ants of the State of Pará, Brazil: a historical and comprehensive dataset of a key biodiversity hotspot in the Amazon Basin.

#### Raw data (spreadsheets in .txt format):
- ANTS_OF_PARA_dataset_v1-2021-04-03d (Raw data on the species-level records used to the manusript 'Ants of the State of Pará, Brazil: a historical and comprehensive dataset of a key biodiversity hotspot in the Amazon Basin').

#### Description of the fields related to the data set linked to the file ANTS_OF_PARA_dataset.

- Code: Unique ID code for each row in the dataset;
- Genus: Genus name as published or noted on the specimen label;
- Species: Species name as published or noted on the specimen label;
- Subspecies: Subspecies name as published or noted on the specimen label;
- Subfamily: Valid subfamily name for the specimen;
- Valid.Genus: Valid genus name for the specimen;
- Valid.Species: Valid species name for the specimen;
- Valid.Subspecies: Valid subspecies name for the specimen;
- Technical.Validation: Indicates if the record is valid for the state of Pará.  validated_record = Yes (valid);  excluded_record = No (record not validated);
- Caste: Caste (worker, queen, male) of the specimen;
- Country: Country where the specimen was collected;
- State: State where the specimen was collected;
- Para.isLatLon: Indicates record without further spatial resolution (i.e., first-order administrative division only). 0 = NO; 1 = YES (no further spatial resolution);
- Municipality: Municipality where the specimen was collected as extracted from the coordinates;
- Locality: Original locality name as published or noted on the specimen label;
- Latitude.Y: Latitude coordinates rounded to 6 decimal places (Datum WGS84);
- Longitude.X: Longitude coordinates rounded to 5 decimal places (Datum WGS84);
- Coordinate.Available: Indicates whether coordinates were georeferenced. NO = coordinates estimated; YES = coordinates available from Source.Citation field;
- Coordinate.Source: Source of georeferenced coordinates;
- Coordinate.Information: Any additional information on extracted coordinates;
- Year: Year of specimen collection or of publication for literature records;
- Type.of.Data: Datasets obtained from leading Brazilian Scientific Institutions or from published sources;
- Collector: Collector’s name as noted on the specimen label;
- Method: Method of collection;
- Label.Code: Label code as noted on the specimen label;
- Label.Add.Info: Any additional information on the specimen label;
- Source.Citation: Full literature reference (Author, Date, Title and Scientific Journal) or Institution (Museum Specimen) or Database Collection;
- Observations: Any additional information from the specimen record;
- Exotic: Refer to exotic species records in the State of Pará. YES = exotic species; NO = native species.

#### Data reading suggestion in R: 

read.table ("ANTS_OF_PARA_dataset_2021-04-03d.txt", header = TRUE,
		stringsAsFactors = FALSE,
		na.strings = c("","NA"),
		fileEncoding = "UTF-8",
		sep = "\t",
		dec=".")

#### References:
Albuquerque, E.Z., Prado, L.P., Andrade-Silva, J., Siqueira, E.L.S., Sampaio, K.L.S., Alves, D., Brandão, C.R.F., Andrade, P.L., Feitosa, R.M., Koch, E.B.A., Delabie, J.H.C., Fernandes, I., Baccaro, F.B., Souza, J.L.P., Almeida, R.P. & Silva, R.R. (2021). Ants of the State of Pará, Brazil: a historical and comprehensive dataset of a key biodiversity hotspot in the Amazon Basin. Zootaxa, 5001(1):1-83. DOI: https://doi.org/10.11646/zootaxa.5001.1.1

