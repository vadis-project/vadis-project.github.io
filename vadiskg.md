# VADIS Knowledge Graph (VADISKG)

The resulting data corpus containing links between scholarly articles, survey variables, and research datasets has been published as Knowledge Graph.

## Data model

The following figure illustrates a simplified version of the VADISKG data model.

![VADISKG](VADISKG_links.png)

**Namespaces and prefixes**

The data model of the VADISKG reuses classes and properties of the following vocabularies while introducing few own classes and properties for which no appropriate equivalent was existing.

* vadiskg: https://data.gesis.org/vadiskg/schema/
* schema: https://schema.org/
* disco: http://rdf-vocabulary.ddialliance.org/discovery#
* gesiskg: https://data.gesis.org/gesiskg/schema/

**Scientific resources in the KG**

| Resource name | Class                   |
| :------------ | :---------------------- |
| Publication   | schema:ScholarlyArticle |
| Variable      | disco:Variable          |
| Dataset       | schema:Dataset          |

**Additional entities in the KG**

| Entity name | Class              |
| :---------- | :----------------- |
| Person      | schema:Person      |
| Keyword     | schema:DefinedTerm |

**Entities generated by VADIS**

| Entity name | Description | Class | Subclass of |
| :------------ | :---------------------- | :---- | :---- |
| Extractive summary | most comprehensive sentence of abstract sentences | vadiskg:ExtractiveSummary | vadiskg:Summary |
| Abstractive summary | tldr extreme summary generated out of the abstract | vadiskg:AbstractiveSummary | vadiskg:Summary |
| Abstract sentence | sentence of the abstract | vadiskg:AbstractSentence | vadiskg:Sentence |
| Variable sentence | sentence containing a variable mention | vadiskg:VariableSentence | vadiskg:Sentence |
| Variable reference | Detected variable in a variable sentence | gesiskg:VariableReference | gesiskg:Reference |

**Link information in the KG**

| Metadata name | Description | Property |
| :---------- | :----------------- | :-- |
| Sentence confidence score | Computed confidence score for the detected sentence containing variable mentions | vadiskg:score |
| Method type | Method which has been used to detect the variable sentences | vadiskg:methodType |
| Common words | Common words used in the variable sentence | vadiskg:commonWords |
| Link reason | Part of text which is the basis for the link detection | gesiskg:linkReason |
| Variable similarity score | Computed similarity score for the detected variable in a variable sentence | gesiskg:linkScore |
| Link type | Specifying that the link was automatically generated | gesiskg:linkType |

**URI paths**

* Base URI: https://data.gesis.org/vadiskg/ 
* Schema URI: https://data.gesis.org/vadiskg/schema/ 
* Resource URI: https://data.gesis.org/vadiskg/resource/ 
* VADISKG metadata: https://data.gesis.org/vadiskg/id/1 

## Statistics

* coming soon 

## Dataset
The VADISKG can be accessed and queried via its SPARQL endpoint. Additionally, the KG and the underlying ontology will be available for download soon.

**SPARQL endpoint**

The data within the VADIS Knowledge Graph can be explored using SPARQL queries at the following SPARQL endpoint: [https://data.gesis.org/vadiskg/sparql](https://data.gesis.org/vadiskg/sparql)

You can find some example SPARQL queries here:

* coming soon 

**Download**

The VADIS Knowledge Graph will be available for download as a full RDF dump as well as its underlying ontology from the following links:

* Dataset: - link coming soon -
* Ontology: - link coming soon -

## License
The VADIS Knowledge Graph is available for access, download, and reuse under a [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/) license since the license of some input sources is CC-BY as well.

## Contact
Benjamin Zapilko, benjamin(dot)zapilko(at)gesis(dot)org


[Back to the VADIS homepage](README.md)