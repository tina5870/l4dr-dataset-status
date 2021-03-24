# ldr-dataset-status

This repository tracks the status of publication/use of Loc-I for Disaster Recovery (l4dr) datasets. It is expected that this information will eventually be folded into the project catalogue and this repository removed.

* X - yes
* ~ - partly
* (empty) - no

**Dataset** | **Manager** | **Have Data** | **Ontology** | **RDF Dataset** | **Ingested into Data Platform** | **Listed in Catalogue** | **Published Via API**
--- | --- | --- | --- | --- | --- | --- | ---
ASGS | David | X | X | ~<br />(old LocI) | | |
Power Infrastructure | Tina | X | | ~ | | ~
Place Names | Tina | X | X | ~<br />(API) | | X
Facilities | Joe/Tina | X | | | | |
Exposure |Joe/Tina | X | | | | |
Floods | | | | | | |
Tropical Cyclones | | | | | | |
Burnt Areas | Joe | X | | | | |
Earthquakes | | | | | | |


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
