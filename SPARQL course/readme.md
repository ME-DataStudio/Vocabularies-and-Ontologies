# SPARQL course #

We stat with the preliminaries:
- Fuseki server: Download de Jena Fuseki server from https://jena.apache.org/download/index.cgi ( at time of writing version 4.2.0 ) and start fuseki-server.bat from the command line. Fuseki GUI is available at http://localhost:3030.  
- Download the RDW Thesaurus from https://github.com/ME-DataStudio/Vocabularies-and-Ontologies/blob/main/VoertuigBegrippen.ttl. One can see a readable version at begrippenXL https://www.begrippenxl.nl/rdw/nl/  
- Within Fuseki open __manage datasets__ tab and click __add new dataset__  
- Click on the __dataset__ tab and then click the __add data__ button
- Then click on __+ select files...__ and browse to the folder where you downloaded the RDW Thesaurus
  
  
Now we can start the convert the RDW Thesaurus into an ontology with the help of SPARQL.  
  
With rq1 in this folder we can see which Concept Schemes are within the RDW Thesaurus and the label it has.

