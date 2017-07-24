# schemaOrg-bdMaps

Mapping semantic between [Schema.Org](http://schema.org) and main Wikipedia-foundation vocabularies, [Wikidata](http://wikidata.org) and DBpedia. Complements:

* [Quering-Wikidata and installing SQL tool](docs/quering-Wikidata.md)
* [Wikidata state summarizations](docs/reports.md)


Our focus is only the "core ontology" of SchemaOrg. Today, as stated by [schema.org/docs](http://schema.org/docs/schemas.html) of version 3.2,

> The core vocabulary currently consists of 589 Types, 860 Properties, and 114 Enumeration values.

So, there are **~1600 items to be mapped** (~600 types + ~900 properties + ~100 values), in both Wikidata-sources code and SchemaOrg-sources.

## Goals
The first aim was expressed as SchemaOrg's [issue-280](https://github.com/schemaorg/schemaorg/issues/280), *"Schema.org should have mappings to Wikidata terms where possible"* ([Dan Brickley](https://github.com/danbri) - coordinator).

This project is a taskforce to enhance the *SchemaOrg core items* definitions, citing in each core item its corresponding Wikidata item (eg. add Wikidata-ID in the text of RFD-comment or linking explicitally adding RDF-statement to the external equivalent), and to link SchemaOrg items in the source code of corresponding Wikidata items.

## Motivations

There are some consensus about mappig task, but the production of results was growing slowly,

![](assets/taskAim-480px.png)

And the initial goal changed from "map SchemaOrg to Wikidata" to "map Wikidata to SchemaOrg", causing some confusin in the team and lost of voluntaries... After 2 years and some work, we (a little group of voluntaries) noticed again that we need the initial goal.

In this project we want to join the two sides of the bridge!

![](assets/Wd2Sc-bridge-fail.jpg)

Wikidata and SchemaOrg also represents two choices of concept-semantic definition strategies, [extensional and intensional](https://en.wikipedia.org/wiki/Extensional_and_intensional_definitions):

* *SchemaOrg definition strategy* is simple and pragmatic. Each entry (class or property) is intensionally defined by a short  phrase, and the real concept is built extensionally by the community of users, with extension at initial samples or statistics of use.

* *Wikidata definition strategy* is based on Wikipedia. All entries (mainly stable classes) define intention associating item with corresponding Wikipedia's entry.

So, providing SchemaOrg-side we enhance correct use and avoid confusion for SchemaOrg users.  Providing wikidata-side we enhance Wikidata definition and offer access to Wikidata users the biggest [semantic *corpus* sampler](https://en.wikipedia.org/wiki/Corpus_linguistics) of the Web.

## Tasks and status

* Check it out on our [PROJECT PAGE](https://github.com/CPT-PC/schemaOrg-bdMaps/projects)

### Working on SchemaOrg side


* To establish a convention (methodology) for inclusion of the definitional Wikidata-link in the RDF SchemaOrg item.
* To include (where possible), in the "core SchemaOrg", the links


### Working on Wikidata side
...
See  also [Wikidata's Guidelines for external relationships](https://www.wikidata.org/wiki/Help:Statements/Guidelines_for_external_relationships#schema_case).
...

### Working with DBpedia methodology

... using "mapping vocabularies"  experience of DBpedia experts... best practices and final automation ...

### Initial and target situations in 2017
...


