# geoscience ontologies
<br />

[//]: # (this site is meant to serve as a companion piece to a review paper currently under review -- a draft of the paper can be found on arxiv.org_linky)

[![](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![](https://badges.gitter.im/geoscience-semantics/geoscience-semantics.github.io.svg)](https://gitter.im/geoscience-semantics/geoscience-semantics.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The contents of this site is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit [CreativeCommons.org](https://creativecommons.org/licenses/by/4.0/).

- - -
### upper-level domain ontologies

| name             | citation | brief synopsis            | expressivity <br />marker  |
| ---------------- | -------- | ------------------------- | -----------             |
| NADM-C1 | [10-12] | **North American Data Model, Conceptual Model 1.0**: Conceptual framework for top level geologic concepts & controlled vocabulary for geologic map data | UML |
| Geo-ontology | [13] | An ontology to formalise structural geologist's expert knowledge in relation to computational 3D model assemblages--including interpretation & provenance | KIF |
| [SWEET](http://sweet.jpl.nasa.gov/) | [14-16] | **Semantic Web for Earth and Environmental Terminology**: Modular, self described "middle level" ontology which has become the *de facto* model for the Earth sciences.  More information is provided in the *notes section of this site.  | OWL-DL |

### domain ontologies

| name      | citation | brief synopsis                        | expressivity <br />marker  |  dependency<br />or related |
| --------- | -------- | ------------------------------------- | ------------- | ------------- |
[//]: # (2002)
| Hierarchical classification of tectonic assemblages | [17] | Describes a schema for classifying lithological assemblages formed in tectonic environments for thematically consistent queries across geologic databases | conceptual model; hierarchical classification | NADM-C1 |
| multihierarchical rock classification scheme | [18] | Rock classification based on three main rock properties -- composition, texture, and fabric -- for thematically consistent queries across geologic databases | conceptual model; hierarchical classificaton | NADM-C1;<br /> GEON |
[//]: # (2004)
| Pluton Object Ontology | [19-20] | A domain model for reasoning about concepts and properties associated with igneous rocks (including a discussion about process models) | UML; conceptual model | SWEET |
| petrographic ontology | [21-23, 60] | Developed to support analysis in the petrographic domain, primarily visual and diagenetic analysis, using *K*-graphs (concept-attribute-value triples) in coordination with multiple DBs | partonomy; sets and slots | PetroGrapher |
| *surface hydrology concepts* | [24] | data model for surface hydrology concepts using *endurant* and *perdurant* for the semantics of processes | *is-a* hierarchies and parthood  | DOLCE |
[//]: # (2006)
| *eMinerals data handling* | [25] | The "ontology" described in the paper is simply provide a description of the property concept and link it to a dictionary reference | OWL & RDF | - |
| StructuralGeoOntology | [26] | Preliminary conceptual model of a portion of a structural geology ontology.  Describes a modular approach alluding to other *subontologies* in the form of Lineation, Foliation, Fault, Joint, and several other structures for common concepts (based on figures 3-5) which would now likely be discussed as Ontology Design Patterns | UML | SWEET |
| FractureGeoOntology | [26]) | A *subontology* of the StructuralGeoOntology | UML | StructuralGeoOntology |
| FoldGeoOntology | [26] | A *subontology* of the StructuralGeoOntology | UML | StructuralGeoOntology |
[//]: # (task)
| Gravity ontology | [27,28] | Describes gravity data types and processing methods for automatic contouring of gravity anomalies (i.e simple to complex Bouguer anomalies) | OWL | GEON |
[//]: # (2007)
[//]: # (task)
| EarthModel Ontology | [29] | The EarthModel ontology describes the the spatio-temporal relationships between geologic objects, geologic events, geological models, and geological assemblages as a mechanism to describe entities like a *formation*; designed as a mechanism to integrate concepts currently relevant in reservoir modelling; an extension of [13] | - | Geo-ontology;<br /> Event Ontology |
[//]: # (task)
| GeologicalEvent Ontology | [30,29] | A general ontology of events applied to spatio-temporal reasoning in the geosciences; could be used to delineate sequences (i.e. diagenetic paragenesis) or automatic reconstruction of lithologic assemblages | - | Geo-ontology;<br /> PetroGrapher;<br /> *Petrology Ontology* |
| Gravity data ontology | [31] | An ontology meant to capture seismic data types in the form of field observations, location information (of point data) and derived data products as well as the methods and products (outputs) associated with the data (i.e. in this sense, provenance) | OWL | WDO; WDO-It! |
[//]: # (task)
| GravityWDO | [27,32] | A gravity data processing ontology created using the WDO-It method which instantiates specifications from Model-Based Workflows (MBWs) to ontological components (OWL) | OWL | GEON; Gravity Ontology |
| Plate-tectonics Ontology | [33-35] | Plate-tectonics classification using plate boundary, lithosphere, etc. | OWL-DL | SWEET; GEON; VSTO |
| Volcano Ontology | [33-35] | Volcano classification by composition, tectonic setting, environmental setting, eruption type, activity, geologic setting, and landform | OWL-DL | SWEET; GEON; VSTO |
| Petroleum Basin ontology | [36] | Refers to the organisation and normalisation of geophysics data to ensure proper datum matching during analysis (namely, time-depth conversion) | - | - |
| Exploration Data ontology | [36,37] | Broad view of exploration data types used in seismic surveys and analysis | - | - |
| Common Depth Point (CDP) ontology | [36,37] | Aligns each depth point, including variation, with other depth points on the vertical and horizontal axes to help with grid alignment | - | Seismic domain ontology; Well-base domain ontology |
| Seismic domain ontology | [36,37] | Provides a supertype with temporal properties and structure to account for different domains of data representation -- i.e.  CDP, COP (common offset point) dimension, CSP (common source point) dimension and CRP (common receiver point) dimension  | - | CDP |
| Vertical Seismic Profile (VSP) ontology | [36,37] | Appears to minimize effects of air waves, ground roll, and diffractions to increase signal to noise ratio during post-processing | - | - |
| Well-base domain ontology | [36,37] | Describes relationships of wells -- id, formation top, depth and horizon, with the Seismic domain ontology | - | Seismic domain ontology |
[//]: # (2008)
|Basic Geology ontology | [38] | Describes geologic objects, units and boundaries, with events as processes at a high level of abstraction  | - | GeoSciML |
| Fractures Ontology | [39,40] | Explicit specifications about Faults, Folds, and Fractures as well as the deformation mechanisms, including properties as indicators, affecting geologic structures in the upper crust of the Earth | OWL-DL | SWEET; DOLCE |
| Hydrogeology Ontology | [41] | Extends (and corrected) portions of SWEET adding concepts and properties related to ground water categories and definitions | OWL | SWEET |
| Visual ontology | [42] | A visual concept ontology which links geologic objects with visual seismic attributes through defining and formalising visual geologic attributes | - | - |
[//]: # (2009)
| CUAHSI discovery ontology V1.0 | [43,44] | A *layered* ontology focusing on tagging compounds, variables and terms associated with hydrology, many of which are typical found on NWIS and STORET | SKOS; <br />OWL-DL | - |
[//]: # (2010)
| Basin Ontology | [45,46] | Describes the concepts describing the basin formation process from earth surface material to source rock, seal, and reservoir | OWL Full | - |
| Magma ontology | [47] | Focuses on physical and chemical properties and processes of magma as it relates to eruptions | UML | Volcano system ontology |
| Micropaleontology ontology | [48] | An ontology for Foraminifera that includes morphologic, taxonomic, biostratigraphic and environmental information | - | - |
| Volcano system ontology | [47] | Concepts organised as a modular representation of volcanic objects and processes of a volcanic system -- including material, event conditions, setting, and environmental parameters | UML | - |
| Volcanic phenomena ontology | [47] | Internal, external and environmental concepts and properties organised by three top level states: pre-eruption, syn-eruption, and post-eruption | UML | Volcano system ontology |
| Volcanic material ontology | [47] | Solid and fluid material associated with a volcano during and after an eruption | UML | Volcano system ontology |
| Volcanic Hazard ontology | [47] | Describes the physical characteristics of an eruption as well as secondary hazards during dormant periods | UML | Volcano system ontology |
| Volcanic vulnerability ontology | [47] | Describes the social, economic and environmental concepts related to volcanic eruptions | UML | Volcano system ontology |
| Volcanic hazard management ontology | [47] | Describes pre-eruptive concepts like preparation and outreach to syn and post eruptive actions and protocol | UML | Volcano system ontology |
[//]: # (2011)
| Geological Time Ontology | [49] | Describes the hierarchy of geological periods as they appear in stratigraphical time scales and corresponds between time scales based on fossils or absolute age | Conceptual Model; OWL | Geo-ontology;<br />GeoSciML |
| Geological Dating Ontology | [49] | Describes the main characteristics of geologic dating by absolute dating and relative methods using stratigraphic scales by linking between the Geological Time ontology and of the Basic Geology ontology | Conceptual Model: OWL | Geo-ontology;<br />Geological Time Ontology<br />Basic Geology ontology<br />GeoSciML |
[//]: # (2012)
| Petrology Ontology | [50] | A formal theory of petrology using axioms, definitions and theorems | OWL-DL; FOL | - |
| *Stratigraphy ontology* | [51] | A formal vocabulary to encode detailed descriptions about sedimentary structure and textures of depositional facies via outcrops and lithologic logs | - | - |
[//]: # (2013)
[//]: # (2014)
| [Sea Ice ontology](https://nsidc.org/ssiii/ontology.html) | [52] | Part of "WMO ontologies"--based on WMO nomenclature; top level ontology (ODP) for describing part of the physical characteristics of ice, as it pertains to a shipping forecast | OWL | Egg ontology |
| [Forms of Ice ontology](https://nsidc.org/ssiii/ontology.html) | [52] | Part of "WMO ontologies"--based on WMO nomenclature; describes ice forms | OWL | Sea Ice ontology |
| [Ice of Land origin ontology](https://nsidc.org/ssiii/ontology.html) | [52] | Part of "WMO ontologies"--based on WMO nomenclature; describes types of ice of land origin now found in the sea | OWL | Forms of Ice ontology |
[//]: # (task)
| [Sea Ice Concentration ontology](https://nsidc.org/ssiii/ontology.html) | [52] | Part of "WMO ontologies"--based on WMO nomenclature; describes concentration of ice now in the ocean | OWL | Sea Ice ontology |
[//]: # (task)
| [Sea Ice Development ontology](https://nsidc.org/ssiii/ontology.html) | [52] | Part of "WMO ontologies"--based on WMO nomenclature; describes stages of development for sea ice | OWL | Sea Ice ontology |
| [Egg ontology](https://nsidc.org/ssiii/ontology.html) | [52] | A "bridge" ontology linking the Sea Ice ontology with the Sigrid 3 ontology as it represents the physical state of sea ice as depicted on ice charts | OWL | Sigrid3 ontology;<br /> Sea Ice ontology |
| [Sigrid 3 ontology](https://nsidc.org/ssiii/ontology.html) | [52] | Formal representation of the Egg code and shapefile information portion of a Sigrid 3 data file | OWL | Egg ontology |
[//]: # (2015)
[//]: # (2016)
[//]: # (2017)


### application ontologies

| name      | citation         | brief synopsis               | expressivity <br />marker  |  dependency<br />or related |
| --------- | ---------------- | ---------------------------- | -------------------------- | -------------           |
[//]: # (2003)
| ESG *ontology* | [53] | Describes identity, scientific purpose, datasets, and other concepts and corresponding relationships as they are related to the Earth Systems Grid (ESG) metadata elements | DAML+OIL | DublinCore |
[//]: # (2004)
| *GEON data ontologies* | [54,55] | Ontologies for data set registration and integration as an underlying component of the GEOscience Network (GEON) | OWL-DL | - |
| Data Model ontology | [56] | The ontology provides a standard vocabulary for dataset registration---i.e. identification, spatio-temporal extent, format, etc. | OWL | - |
[//]: # (2005)
| Data set ontology | [57] | Models data set properties such as: projection; spatial, vertical, and temporal values | DAML-OIL; UML | ESML;<br />subsetting ontology |
| subsetting ontology | [57] | Describes rules for subsetting datasets via spatial or temporal dimensions; spatial subsetting can be horizontal (Lat, Long) or vertical (measured value) | DAML-OIL; UML | ESML;<br />Data set ontology |
[//]: # (2006)
| CHRONOS thesauri | [58,59] | CHRONOS uses taxonomic models of timescale (i.e. GeoSciML time) and thesauri (i.e. phylogeny) as a translation schema to integrate multiple datasets and services | RDF; SKOS; Microformats | GML; GeoSciML; DublinCore; FOAF |
[//]: # (2007)
[//]: # (| ESIP data ontology | [61] |  |  |  |)
| Wings | [62] | Generates and runs workflows (computational) against data sets using semantically described science applications in a distributed computational environment | OWL-DL | - |
[//]: # (2008)
[//]: # ( see Rainaud et al. 2008 for the next three from 63---double check; see also Mastella et al 2007 -- # 29 )
| Geological Time ontology | [63,29] | for defining and managing geologic ages | OWL-DL | Geo-ontology |
| Basic Geology ontologies | [63,29] | Ontologies for describing "basic" geologic constructs such as: unit, lithology, processes and boundaries | OWL-DL | Geo-ontology |
| GeoLocalization ontology | [63,29] | geographical terms ontology; utilising geopolitical boundaries and nomenclature | OWL-DL | - |
| Virtual Data Archive (VDA) Ontology | [64] | An ontology serving as an upper-level ontology, or cross-walk, consisting of common concepts across source data archive (SDA) ontologies.  The two SDA ontologies described are the STEWARDS ontology and BGC-DAAC ontology | RDF | - |
| BGC-DAAC Data Archive Ontology | [64] | Ontology derived directly from the metadata language for this specific data archive | RDF | VDA ontology |
| STEWARDS Data Archive Ontology | [64] | Ontology derived directly from the relational database schema for this specific data archive | RDF | VDA ontology |
[//]: # (2009)
| geoonto ontology | [65] | An ontology to map Asian science terms to the geoscience world topic hierarchy (AGI thesaurus) | OWL | AGI Thesaurus |
| Structural modelling ontology | [66] | Created to detect conflicts in geologist's structural interpretations of data |  | Geo-ontology |
[//]: # (2010)
| event ontology | [67] | Well surveillance application; uses OWL to model events and SWRL to capture relationships between events of interest at the surface and sub-surface to monitor underperforming wells | OWL; SWRL | - |
| EPONT | [68] | **Earth and Planetary ONTology**; A domain level application ontology to connect geoscience ontologies (primarly SWEET) and XML schemata via registration in an effort to interoperate information from heterogeneous geologic data sets | UML; conceptual model | SUO; SWEET; NADM; GEON |
[//]: # (2012)
| GTS ontology | [69] | **geologic time scale ontology**; Structure created to annotate geologic time as depicted in geologic maps | RDF | - |
[//]: # (2014)
[//]: # (2015)
| [ODISEES](http://cmdb.nccs.nasa.gov:8080/odisees/) ontology | [70] | Classifies measured phenomena of primarily atmospheric data via their attributed variables--as described in ASDC data | RDF | - |
| [Geolink Base ontology](http://schema.geolink.org/1.0/base/main.html) | [71] | GeoLink is a set of content patterns (ODPs) developed to model a data provider's discovery facet. These include cruise, person, organization, dataset, funding award, program, etc. (was previously OceanLink [72]) | RDF | - |