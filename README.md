# ontology_assignment3

## sparql endpoints
    - https://www.w3.org/wiki/SparqlEndpoints
    - https://wiki.nci.nih.gov/display/VKC/SPARQL+Endpoints+List+of+URLs
    
### query format 
 - https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service
 
 - to query data url should be : https://{sparqlendpoint}?query={sparql query}
 - ex : https://dbpedia.org/sparql?query=select distinct ?Concept where {?a a ?Concept} LIMIT 100
 - specifying the return format : add parameter format={xml/json/html} in url or specify in header  
