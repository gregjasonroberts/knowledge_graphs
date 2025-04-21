#  Knowledge Graphs and NLP: Key Concepts and Applications

This repository captures summaries and key takeaways from selected chapters of two foundational texts in the fields of **knowledge graph** and **natural language processing (NLP)**. The purpose is to provide a reference base for building smarter, grounded, and more reliable AI systems using structured knowledge and large language models (LLMs).

---

##  Resources

- **_Knowledge Graphs: Fundamentals, Techniques, and Applications_**  
  Authors: Mayank Kejriwal, Craig Knoblock, Pedro Szekely (MIT Press)

- **_Natural Language Processing in Action_**  
  Authors: Hobson Lane, Cole Howard, Hannes Hapke (Manning)

---

##  Part 1: Knowledge Graphs – Summary of Key Concepts  
 _Based on Chapters 1–2 from_ **Knowledge Graphs**

This section introduces the foundations of knowledge graphs (KGs), focusing on how entities and relationships are modeled using RDF triples and ontologies.

---

##  Part 2: Domain Discovery & Web Information Extraction  
 _Based on Chapters 3 and 5 from_ **Knowledge Graphs**

These chapters focus on how to acquire domain-specific web content and extract structured facts using wrapper-based and learning-based approaches.
 
---

##  Part 3: Named Entity Recognition (NER)  
 _Based on Chapter 4 from_ **Knowledge Graphs**

NER is a foundational step in information extraction, identifying class instances in text using ontology-guided or open approaches.
 
---

##  Chapter 10: LLMs, Errors & Retrieval-Augmented Generation  
 _From_ **Natural Language Processing in Action**

This chapter discusses the power and limitations of LLMs and how to ground their outputs in facts using vector-based retrieval and fine-tuning.
 
---

##  Chapter 11: Information Extraction and Knowledge Graphs  
 _From_ **Natural Language Processing in Action**

This chapter walks through how to extract facts from text and build a knowledge graph for reasoning and grounding LLMs. It emphasizes that while language models sound fluent, they lack true understanding—something that symbolic, structured knowledge systems can support.

###  Key Concepts

1. **Entity and Relation Extraction**  
   By using part-of-speech tagging and dependency parsing, you can extract named entities and relationships from sentences to create triples that serve as the building blocks of a knowledge graph.

2. **Symbolic Reasoning with Knowledge Graphs**  
   Knowledge graphs store facts as entity–relationship–entity triples and allow reasoning beyond pattern prediction. You can infer new knowledge and correct errors in LLM outputs by grounding them in trusted facts.

3. **Building and Querying Your Knowledge Base**  
   Tools like `nlpia2` help visualize graphs like NELL (Never-Ending Language Learning). For production systems, larger graphs like **Wikidata** (100M+ entities) provide a powerful, community-maintained source of structured knowledge. Graph query languages such as **SPARQL** (used in this book), **Cypher** (Neo4j), and **AQL** (ArangoDB) allow you to retrieve information with precision. A major challenge remains in **mapping natural language questions to SPARQL queries**—a critical step in automating knowledge-based reasoning.


---
 

