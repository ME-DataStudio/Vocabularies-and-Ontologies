# SPARQL course #

## Goal ##
We want to convert a Thesaurus into a Knowledge base and add the data from RDW Open data. The red circles in pictures down below are coming from the Thesaurus. The green circles come from RDW Open data.

![image](https://user-images.githubusercontent.com/75776348/134909745-62542b9e-6a81-4d09-bfe7-82a3c31270fc.png)

![image](https://user-images.githubusercontent.com/75776348/134910421-f9f76408-945b-4568-a8ed-aba507fd0551.png)


## Start ##
We start with the preliminaries:
- Fuseki server: Download de Jena Fuseki server from https://jena.apache.org/download/index.cgi ( at time of writing version 4.2.0 ) and start fuseki-server.bat from the command line. Fuseki GUI is available at http://localhost:3030.  
- Download the RDW Thesaurus from https://github.com/ME-DataStudio/Vocabularies-and-Ontologies/blob/main/VoertuigBegrippen.ttl. One can see a readable version at begrippenXL https://www.begrippenxl.nl/rdw/nl/  
- Within Fuseki open __manage datasets__ tab and click __add new dataset__  
- Click on the __dataset__ tab and then click the __add data__ button
- Then click on __+ select files...__ and browse to the folder where you downloaded the RDW Thesaurus
  
  
Now we can start the conversion of the RDW Thesaurus into an ontology with the help of SPARQL.  
  
With rq1 in this folder we can see which ConceptSchemes are within the RDW Thesaurus and what label it has.

## Create the ontology from Thesaurus ##

With rq2 we convert the thesaurus into a basic ontology. Changing the concepts into classes.
