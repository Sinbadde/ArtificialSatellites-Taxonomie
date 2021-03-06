# ArtificialSatellites-Taxonomie
![satellite](https://user-images.githubusercontent.com/32934338/155358562-c7096a5f-adc6-4004-9819-41eaf2433e7f.jpg)
![MISP-logo](https://user-images.githubusercontent.com/32934338/155358978-9fa6ecb8-37b9-45b8-a456-d415e85f4ce1.png)


In the context of the realization of a project of the threat intelligence module of the Master 2 SSI (information systems security) 2021-2022 in the UFR-MIM in Metz, we had the opportunity to contribute to the enrichment of MISP by focusing on a taxonomy dedicated to astronomy which is a domain that interests us particularly.
Given the diversity of this field, we focused on artificial satellites. 

# Implementation of the project 

After several researches we found some interesting websites which helped us to build a large knowledge base on the different existing artificial satellites (about 2000).

## Used links ##
- https://space.oscar.wmo.int/satellites
- https://www.isro.gov.in/list-of-spacecrafts
- https://www.celestrak.com/NORAD/elements/

## Json script  ##
Thanks to this knowledge base we built a json based on examples of taxonomies found in the link https://github.com/MISP/misp-taxonomies
This was done by first classifying all the information on excel tables and sorting it before building the [json file](https://github.com/Sinbadde/ArtificialSatellites-Taxonomie/blob/main/machinetag.json), and then adapting it to the format of a json script appropriate for a MISP taxonomy.


# TO-DO LIST

- [x] Search for artificial satellites
- [X] Classification and sorting of information
- [X] Creating a proper json file in MISP format
- [ ] File checking
- [ ] Validation by the MISP team in charge of the project
- [ ] Integration into the MISP project

# Collaborators 

- RABER Lydia  https://github.com/lydia-lyly
- SAIDI Lysa https://github.com/yasmine15
- MERGEN Mélanie https://github.com/Sinbadde

# MISP Team in charge of this Project 

- Alexandre DULAUNOY : https://github.com/adulau
- Raphaël VINOT : https://github.com/Rafiot



