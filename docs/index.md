# awesome geoscience semantics
A curated list of geoscience semantic frameworks.

This work was inspired by    [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) lists.  

Join the chat at [![https://gitter.im/geoscience-semantics/geoscience-semantics.github.io](https://badges.gitter.im/geoscience-semantics/geoscience-semantics.github.io.svg)](https://gitter.im/geoscience-semantics/geoscience-semantics.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- - -
## Preliminaries
The following geoscience semantic models are organised based (loosely) on the ***semantic spectrum*** (Obrst, 2003; 2010; Uschold and Gruninger, 2004; Smith and Welty, 2001; McGuinness, 2003), with particular focus on the high level categorisations described by Guarino and others (2009).  

- - -
## Logical Languages
- Web Ontology Language ([OWL 2](https://www.w3.org/TR/owl2-overview/)) (there is also the initial version of [OWL](https://www.w3.org/TR/2004/REC-owl-features-20040210/))
- Knowledge Interchange Format ([KIF](http://logic.stanford.edu/kif/Hypertext/kif-manual.html))
- Common Logic ([CL](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=39175))

### upper-level domain ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies | domain |
| --------- | ---------------- | ---------------------------- | ----------- | ------- | ------ |
| SWEET | (Raskin, 2006); <br />(Raskin and Pan, 2005) |  | OWL-DL | Upper-level domain |
| NADM-C1 | (NADM Steering Committee, 2004); <br />(Richard, 2006) |  | UML | Upper-level domain; <br />Geologic Map |
| Geo-ontology | (Perrin et al., 2005) |  | KIF | general geology |
| Geological Time Ontology | (Perrin et al., 2011) | Geologic Time |
| Geological Dating Ontology | (Perrin et al., 2011) | Geologic Time |

### domain ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies | domain |
| --------- | ---------------- | ---------------------------- | ----------- | ------- | ------ |
| Basin Ontology | (Whitehead et al., 2010); <br />(Everett et al., 2011) | Exploration |
| Fractures Ontology | (Zhong et al., 2009); <br />(Zhong et al., 2008) | Structural |
| Hydrogeology Ontology | (Tripathi and Babaie, 2008) | Hydrogeology |
| StructuralGeoOntology | (Babaie et al., 2006) | Structural (top level, many sub-level ontologies) |
| FractureGeoOntology | (Babaie et al., 2006) | Structural |
| FoliationGeoOntology | (Babaie et al., 2006) | Structural |
| FoldGeoOntology | (Babaie et al., 2006) | Structural |
| pluton object ontology | (Sinha et al., 2006) | Petrology; informal; Ontology for processes acting on plutons |
| EPONT | (Malik et al., 2010) | Upper-level domain |
| Volcano system ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Volcanic phenomena ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Volcanic material ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Magma ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Volcanic Hazard ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Volcanic vulnerability ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Volcanic hazard management ontology | (Fauziati and Watanabe, 2010) | Volcanology |
| Volcano Ontology | (Fox et al., 2007); <br />(McGuinness et al., 2007b); <br />(Sinha et al., 2007) | Volcanology |
| Plate-tectonics Ontology | (Fox et al., 2007); <br />(McGuinness et al., 2007b); <br />(Sinha et al., 2007) | Plate-tectonics |
| Petrology Ontology | (Shkotin et al., 2012) | Petrology |
| Petroleum Basin ontology | (Nimmagadda et al., 2007) | Seismology |
| HIS ontology | (Piasecki and Beran, 2009); <br />(Beran and Piasecki, 2009) | Water resources |
| CUAHSI discovery ontology V1.0 | (Piasecki and Beran, 2009); <br />(Beran and Piasecki, 2009) | Water resources |
| Hierarchical classification of tectonic assemblages | (Struik and Quat, 2002) | Tectonics |
| Scheme for rock classification | (Struik et al., 2002) | Rock Classification |
| PetroGrapher | (Abel et al., 2004b) | Petrography |
| | (Abel et al., 2005); <br />(Abel et al., 2004a) | Petrography |
| stratigraphy ontology | (Abel et al., 2012) | Stratigraphy |
| Micropaleontology ontology | (Gary & Platon, 2010) | Micropaleontology |
| Gravity anomaly ontology | (Gates et al., 2007) | Seismology |


### task ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies | domain |
| --------- | ---------------- | ---------------------------- | ----------- | ------- | ------ |
| Event Ontology | (Mastella et al., 2007) | Geologic Events |
| EarthModel Ontology | (Mastella et al., 2007) | General Geoscience |
| Gravity ontology | (Salayandia et al., 2006) | Seismology |
| Gravity-data ontology | (Gates et al., 2007) | Seismology |
| GravityWDO | (Da Silva et al., 2007) | Seismology; (gravity data processing) |
| Wings | (Gil et al., 2007) | |
| | (Maechling et al., 2005) | |



### application ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies | domain |
| --------- | ---------------- | ---------------------------- | ----------- | ------- | ------ |
| Data and Ontology MAPPING (GEON) | (Lin and Ludäscher, 2004); <br />(Lin and Ludäscher, 2003) | Data Integration |
| data model ontology | (Parekh et al., 2004) | Data Integration |
| geoonto ontology | (Xiong et al., 2009) | Application |
| Geologic Ages | (Rainaud et al., 2008) | Application |
| Basic Geology | (Rainaud et al., 2008) | Application |
| Geographical Terms | (Rainaud et al., 2008) | Application |
| ESG ontology | (Pouchard et al., 2003) | General Geoscience Data (ontology for scientific information) |
| | (Victoreti et al., 2007) | Petrography |
| Structural modelling ontology | (Zhu et al., 2009) | Structural |
| Data set Ontology | (Movva et al., 2005) | Geoscience Data |
| event ontology | (Zhu et al., 2010) | Well surveillance (processes) |
| Virtual Data Archive (VDA) Ontology | **(Keller et al., 2008)** | Data Archive |
| BGC-DAAC Data Archive Ontology | **(Keller et al., 2008)** | Data Archive |
| STEWARDS Data Archive Ontology | **(Keller et al., 2008)** | Data Archive |


- - -
### Data Models
- Resource Description Framework ([RDF](https://www.w3.org/TR/owl2-overview/))

| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies | domain |
| --------- | ---------------- | ---------------------------- | ----------- | ------- | ------ |
| *what goes here?* | *who created it?*   | *what was it about?* |
| geotime... | ma et al | something about time... |


- - -
## Metadata, XML Schema & Data Models

### XML & XML Schema
*I do not distinguish between XML and XML Schema.  I assume any raw XML will have sufficient documentation.*

| schema name      | citation                                | brief synopsis                                       |
| ---------------- | --------------------------------------- | ---------------------------------------------------- |
| [GML](http://www.opengeospatial.org/standards/gml) | <p>(Portele et al., 2011; 2007);</br> (Lake et al., 2004);</br> (Cox et al., 2003)</p>     | **Geographic Markup Language**: geographic, or geospatial, objects, including: measurement and observation |
| [GeoSciML](http://www.geosciml.org/) | (Sen and Duffy, 2005) | Data transfer standard for geological data and applications |
| [EarthResourceML](http://www.earthresourceml.org/) | (Raymond et al., 2012) | A standard for exchanging information about mineral occurrences, mines, and mining activities. |
| EarthquakeML | (Babaie and Babaei, 2005a) | Seismology |
| TectonicsML  | (Babaie and Babaei, 2005b) | Seismology |
| [QuakeML](https://quake.ethz.ch/quakeml) | (Schorlemmer and Euchner, 2007) | Seismology |
| [GPML](http://www.gplates.org/gpml.html) | (Qin et al., 2012) | **GPlates Markup Language**: Geology & Geophysics |
| [HYDROML](http://water.usgs.gov/XML/NWIS/nwis_hml.htm) | (USGS, 2012) | **USGS Hydrologic Markup Language** (also called _USGSHydroML_): XML tags for hydrologic information |
| [WaterML](http://www.opengeospatial.org/standards/waterml) | (Zaslavsky et al., 2007) | A standardised model for the representation and exchange of water observation data. |
| [GWML](http://ngwd-bdnes.cits.rncan.gc.ca/service/api_ngwds/en/gwml.html) | (Boisvert and Brodaric, 2007; 2010) | **GroundWater Markup Language**: |
| [HydroXC schema](http://www.nws.noaa.gov/ohd/hydroxc/) | (Piasecki, 2007) | Water resources |
| [WDTF](http://www.bom.gov.au/water/standards/wdtf/) | (Yu et al., 2011) | **Water Data Transfer Format**:  |
| [SoTerML](http://www.ogcnetwork.net/node/618) | (Pourabdollah et al., 2012) | **Soil and Terrain Markup Language**: |
| RiverML | (Jackson and Maidment, 2014); (Jackson et al., 2013) |  |
| [SoilML](http://www.opengeospatial.org/projects/initiatives/soildataie) | (Montanarella et al., 2010) | |
| [WITSML](http://www.energistics.org/drilling-completions-interventions/witsml-standards/current-standards) | (Energistics, 2012) | **Well Information Transfer Standard Markup Language**: Energy and Petroleum |
| [RESQML](http://www.energistics.org/reservoir/resqml-standards) | (Energistics, 2011) | **Reservoir Quality Markup Language**: Energy and Petroleum |
| [SensorML](http://www.opengeospatial.org/standards/sensorml) | (Botts and Robin, 2007) | **Sensor Model Language**: |


- - -
### Thesauri or Taxonomies
* [AGI thesaurus](http://www.americangeosciences.org/georef/thesaurus)


- - -
### Glossaries and Data Dictionaries

*Basic sources of geoscience terminology. There are many versions of resources that could populate this section.  These are provided for example only to illustrate overall comprehensiveness.*

* [Dictionary of Geologic Terms](https://books.google.co.uk/books?id=m4iFpN2SpkEC&printsec=frontcover&dq=editions:ISBN0385181019) - A hard copy dictionary.
* [Dictionary of Geology & Earth Sciences](http://www.oxfordreference.com/view/10.1093/acref/9780199653065.001.0001/acref-9780199653065) - A hard copy dictionary.
* [General Dictionary of Geology](https://alvathea.files.wordpress.com/2009/01/general-dictionary-of-geology.pdf) - A general dictionary of geology.

* [Glossary of Geology](http://www.americangeosciences.org/pubs/glossary/) - Hard copy glossary.  (Also available as a paid app on [iTunes](https://itunes.apple.com/us/app/glossary-of-geology/id398194234?mt=8) and [Google Play](https://play.google.com/store/apps/details?id=org.agiweb.glossaryofgeology&hl=en))
* [GSL Glossary of Terms](https://www.geolsoc.org.uk/ks3/gsl/education/resources/rockcycle/page3451.html) - The Geological Society's glossary of terms.

* [AGU Index of Terms](http://onlinelibrary.wiley.com/doi/10.1029/EO067i039p00756/abstract) - Closed set of terms used by the American Geophysical Unioon (AGU) to categorize conference and publication keywords.<br />
* [Global Change Master Directory](http://gcmd.nasa.gov/learn/keywords.html) - Terms for tagging NASA's Earth Science data and services.

- - -
## Geoscience frameworks utilizing semantics
* Talkoot
* TERN
* NEON

- - -
## Geoscience services
- [British Geological Survey Vocabulary web service](Vocabulary web service)
- [SISSVoc](http://www.sissvoc.info/) the Spatial Information Services Stack Vocabulary Service
- oceanLink
- geolink

- - -
## Resources
Where to discover new geoscience semantic artefacts.

- - -
### Academic Journals
* [Earth Science Informatics](http://link.springer.com/journal/12145)
* [Computers & Geosciences](http://www.journals.elsevier.com/computers-and-geosciences/)
* [Semantic Web Journal](http://semantic-web-journal.net/)
* [Applied Ontology](http://www.iospress.nl/journal/applied-ontology/)
* Journal of Data Semantics
* [Journal of Web Semantics](http://www.journals.elsevier.com/journal-of-web-semantics/)

- - -
### Conferences
* []
* []

- - -
### Websites and other work under construction
*material that was culled from an online resource, but hasn't (to my knowledge) been published*
github:<br />
BCube,<br />
ToolMatch,<br />
Spatial Data WG (W3C),<br />
DataONE sem-prov-design,<br />
ANU-Linked-Earth-Data ontology<br />
RDA working groups<br />
  -a<br />
  -b<br />
OGC<br />
GTWG (working group for GeoSciML vocabularies)<br />
etc...

- - -
### Twitter
[@ge0semantics](https://twitter.com/ge0semantics)

[//]: # (review ontology summit 2016 material, in particular, Torsten's slides/references )
[//]: # (go through book edited by Fox and Narock)
[//]: # ()

- - -
### Other Relevant Lists

* stuff
    * [pycrumbs](https://github.com/kirang89/pycrumbs/blob/master/pycrumbs.md)

* things
    * [awesome](https://github.com/sindresorhus/awesome)

- - -
A ***big*** thanks to [roomthily](https://github.com/roomthily) for the suggestion.
