# awesome geoscience semantics
A curated list of geoscience semantic resources.
<br />

[![](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![](https://badges.gitter.im/geoscience-semantics/geoscience-semantics.github.io.svg)](https://gitter.im/geoscience-semantics/geoscience-semantics.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)[![](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=brandonnodnarb&url=http://www.geoscience-semantics.info&title=awesome_geoscience_semantics&language=en_GB&tags=geosciene,semantics,github&category=semantic_web)

This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit [CreativeCommons.org](https://creativecommons.org/licenses/by/4.0/).

- - -
## Preliminaries
#### on categorisation
The following geoscience semantic models are organised based (loosely) on the ***semantic spectrum*** (Obrst, 2003; 2010; Uschold and Gruninger, 2004; Smith and Welty, 2001; McGuinness, 2003; Uschold 2003!!), with particular focus on the high level categorisations described by Guarino and others (2009).  

The criteria distinguishing between *upper-level*, *domain*, *task*, and *application* ontologies after Guarino (1998 -- check also 1997(?), & Guarino and Giaretta 1995(?)), Obrst (2010), and Obrst and Cassidy (2011).

#### on order
The ontologies are listed by name, where available, in chronological order by publication year.  Where the structure was not given a name explicitly, a logical equivalent is given in *italics*.  Links on this page are to project homepages and/or repositories.

#### on multiplicity
Many papers discuss more than one ontology.  In most cases each ontology is referenced here.  In some cases multiple "ontologies" are mentioned in the publication, when in fact they are referring to multiple OWL files for one ontology.  There are also cases where an object model is discussed with a corresponding process model.  If possible (i.e. if there is enough information in the paper and/or documentation) these have been listed separately.  Further, there are ontological lineages of models -- i.e. an ontology was developed and in time/development became another structure.  When this is known (i.e. explicitly stated somewhere) the ontologies are connected via the "dependencies / related" field in the table.

- - -
## Logical Languages
- Web Ontology Language (OWL) -- the current, updated, version is [OWL 2](https://www.w3.org/TR/owl2-overview/); the initial version, referenced in many of the published works, is [OWL](https://www.w3.org/TR/2004/REC-owl-features-20040210/).  There is no distinction between versions, only expressivity where available.
- Knowledge Interchange Format ([KIF](http://logic.stanford.edu/kif/Hypertext/kif-manual.html))
- Common Logic ([CL](http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=39175))

### upper-level domain ontologies

| name          | citation  | brief synopsis               | expressivity <br />marker  |
| ------------- | --------- | ---------------------------- | -------------              |
| NADM-C1 | (NADM Steering Committee, 2004); <br />(Richard, 2006) | **North American Data Model, Conceptual Model 1.0**: Conceptual framework for top level geologic concepts & controlled vocabulary for geologic map data | UML |
| Geo-ontology | (Perrin et al., 2005) | An ontology to formalise structural geologist's expert knowledge in relation to computational 3D model assemblages--including interpretation & provenance | KIF |
| [SWEET](http://sweet.jpl.nasa.gov/) | (Raskin and Pan, 2005);<br />(Raskin, 2006) | **Semantic Web for Earth and Environmental Terminology**: Modular, self described "middle level" ontology which has become the *de facto* model for the Earth sciences.  More information is provided in the *notes section of this site.  | OWL-DL |

### domain ontologies

| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies / related |
| --------- | ---------------- | ---------------------------- | -------------              | -------------           |
[//]: # (2002)
| Hierarchical classification of tectonic assemblages | (Struik and Quat, 2002) | Describes a schema for classifying lithological assemblages formed in tectonic environments for thematically consistent queries across geologic databases | conceptual model; hierarchical classification | NADM-C1 |
| multihierarchical rock classification scheme | (Struik et al., 2002) | Rock classification based on three main rock properties -- composition, texture, and fabric -- for thematically consistent queries across geologic databases | conceptual model; hierarchical classificaton | NADM-C1 |
[//]: # (2004)
| Pluton Object Ontology | (Sinha et al., 2004; 2006) | A domain model for reasoning about concepts and properties associated with igneous rocks (including a discussion about process models) | UML; conceptual model | SWEET |
| PetroGrapher | (Abel et al., 2004a; 2004b; 2005) | Developed to support analysis in the petrographic domain, primarily visual and diagenetic analysis, using *K*-graphs (concept-attribute-value triples) in coordination with multiple DBs | partonomy; sets and slots | - |
| *surface hydrology concepts* | (Feng et al., 2004) | data model for surface hydrology concepts using *endurant* and *perdurant* for the semantics of processes | *is-a* hierarchies and parthood  | DOLCE |
[//]: # (2006)
| *eMinerals data handling* | (White et al. 2006) | The "ontology" described in the paper is simply provide a description of the property concept and link it to a dictionary reference | OWL & RDF | - |
| StructuralGeoOntology | (Babaie et al., 2006) | Preliminary conceptual model of a portion of a structural geology ontology.  Describes a modular approach alluding to other *subontologies* in the form of Lineation, Foliation, Fault, Joint, and several other structures for common concepts (based on figures 3-5) which would now likely be discussed as Ontology Design Patterns | UML | SWEET |
| FractureGeoOntology | (Babaie et al., 2006) | A *subontology* of the StructuralGeoOntology | UML | StructuralGeoOntology |
| FoldGeoOntology | (Babaie et al., 2006) | A *subontology* of the StructuralGeoOntology | UML | StructuralGeoOntology |
[//]: # (2007)
| Gravity anomaly ontology | (Gates et al., 2007) |  |  |  |
| Plate-tectonics Ontology | (Fox et al., 2007); <br />(McGuinness et al., 2007b); <br />(Sinha et al., 2007) | Plate-tectonics classification using plate boundary, lithosphere, etc. | OWL-DL | SWEET; GEON; VSTO |
| Volcano Ontology | (Fox et al., 2007); <br />(McGuinness et al., 2007b); <br />(Sinha et al., 2007) | Volcano classification by composition, tectonic setting, environmental setting, eruption type, activity, geologic setting, and landform | OWL-DL | SWEET; GEON; VSTO |
| Petroleum Basin ontology | (Nimmagadda et al., 2007) | Refers to the organisation and normalisation of geophysics data to ensure proper datum matching during analysis (namely, time-depth conversion) | - | - |
| Exploration Data ontology | (Nimmagadda et al., 2007; Nimmagadda & Dreher 2008) |  |  |  |
| Vertical Seismic Profile (VSP) ontology | (Nimmagadda et al., 2007; Nimmagadda & Dreher 2008) |  |  |  |
| Common Depth Point (CDP) ontology | (Nimmagadda et al., 2007; Nimmagadda & Dreher 2008) |  |  |  |
| Seismic domain ontology | (Nimmagadda et al., 2007; Nimmagadda & Dreher 2008) |  |  |  |
| Well-base domain ontology | (Nimmagadda et al., 2007; Nimmagadda & Dreher 2008) |  |  |  |
| **2008** | |
[//]: # (2008)
| Fractures Ontology | (Zhong et al., 2008); <br />(Zhong et al., 2009) | Explicit specifications about the deformation mechanisms affecting geologic structures, including properties as indicators | OWL-DL | SWEET & DOLCE |
| Hydrogeology Ontology | (Tripathi and Babaie, 2008) | Extends (and corrected) portions of SWEET adding concepts and properties related to ground water categories and definitions | OWL | SWEET |
| Visual ontology | (Verney et al. 2008) | A visual concept ontology linking visual data with interpretations; links geologic objects to seismic data | - | - |
| **2009** | |
[//]: # (2009)
| CUAHSI discovery ontology V1.0 | (Piasecki and Beran, 2009); <br />(Beran and Piasecki, 2009) |  | SKOS; OWL-DL | - |
| **2010** |
[//]: # (2010)
| Basin Ontology | (Whitehead et al., 2010); <br />(Everett et al., 2011) | Describes the objects, processes and properties as they relate to the basin formation process | OWL Full | - |
| Magma ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Micropaleontology ontology | (Gary & Platon, 2010) | An ontology for Foraminifera that includes morphologic, taxonomic, biostratigraphic and environmental information | - | - |
| Volcano system ontology | (Fauziati and Watanabe, 2010) | Concepts organised as a modular representation of volcanic objects and processes | UML | - |
| Volcanic phenomena ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic material ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic Hazard ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic vulnerability ontology | (Fauziati and Watanabe, 2010) |  | UML | Volcano system ontology |
| Volcanic hazard management ontology | (Fauziati and Watanabe, 2010) |  | UML |  | Volcanology |
| **2011** | |
[//]: # (2011)
| Geological Time Ontology | (Perrin et al., 2011) |  | Conceptual Model; OWL | Geo-ontology |
| Geological Dating Ontology | (Perrin et al., 2011) |  | Conceptual Model: OWL | Geo-ontology |
| ** 2012** | |
[//]: # (2012)
| Petrology Ontology | (Shkotin et al., 2012) | A formal theory of petrology as a domain model | OWL-DL | - |
| stratigraphy ontology | (Abel et al., 2012) | A formal vocabulary to encode stratigraphy of lithologic logs via sign/icon classification | - | - |

### task (or process) ontologies

| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies / related |
| --------- | ---------------- | ---------------------------- | -------------------------- | -------------           |
[//]: # (2005)
| *expert validation tool* | (Maechling et al., 2005) | Uses OWL as a validation mechanism for a Composition Analysis Tool | OWL | Wings |
[//]: # (2006)
| Gravity ontology | (Salayandia et al., 2006) | For automatic contouring of gravity anomalies | OWL | GEON |
[//]: # (2007)
| Event Ontology | (Mastella et al., 2007a) | Rules for reasoning about spatio-temporal relationships | - | Geo-ontology; Petrology ontology |
| EarthModel Ontology | (Mastella et al., 2007b) | For correlating spatial and temporal relations - as applied to 3D geologic models | - | Geo-ontology |
| Gravity-data ontology | (Gates et al., 2007) | Ontology for gravity data | OWL | - |
| GravityWDO | (Da Silva et al., 2007) | A gravity data processing ontology | OWL | - |
| Wings | (Gil et al., 2007) | Generates and runs earthquake science workflows in a distributed environment | OWL-DL | - |

### application ontologies

| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependencies / related |
| --------- | ---------------- | ---------------------------- | -------------------------- | -------------           |
[//]: # (2003)
| ESG ontology | (Pouchard et al., 2003) | Uses DublinCore to link metadata and filter data queries | OWL (may be DAML-OIL) | DublinCore |
[//]: # (2004)
| Data and Ontology MAPPING (GEON) | (Lin and Ludäscher, 2004); <br />(Lin and Ludäscher, 2003) | Ontologies for data set registration and integration | OWL-DL | - |
| data model ontology | (Parekh et al., 2004) | Ontology to model data parameters -- identificaton, spatio-temporal extent, format, etc. | OWL | - |
[//]: # (2005)
| Data set Ontology | (Movva et al., 2005) | Extends ESML to integrating metadata; coupled with ontologies to allow applications to "use" science data | DAML-OIL; UML |  |
[//]: # (2007)
| *Petrography ontology* (*structure not named*) | (Victoreti et al., 2007) | Ontology of petrographic descriptions and diagenetic interpretation | *knowledge graph* | PetroGrapher |
[//]: # (2008)
| Geologic Ages | (Rainaud et al., 2008) | Semantic annotation for geologic knowledge and interpretations | OWL-DL | see Mastella et al. 2007b (double check) |
| Basic Geology | (Rainaud et al., 2008) | - | OWL-DL | see Mastella et al. 2007b (double check) |
| Geographical Terms | (Rainaud et al., 2008) | - | OWL-DL | see Mastella et al. 2007b (double check) |
| Virtual Data Archive (VDA) Ontology | (Keller et al., 2008) | Ontologies for metadata integration and translation without a unified metadata standard | RDF | - |
| BGC-DAAC Data Archive Ontology | (Keller et al., 2008) | - | RDF | - |
| STEWARDS Data Archive Ontology | (Keller et al., 2008) | - | RDF | - |
[//]: # (2009)
| geoonto ontology | (Xiong et al., 2009) | An ontology to match Asian science terms to the geoscience world topic hierarchy (AGI thesaurus) | OWL | AGI Thesaurus |
| Structural modelling ontology | (Zhu et al., 2009) | Created for conflict detection in structural interpretations |  | Geo-ontology |
[//]: # (2010)
| event ontology | (Zhu et al., 2010) | Well surveillance application; uses OWL for events and SWRL for relationships between events of interest at the surface and sub-surface to monitor underperforming wells | OWL; SWRL | - |
| EPONT | (Malik et al., 2010) |  | UML; conceptual model | SUO; SWEET; NADM |
[//]: # (20XX)
| [ODISEES](http://cmdb.nccs.nasa.gov:8080/odisees/) | (Rutherford et al., 2015) |  |  |  |


- - -
## Data Models
- Resource Description Framework ([RDF](https://www.w3.org/TR/owl2-overview/))

| name      | citation         | brief synopsis               | dependencies /<br /> related |
| --------- | ---------------- | ---------------------------- | ------------ |
| CHRONOS | (Fils et al 2006; 2009) | (RDF and SKOS) Integrating multiple geologic time scales | GeoSciML |
| *geologic time scale* | (Ma et al., 2012) | Intended for annotating geologic time scales in geologic maps | - |


- - -
## Thesauri or Taxonomies
| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [AGI thesaurus](http://www.americangeosciences.org/georef/thesaurus) |  |
| *multi-lingual thesaurus* | Represented ordinal hierarchical structure of geological time scale for multiple languages to translate terms in online geologic maps (Ma et al. 2011) |
| [EARTh]() | SKOS; (Albertoni et al. 2013) |


- - -
## Glossaries and Data Dictionaries
*Basic sources of geoscience terminology. There are many versions of resources that could populate this section.  These are provided for example only to illustrate overall comprehensiveness.*

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| [Dictionary of Geologic Terms](https://books.google.co.uk/books?id=m4iFpN2SpkEC&printsec=frontcover&dq=editions:ISBN0385181019) | A hard copy dictionary. |
| [Dictionary of Geology & Earth Sciences](http://www.oxfordreference.com/view/10.1093/acref/9780199653065.001.0001/acref-9780199653065) | A hard copy dictionary. |
| [General Dictionary of Geology](https://alvathea.files.wordpress.com/2009/01/general-dictionary-of-geology.pdf) | A general dictionary of geology. |
| [Glossary of Geology](http://www.americangeosciences.org/pubs/glossary/) | Hard copy glossary. (Also available as an app on [iTunes](https://itunes.apple.com/us/app/glossary-of-geology/id398194234?mt=8) and [Google Play](https://play.google.com/store/apps/details?id=org.agiweb.glossaryofgeology&hl=en)) |
| [GSL Glossary of Terms](https://www.geolsoc.org.uk/ks3/gsl/education/resources/rockcycle/page3451.html) | The Geological Society's glossary of terms. |
| [AGU Index of Terms](http://onlinelibrary.wiley.com/doi/10.1029/EO067i039p00756/abstract) | Closed set of terms used by the American Geophysical Unioon (AGU) to categorize conference and publication keywords. |
| [Global Change Master Directory](http://gcmd.nasa.gov/learn/keywords.html) | Terms for tagging NASA's Earth Science data and services. |


## Works in progress

| name/group/project      |  brief synopsis                                       |
| ----------------        | ----------------------------------------------------  |
| W3C Spatial Data Working Group (SDWG) |  |
| DataONE sem-prov-design |  |
| [ANU-Linked-Earth-Data ontology](https://github.com/ANU-Linked-Earth-Data/ontology) |  |
| RDA working groups | there are several...list them here. |
| Open Geospatial Consortium (OGC) | many |
| Geologic Terminology Working Group (GTWG) | working group for GeoSciML, EarthResourceML, ... vocabularies.  sponsored by International... |
| Oceanography and geospatial ontology | from a blog post? |
| others? |  |
| ToolMatch |  |

- - -
A ***big*** thanks to [roomthily](https://github.com/roomthily) for suggesting I have a look at [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  lists.

<br /><br />
*"That rug really tied the room together."*<br />
-[The Dude](http://www.imdb.com/character/ch0003518/?ref_=tt_cl_t1)
