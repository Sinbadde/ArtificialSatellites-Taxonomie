# ArtificialSatellites-Taxonomie

In the context of the realization of a project of the threat intelligence module of the Master 2 SSI (information systems security) 2021-2022 in the UFR-MIM in Metz, we had the opportunity to contribute to the enrichment of MISP by focusing on a taxonomy dedicated to astronomy which is a domain that interests us particularly.
Given the diversity of this field, we focused on artificial satellites. 

# Implementation of the project 

After several extensive researches we found many interesting websites that helped us to build a large knowledge base on the different existing artificial satellites (about 1000).

## Used links ##
- https://space.oscar.wmo.int/satellites
- https://www.isro.gov.in/list-of-spacecrafts

## Json script  ##
Thanks to this knowledge base we built a json based on examples of taxonomies found in the link https://github.com/MISP/misp-galaxy/blob/main/clusters/android.json
This was done by first classifying all the information on excel tables and sorting it before building the [json file](https://github.com/Sinbadde/ArtificialSatellites-Taxonomie/blob/main/machinetag.json) and adapting it to the format of a json script appropriate for a MISP taxonomy.


# TO-DO LIST

- [x] Search for artificial satellites
- [X] Classification and sorting of information
- [X] Creating a proper json file in MISP format
- [ ] File verification
- [ ] Validation by the MISP team in charge of the project
- [ ] Integration into the MISP project



