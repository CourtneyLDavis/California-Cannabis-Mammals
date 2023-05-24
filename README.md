# California-Cannabis-Mammals

# Integrating existing data to assess the risk of an expanding land use change on mammals
Submitted to Landscape Ecology

Lindsey N. Rich*, Ivan Medel, Sara Bangen, Greta Wengert, Matthew Toenies, Jody Tucker, Mourad Gabriel, Courtney Davis

*Please contact the first author with any questions about the code or publication: Lindsey N. Rich (lindsey.rich@wildlife.ca.gov)


## Abstract
Land-use change, including agricultural expansion, is one of the major drivers of biodiversity loss globally. Given the rapid pace of land-use change, data-driven, strategic, and dynamic conservation planning is imperative. We present an exemplar application of using existing data to inform conservation planning. Specifically, we developed a systematic approach for identifying areas of conservation concern due to cannabis cultivation in California, USA. We used three existing datasets: 1) camera trap data from ten projects (n = 1,186); 2) the locations of cannabis cultivation sites eradicated by law enforcement (n = 834); and 3) the locations of cultivation licenses (n = 4,366). We analyzed this data using multi-species occupancy models to estimate the occupancy and richness of 30 species, and maximum entropy models to estimate the risk of unlicensed and trespass cultivation. We then identified areas of overlap and determined the percent of suitable habitat potentially impacted by cannabis cultivation. Cannabis cultivation potentially influenced 39–74% of suitable habitat for special status species. Private land cultivation tended to have a larger influence on generalist species whereas trespass cultivation had the largest potential influence on fisher (Pekania pennanti), a special status species. Our results can be used to prioritize eradication, restoration, and remediation activities; to target mitigation efforts; and to guide the placement of new, licensed cultivation. Our approach demonstrates the utility of aggregating existing biological and socioeconomic data to inform conservation planning and is broadly applicable to other data sources and ecological stressors.


## Repository Directory
This repository will be archived on Zenodo upon acceptance.

### Scripts
This contains the JAGS model file to run the multi-species occupancy analysis using processed camera trap data on 30 mammals species in the northern and Siera Nevada region of California, USA. It includes the following:

- `Multispecies_CA_Mammals.txt`: JAGS model file for hierarchical multi-species model used in analysis.

