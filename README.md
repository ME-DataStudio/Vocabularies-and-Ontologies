# Vehicle Terms #  

This repository is a running project to build vehicle ontology.  

First is Voertuig Open Data. Starting with SKOS vocabularies for GekentekendVoertuig, Typegoedkeuring, Keuringen, ErkendBedrijf, ProductCatalogus and TerugroepActies.

All SKOS definitions in one file: voertuigbegrippen.ttl. Published on https://www.begrippenxl.nl/rdw/nl/

# Ontologies #
From the SKOS file an ontology is made with SPARQL (see workshop SPARQL queries rq2 and rq3) for Erkende Bedrijven (erkendbedrijf.owl).

In this repository I used fuseki as a triplestore in [Virtuoso](https://github.com/ME-DataStudio/virtuoso/) I am starting to use Openlinksw Virtuoso.

# Queries.ttl #  
In Virtuoso it is not possible to save SPARQL and SQL queries with the default open-source installation/docker container. So I started queries.ttl to store SPARQL queries as linked-data in Virtuoso. 

