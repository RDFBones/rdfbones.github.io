---
layout: page
title: RDFBones
---



## Why RDFBones?
RDFBones serves as a framework for standardised osteological research data in biological anthropology. Coding data with RDFBones helps to achieve the folowing aims:
Enrich osteological research data with information on research design, circumstances of analyses, executing researchers, property information etc.
Prepare osteological research data for long-term storage and subsequent reuse
Merge osteological research data coded according to different standards
Release subsequent versions of datasets
What is RDFBones?
RDFBones is an ontology describing osteological research data as produced in biological anthropology. It is built on the following domain ontologies from which it borrows most of its elements:

* [Ontology for Biomedical Investigations (OBI)](http://obi-ontology.org/) \\
	Scientific investigations
* [Foundational Model of Anatomy (FMA)](http://si.washington.edu/projects/fma) \\
  Human anatomy
* [CIDOC Conceptual Reference Model (CIDOC CRM)](http://cidoc-crm.org/) \\
  Collections
* [GeoNames Ontology](http://www.geonames.org/ontology/documentation.html)\\
  Geography
* [Bibliographic Ontology (BIBO)](http://www.bibliontology.com/) \\
Documents


Elements from these Ontologies are combined into RDFBones to provide a resource for coherent description of materials, methods, research processes and outputs in biological anthropology.
RDFBones applies the [Resource Description Framework (RDF)](https://www.w3.org/RDF/), a standard model that was originally developed to amalgamate disparate data on the internet. It has been applied in many fields, including describing research data in many life sciences.


## How Does RDFBones Work?
RDFBones consists of a core ontology that can be adapted to support all kinds of research by writing additional ontologies, referred to as *'extensions'*.


The **core ontology** describes how osteological research is conducted in general, what materials are commonly investigated, what kinds of methods are employed and which instruments are available. The core ontology is developed by the RDFBones project group with input from the scientific community.

**Extensions** describe specific research topics and methods. To do this they can introduce new concepts describing materials and methods that are not covered by the core ontology; but in doing so they need to define them as a more concrete example of a general term available in the core ontology. As a consequence, all extensions stay within the framework of the core ontology and relate to some elements there. Extensions are developed by individual scientists, either for their own research or on behalf of some research institution.

The core ontology, extensions, and also research data coded according to some extension, are available as RDF code in simple text files. They can be opened, read and edited with any text editor. Additionally, there are special editors for RDF data that facilitate this work and can also be used to code research data according to extensions. As text files are among the most simple and secure formats they make a good basis for long-term storage.

Queries on RDF data can be performed through specialised software known as semantic reasoning engines. Several of these reasoners can be downloaded and installed on desktop computers for free. There, they can evaluate data directly from text files that are saved on the local hard drive. This is the entire infrastructure needed for typical osteological studies. Large-scale projects rely on dedicated RDF databases known as triple stores. So RDF information technology supports osteological research on various scales, from a simple PhD project up to centralised research data platforms.

As the RDF standard is an open format it is not bound to a certain software provider and supported by several software solutions. Semantic reasoners can be used to convert RDF information into tabular data to be handled by relational databases. But as this conversion removes all semantic relations defined in the original dataset, this is only advisable for immediate analyses. RDF is a suitable format for data archival from were information can be broken down for processing in less sophisticated systems.
These qualities of semantic data modelling lets researchers provide their data for reuse in other studies while keeping control about the methods employed by them.


## How Can RDFBones Be Used?

The flexibility of semantic research data modelling allows for a wide range of application leaving space for researchers' creativity.
Osteologists can use RDFBones to document their research and submit resulting data.
Scientists publish their newly invented methods as RDFBones extensions to facilitate implementation in research.
Researchers can use RDFBones to pool osteological data from earlier investigations to conduct large-scale analyses. These can follow data models that deviate from the models according to which the data were originally established.
Research institutions can use RDFBones to compile large amounts of research data over time without being forced to stick to the same data structures. RDFBones provides a basis for data stewardship and curation through correction of erroneous information, evaluation by re-investigation of material etc.
Osteological research collection can use RDFBones to minimise damage to their specimen by tracking skeletal inventories over time and avoid handling of material by providing existing research data.


Like many other software applications, the statistical programming language R provides packages for interacting with RDF data. This allows researchers to write packages that automatically process data from specific extensions.


Contact us to learn how RDFBones can help your research.
