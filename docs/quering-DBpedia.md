

## Wikimedia / DBpedia properties 

Source: [How I can know the equivalent DBPedia and Wikidata properties](http://stackoverflow.com/questions/39850833/how-i-can-know-the-equivalent-dbpedia-and-wikidata-properties)
```
PREFIX       owl:  <http://www.w3.org/2002/07/owl#>
PREFIX      rdfs:  <http://www.w3.org/2000/01/rdf-schema#>

SELECT Distinct ?WikidataProp ?DBpediaProp  
WHERE
  {
    ?DBpediaProp  owl:equivalentProperty  ?WikidataProp .
                  FILTER ( CONTAINS ( str(?WikidataProp) , 'wikidata' ) ) .
 
  }
ORDER BY  ?DBpediaProp
```
