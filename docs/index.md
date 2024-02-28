# Entity Annotation Vocabulary


Welcome to the documentation of the *Entity Annotation Vocabulary* (EAV).  The vocabulary was designed to support the annotations of values and relations within knowledge graphs. It emphasizes properties that assess the quality of these relationships and encapsulate their lifecycle to facilitate automation.


```jsonld
"@context": {
  "sdo": https://schema.org/,
  "eav": https://w3id.org/meg/eav/
},
"@type": "sdo:LearningResource",
"sdo:name" : "Introduction into the Semantic Web",
"sdo:audience": {
  "@language": "en",
  "@value": "students in higher education",
  "@annotation": {
    "eav:confidence": 0.85, 
    "eav:status": "suggested", 
    "eav:method": "RAG"
  }
}

```

The development of this ontology is part of a research project focused on enriching metadata for learning resources. Through the use of self-learning AI models, the framework supports the recommendation of additional metadata and the establishment of new connections within the knowledge graph.

As this is an ongoing project, the vocabulary of the ontology is continually being extended and refined to better serve its intended purposes. This document aims to provide a comprehensive overview of the current state of the ontology and guide users in its application and contribution to its development. 

The vocabulary makes heavy use of [RDF-star](https://www.w3.org/2022/08/rdf-star-wg-charter/). RDF Star is an enhancement of the Resource Description Framework (RDF), designed to extend RDF's capabilities by introducing a mechanism for making statements about other statements. This extension allows for the representation of more complex relationships and metadata within a knowledge graph, providing a means to encapsulate attributes such as the quality and lifecycle of relationships. RDF Star's ability to embed additional information about the connections between data points enriches the semantic context of the graph, making it a powerful tool for advanced data modeling and knowledge representation.