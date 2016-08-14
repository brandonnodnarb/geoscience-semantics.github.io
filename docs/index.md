# awesome geoscience semantics
*"That rug really tied the room together."*<br />
-[The Dude](http://www.imdb.com/character/ch0003518/?ref_=tt_cl_t1)
<br /><br />
A curated list of geoscience semantic resources.

[![https://gitter.im/geoscience-semantics/geoscience-semantics.github.io](https://badges.gitter.im/geoscience-semantics/geoscience-semantics.github.io.svg)](https://gitter.im/geoscience-semantics/geoscience-semantics.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  [![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=brandonnodnarb&url=http://www.geoscience-semantics.info&title=awesome_geoscience_semantics&language=en_GB&tags=geosciene,semantics,github&category=semantic_web)

- - -
## Preliminaries
The following geoscience semantic models are organised based (loosely) on the ***semantic spectrum*** (Obrst, 2003; 2010; Uschold and Gruninger, 2004; Smith and Welty, 2001; McGuinness, 2003), with particular focus on the high level categorisations described by Guarino and others (2009).  

The criteria distinguishing between *upper-level*, *domain*, *task*, and *application* ontologies is taken from Guarino ([CITE]), Obrst ([CITE]), and Obrst and Cassidy ([CITE]).
- - -
## Logical Languages
- Web Ontology Language (OWL) -- the current, updated, version is [OWL 2](https://www.w3.org/TR/owl2-overview/); the initial version, referenced in many of the published works, is [OWL](https://www.w3.org/TR/2004/REC-owl-features-20040210/).  There is no distinction between versions, only expressivity where available.
- Knowledge Interchange Format ([KIF](http://logic.stanford.edu/kif/Hypertext/kif-manual.html))
- Common Logic ([CL](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=39175))

### upper-level domain ontologies
| name      | citation  | brief synopsis               | expressivity <br />marker  | dependencies |
| --------- | --------- | ---------------------------- | -------------              | ------------ |
| SWEET | (Raskin, 2006); <br />(Raskin and Pan, 2005) | - | OWL-DL | - |
| NADM-C1 | (NADM Steering Committee, 2004); <br />(Richard, 2006) | Conceptual framework for top level geologic concepts & controlled vocabulary for geologic map data | Conceptual Model; UML | - |
| Geo-ontology | (Perrin et al., 2005) | Four schemas formalising structural geologists expert knowledge for 3D models, interpretation & provenance | KIF | - |
| Geological Time Ontology | (Perrin et al., 2011) |  | Conceptual Model; OWL | Geo-ontology |
| Geological Dating Ontology | (Perrin et al., 2011) |  | Conceptual Model: OWL | Geo-ontology |


### domain ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies / related |
| --------- | ---------------- | ---------------------------- | -------------              | -------------           |
| Basin Ontology | (Whitehead et al., 2010); <br />(Everett et al., 2011) |  | OWL Full |  |
| Fractures Ontology | (Zhong et al., 2009); <br />(Zhong et al., 2008) | explicit specifications about fractures, including: properties, deformation mechanisms, formation and evolution. | OWL-DL | SWEET |
| Hydrogeology Ontology | (Tripathi and Babaie, 2008) |  |  | SWEET |
| StructuralGeoOntology | (Babaie et al., 2006) |  | UML |  |
| FractureGeoOntology | (Babaie et al., 2006) |  | UML | StructuralGeoOntology |
| FoliationGeoOntology | (Babaie et al., 2006) |  | UML | StructuralGeoOntology |
| FoldGeoOntology | (Babaie et al., 2006) |  | UML | StructuralGeoOntology |
| pluton object ontology | (Sinha et al., 2006) | A domain model for reasoning about processes affecting the rock record | UML; conceptual model |  |
| Volcano system ontology | (Fauziati and Watanabe, 2010) | Concepts organised as a modular representation of volcanic objects and processes | UML | - |
| Volcanic phenomena ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic material ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Magma ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic Hazard ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic vulnerability ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic hazard management ontology | (Fauziati and Watanabe, 2010) |  | UML |  | Volcanology |
| Volcano Ontology | (Fox et al., 2007); <br />(McGuinness et al., 2007b); <br />(Sinha et al., 2007) | Volcano classification | OWL-DL | SWEET |
| Plate-tectonics Ontology | (Fox et al., 2007); <br />(McGuinness et al., 2007b); <br />(Sinha et al., 2007) | Plate-tectonics classification | OWL-DL | SWEET |
| Petrology Ontology | (Shkotin et al., 2012) | A formal theory of petrology as a domain model | OWL-DL | - |
| Petroleum Basin ontology | (Nimmagadda et al., 2007) | Refers to the organisation and normalisation of geophysics data to ensure proper datum matching during analysis (namely, time-depth conversion) | - | - |
| Exploration ontology | (Nimmagadda et al., 2007) |  |  |  |
| Vertical Seismic Profile (VSP) ontology | (Nimmagadda et al., 2007) |  |  |  |
| Common Depth Point (CDP) ontology | (Nimmagadda et al., 2007) |  |  |  |
| CUAHSI discovery ontology V1.0 | (Piasecki and Beran, 2009); <br />(Beran and Piasecki, 2009) |  | SKOS; OWL-DL | - |
| Hierarchical classification of tectonic assemblages | (Struik and Quat, 2002) | Describes a schema for classifying lithological assemblages formed in tectonic environments | Hierarchical classificaton | NADM-C1 |
| Scheme for rock classification | (Struik et al., 2002) | Model for rock classification | Hierarchical classificaton | NADM-C1 |
| PetroGrapher | (Abel et al., 2004b) | Developed to illustrate visual tacit knowledge applied to petrographic analysis via rock descriptions | partonomy; sets and slots | - |
|  | (Abel et al., 2005); <br />(Abel et al., 2004a) |  |  |  |
| stratigraphy ontology | (Abel et al., 2012) | A formal vocabulary to encode stratigraphy of lithologic logs via sign/icon classification | - | - |
| Micropaleontology ontology | (Gary & Platon, 2010) | An ontology for Foraminifera that includes morphologic, taxonomic, biostratigraphic and environmental information | - | - |
| Gravity anomaly ontology | (Gates et al., 2007) |  |  |  |
| surface hydrology *concepts* | (Feng et al., 2005) | data model for surface hydrology processes | *is-a* hierarchies <br /> and parthood  | DOLCE |
| *not named* | (White et al. 2006) |  | OWL & RDF |  |
| Visual ontology | (Verney et al. 2008) | A visual concept ontology linking visual data with interpretations; links geologic objects to seismic data | - | - |

### task ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies / related |
| --------- | ---------------- | ---------------------------- | -------------------------- | -------------           |
| Event Ontology | (Mastella et al., 2007a) | Rules for reasoning about spatio-temporal relationships | - | Geo-ontology; Petrology ontology |
| EarthModel Ontology | (Mastella et al., 2007b) | For correlating spatial and temporal relations - as applied to 3D geologic models | - | Geo-ontology |
| Gravity ontology | (Salayandia et al., 2006) | For automatic contouring of gravity anomalies | OWL | GEON |
| Gravity-data ontology | (Gates et al., 2007) | Ontology for gravity data | OWL | - |
| GravityWDO | (Da Silva et al., 2007) | A gravity data processing ontology | OWL | - |
| Wings | (Gil et al., 2007) | Generates and runs earthquake science workflows in a distributed environment | OWL-DL | - |
|  | (Maechling et al., 2005) | Uses OWL as a validation mechanism for a Composition Analysis Tool | OWL | Wings |

### application ontologies
| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies / related |
| --------- | ---------------- | ---------------------------- | -------------------------- | -------------           |
| EPONT | (Malik et al., 2010) |  | UML; conceptual model | SUO; SWEET; NADM |
| Data and Ontology MAPPING (GEON) | (Lin and Ludäscher, 2004); <br />(Lin and Ludäscher, 2003) | Ontologies for data set registration and integration | OWL-DL | - |
| data model ontology | (Parekh et al., 2004) | Ontology to model data parameters -- identificaton, spatio-temporal extent, format, etc. | OWL | - |
| geoonto ontology | (Xiong et al., 2009) | An ontology to match Asian science terms to the geoscience world topic hierarchy (AGI thesaurus) | OWL | AGI Thesaurus |
| Geologic Ages | (Rainaud et al., 2008) | Semantic annotation for geologic knowledge and interpretations | OWL-DL | see Mastella et al. 2007b (double check) |
| Basic Geology | (Rainaud et al., 2008) | - | OWL-DL | see Mastella et al. 2007b (double check) |
| Geographical Terms | (Rainaud et al., 2008) | - | OWL-DL | see Mastella et al. 2007b (double check) |
| ESG ontology | (Pouchard et al., 2003) | Uses DublinCore to link metadata and filter data queries | OWL (may be DAML-OIL) | DublinCore |
| *Petrography ontology* (*structure not named*) | (Victoreti et al., 2007) | Ontology of petrographic descriptions and diagenetic interpretation | *knowledge graph* | PetroGrapher |
| Structural modelling ontology | (Zhu et al., 2009) | Created for conflict detection in structural interpretations |  | Geo-ontology |
| Data set Ontology | (Movva et al., 2005) | Extends ESML to integrating metadata; coupled with ontologies to allow applications to "use" science data | DAML-OIL; UML |  |
| event ontology | (Zhu et al., 2010) | Well surveillance application; uses OWL for events and SWRL for relationships between events of interest at the surface and sub-surface to monitor underperforming wells | OWL; SWRL | - |
| Virtual Data Archive (VDA) Ontology | (Keller et al., 2008) | Ontologies for metadata integration and translation without a unified metadata standard | RDF | - |
| BGC-DAAC Data Archive Ontology | (Keller et al., 2008) | - | RDF | - |
| STEWARDS Data Archive Ontology | (Keller et al., 2008) | - | RDF | - |
| ODISEES |  |  |  |  |

- - -
### Data Models
- Resource Description Framework ([RDF](https://www.w3.org/TR/owl2-overview/))

| name      | citation         | brief synopsis               | dependencies /<br /> related |
| --------- | ---------------- | ---------------------------- | ------------           |
| *geologic time scale* | (Ma et al., 2012) | Intended for annotating geologic time scales in geologic maps | - |


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
| [Rock.XML]() | (Jensen et al. 2016) |  |

- - -
### Thesauri or Taxonomies
| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [AGI thesaurus](http://www.americangeosciences.org/georef/thesaurus) |  |
| [EARTh]() | SKOS; (Albertoni et al. 2013) |
| *multi-lingual thesaurus* | Represented ordinal hierarchical structure of geological time scale for multiple languages to translate terms in online geologic maps (Ma et al. 2011) |
| CHRONOS | Integrating multiple geologic time scales using SKOS and GeoSciML (Fils et al. 2009) |

- - -
### Glossaries and Data Dictionaries
*Basic sources of geoscience terminology. There are many versions of resources that could populate this section.  These are provided for example only to illustrate overall comprehensiveness.*

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [Dictionary of Geologic Terms](https://books.google.co.uk/books?id=m4iFpN2SpkEC&printsec=frontcover&dq=editions:ISBN0385181019) | A hard copy dictionary. |
| [Dictionary of Geology & Earth Sciences](http://www.oxfordreference.com/view/10.1093/acref/9780199653065.001.0001/acref-9780199653065) | A hard copy dictionary. |
| [General Dictionary of Geology](https://alvathea.files.wordpress.com/2009/01/general-dictionary-of-geology.pdf) | A general dictionary of geology. |
| [Glossary of Geology](http://www.americangeosciences.org/pubs/glossary/) | Hard copy glossary. (Also available as a paid app on [iTunes](https://itunes.apple.com/us/app/glossary-of-geology/id398194234?mt=8) and [Google Play](https://play.google.com/store/apps/details?id=org.agiweb.glossaryofgeology&hl=en)) |
| [GSL Glossary of Terms](https://www.geolsoc.org.uk/ks3/gsl/education/resources/rockcycle/page3451.html) | The Geological Society's glossary of terms. |
| [AGU Index of Terms](http://onlinelibrary.wiley.com/doi/10.1029/EO067i039p00756/abstract) | Closed set of terms used by the American Geophysical Unioon (AGU) to categorize conference and publication keywords. |
| [Global Change Master Directory](http://gcmd.nasa.gov/learn/keywords.html) | Terms for tagging NASA's Earth Science data and services. |


## other relevant works
### Foundational ontologies
(explanation)

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| Science Knowledge Information ontology (SKIo) |  |
| Descriptive Ontology for Linguistic and Cognitive Engineering [(DOLCE)](http://www.loa.istc.cnr.it/old/DOLCE.html) |  |
| Basic Formal Ontology [(BFO)](http://ifomis.uni-saarland.de/bfo/) |  |
| COSMO  | see Pat Cassidy paper |

### Units and measurement
(explanation)

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [(QUDT)](http://www.qudt.org/) | (i.e. Quantities, Units, Dimensions and Data Types Ontologies) |
| O&M | (Cox) |
| O&M | (other) |
| O&M | (POSC supported...or maybe it was Energistics...check notes) |

### Geologic Time
*should this be separate?*

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
|  |  |

- - -
### Geoscience frameworks utilizing semantics
| name/group/project |  brief synopsis                                       |
| ----------         | ----------------------------------------------------  |
| GEOscience Network [GEON](http://geongrid.org/) |  |
| [Talkoot](http://miningsolutions.itsc.uah.edu/talkoot/) | see also [esipfed's page](http://wiki.esipfed.org/index.php/Talkoot:_Discover%2C_Tag%2C_Share%2C_and_Reuse_Collaborative_Science_Workflows) and [cite this](https://link.springer.com/article/10.1007/s12145-012-0094-y) |
| Terrestrial Ecosystem Research Network [(TERN)](http://www.tern.org.au/) |  |
| Long Term Ecological Research Network [(LTER Network)](https://lternet.edu/) |  |
| National Ecological Observatory Network [(NEON)](http://www.neonscience.org/) |  |
| [Mirador](http://mirador.gsfc.nasa.gov/cgi-bin/mirador/presentNavigation.pl?tree=project&CURRENT_CONTEXT=Projects) |  |
| Multi-sensor Data Synergy Advisor [(MDSA)](http://tw.rpi.edu/portal/MDSA) |  |
| [Noesis](http://noesis.itsc.uah.edu/) |  |
| [SESDI](http://sesdi.hao.ucar.edu/) |  |
| Virtual Solar-Terrestrial Observatory [(VSTO)](https://tw.rpi.edu//web/project/VSTO) | (ontologies as well as application)  |
| [SAM](http://miningsolutions.itsc.uah.edu/) |  |
| [DQSS](http://tw.rpi.edu/portal/DQSS) | (not sure about this one) |
| [AeroStat](http://tw.rpi.edu/portal/AeroStat) |  |

- - -
### Geoscience services
| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [British Geological Survey Vocabulary web service](http://www.bgs.ac.uk/data/vocabularies/home.html) | Vocabulary web service |
| [SISSVoc](http://www.sissvoc.info/) | the Spatial Information Services Stack Vocabulary Service (CITE) |
| OceanLink | (link; cite-Narock etal and Krishnadi et al) |
| [GeoLink](http://www.geolink.org/) | (CITE - Krishnadi 2015) ([Geolink Base ontology](http://schema.geolink.org/1.0/base/main.html) - in RDF) |

- - -
### Works in progress
*material that was culled from an online resource, but hasn't (to my knowledge) been published*

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [Spatial Data WG]() [(W3C sponsored)]() |  |
| DataONE sem-prov-design |  |
| ANU-Linked-Earth-Data ontology |  |
| RDA working groups |  |
| OGC |  |
| GTWG | working group for GeoSciML, EarthResourceML, ... vocabularies |
| others? |  |

- - -
A ***big*** thanks to [roomthily](https://github.com/roomthily) for suggesting I have a look at [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  lists.
