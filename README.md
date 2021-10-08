# Clinical Trials Knowledge Graph (CTKG)

Clinical Trials Knowledge Graph (CTKG) is a knowledge graph constructed over the clinical trial data from The Access to Aggregate Content of ClinicalTrials.gov (AACT) database[^1]. CTKG includes nodes representing medical entities in clinical trials (e.g., studies, drugs, conditions), and edges representing the relations among these entities (e.g., drugs used in studies). It includes 1,501,333 nodes belonging to 19 node-types; and 3,664,619 triplets belonging to 22 relation-types. It also provides three notebooks about how to explore and analysis the CTKG using the knowledge graph embeddings.



<img src="E:\PhDInOSU\Project\AACT\github\Clinical-Trial-Knowledge-Graph\Schema.png" alt="Schema" style="zoom:40%;" />



### CTKG dataset

The directory <code>rawdata</code> contains all the entities and relations:

* <code>attributes.zip</code> : the attributes of entities (e.g., "study").
* <code>relations.zip</code> : the attributes of relations between two types of entities (e.g., "study"--- study-drug ---"drug").
* <code>reverse.zip</code> : the attributes of reverse relations between two types of entities (e.g., "drug" --- drug-study --- "study").



# Reference

[^1]: Tasneem A, Aberle L, Ananth H, Chakraborty S, Chiswell K, McCourt BJ, et al. (2012) The Database for Aggregate Analysis of ClinicalTrials.gov (AACT) and Subsequent Regrouping by Clinical Specialty. PLoS ONE 7(3): e33677. https://doi.org/10.1371/journal.pone.0033677

