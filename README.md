# Digital Atlas datasets status

This repository tracks the status of publication/use of Digital Atlas datasets. It is expected that this information will eventually be folded into the project catalogue and this repository removed.

* X - yes
* ~ - partly
* (empty) - no

**Dataset** | **Manager** | **Have Data** | **Ontology** | **Run ETL on GA infra** | **Run API + triplestore on GA infra** | **End to end testing of ETL update flowing through to API** | **Notes** 
--- | --- | --- | --- | --- | --- | --- | --- 
ASGS | David | X | X | | | | 
Power Infrastructure | Tina | X | FSDF + vocabs | | | | 
Place Names | Tina | X | X | | | | 
Facilities | Tina | X | FSDF | | | | 
Floods | X | FSDF | | | | | 
ABS stats | X | FSDF + Vocabs | | | | | Out of Scope
Exposure | | | | | | | Out of Scope
Tropical Cyclones | | | | | | | Out of Scope
Burnt Areas | Joe | X | | | | | Out of Scope
Earthquakes | | | | | | | Out of Scope


## ASGS
#### Data
Original data is XML data taken from a production Web Service (WFS) hosted by the ABS at <https://geo.abs.gov.au/arcgis/services/ASGS2016/MB/MapServer/WFSServer?service=wfs&version=2.0.0&request=GetCapabilities>.

#### Ontology
Published online at <https://linked.data.gov.au/def/asgs>.

#### RDF Dataset
RDF data was originally interpreted _on the fly_ from this WS but is now available for download from the LocI S3 bucket (David knows where this is).

The online data API is at <https://linked.data.gov.au/dataset/asgs2016>.

Geometry data is within the LocI Geometry Data Service (https://gds.loci.cat/).

#### Ingested into Data Platform
#### Listed in Catalogue
#### Published Via API


## Place Names
#### Data
Direct connection to FSDF database - SURROUND has access details.

#### Ontology
<https://linked.data.gov.au/def/placenames>

#### RDF Dataset
The RDF dataset is being built according to the ontology, within the API at <https://linked.data.gov.au/dataset/placenames>, but this needs validiating.

Code from the API can be reused to produce a static dataset, see the API's source code at <https://github.com/GeoscienceAustralia/placenames-dataset/tree/master/model>.


#### Ingested into Data Platform
#### Listed in Catalogue
#### Published Via API

## Power Infrastructure
#### Data
Data is held in table form at GA. Example rows of the data have been sent to SURROUND (Nick).

#### Ontology
#### RDF Dataset
#### Ingested into Data Platform
#### Listed in Catalogue
#### Published Via API

## Power Infrastructure
Combined Power Lines, Power Stations, Power Substations

#### Data
CarSA data sets DB

#### Ontology
#### RDF Dataset
#### Ingested into Data Platform
#### Listed in Catalogue
#### Published Via API

## Facilities
#### Data
CarSA data sets DB

#### Ontology
#### RDF Dataset
#### Ingested into Data Platform
#### Listed in Catalogue
#### Published Via API
