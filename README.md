# Awesome Knowledge Graph Construction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of knowledge graph construction resources.

## Contents
* [Research Trends and Surveys](#research-trends-and-surveys)
* [Papers](#papers)
	* [Supervised Approaches](#supervised-approaches)
	* [Distant Supervision Approaches](#distant-supervision-approaches)
	* [Language Models](#language-models)
* [Lectures](#courses-and-lectures)
	* [Tutorials](#tutorials)
* [Datasets](#datasets)
* [Implenmetation and Systems](#implenmetation-and-systems)


## Research Trends and Surveys

* From Information to Knowledge: Harvesting Entities and Relationships from Web Sources (Weikum et al, 2010) [[paper]](https://people.mpi-inf.mpg.de/~weikum/pods2010-weikum&theobald.pdf)
* Knowledge Base Population: Successful Approaches and Challenges (Ji et al, 2011) [[paper]](https://www.aclweb.org/anthology/P11-1115.pdf)
* Advances in Automated Knowledge Base Construction (Suchanek et al, 2012) [[paper]](https://pdfs.semanticscholar.org/709e/64be9cc9eb7c8b29bf49237cd2df835efd24.pdf)



## Papers

### Curated Approaches 

Triples are created manually by a closed group of experts.

* CYC: A Large-scale Investment in Knowledge Infrastructure [[paper]](https://www.cc.gatech.edu/~isbell/classes/reading/papers/lenat95cyc.pdf)
	* Douglas B. Lenat
	* Communications of the ACM 1995
* WordNet: A Lexical Database for English [[paper]](http://l2r.cs.uiuc.edu/Teaching/CS598-05/Papers/miller95.pdf)
	* GA Miller (Princeton University)
	* Communications of the ACM 1995
* The Unified Medical Language System (UMLS): integrating biomedical terminology [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/)
	* Olivier Bodenreider (Lister Hill National Center for Biomedical Communications)
	* Nucleic acids research 2004

### Collaborative Approaches

Triples are created manually by an open group of volunteers.

* Wikidata: a free collaborative knowledgebase [[paper]](http://ws.nju.edu.cn/courses/ke/reading/3_wikidata.pdf)
	* DENNY VRANDECˇIC´ and  MARKUS KRÖTZSCH 
	* Communications of the ACM 2014
* Freebase: a collaboratively created graph database for structuring human knowledge [[paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.538.7139&rep=rep1&type=pdf)
	* Kurt Bollacker, Colin Evans, Praveen Paritosh, Tim Sturge, Jamie Taylor (Metaweb Technologies, Inc)
	* SIGMOD'08

### Automated Semi-structured Approaches

Triples are extracted automatically from semi-structured text (e.g., infoboxes in Wikipedia) via hand-crafted rules, learned rules, or regular expressions 

* Yago: A Core of Semantic Knowledge [[paper]](https://www2007.org/papers/paper391.pdf)
	* Fabian M. Suchanek, Gjergji Kasneci, Gerhard Weikum (Max-Planck-Institut)
	* WWW'07
* YAGO2: A spatially and temporally enhanced knowledge base from Wikipedia [[paper]](https://www.sciencedirect.com/science/article/pii/S0004370212000719)
	* Johannes Hoffart, Fabian M. Suchanek, Klaus Berberich and Gerhard Weikum (Max-Planck-Institut)
	* Artificial Intelligence 2013
* DBpedia: A Nucleus for a Web of Open Data [[paper]](https://www.cis.upenn.edu/~zives/research/dbpedia.pdf)
	* S. Auer, C. Bizer, G. Kobilarov, J. Lehmann, R. Cyganiak, and Z. Ives (University of Pennsylvania & Universit¨at Leipzig)
	* The Semantic Web 2007

### Automated Unstructured Approaches

Triples are extracted automatically from unstructured text via machine learning and natural language processing techniques

#### Schema-based Approaches

* Knowledge Vault: A Web-scale Approach to Probabilistic Knowledge Fusion [[paper]](https://www.cs.ubc.ca/~murphyk/Papers/kv-kdd14.pdf)
	* Xin Luna Dong et al (Google)
	* KDD'14
* NELL: Toward an Architecture for Never-Ending Language Learning [[paper]](http://www.cs.cmu.edu/~acarlson/papers/carlson-aaai10.pdf)
	* Andrew Carlson, Justin Betteridge, Bryan Kisiel, Burr Settles, Estevam R. Hruschka Jr., and Tom M. Mitchell (CMU)
	* AAAI'10
* PROSPERA: Scalable knowledge harvesting with high precision and high recall [[paper]](http://www.nakashole.com/papers/2011-wsdm-prospera.pdf)
	* Ndapandula Nakashole, Martin Theobald, Gerhard Weikum (Max Planck Institute)
	* WSDM'11
* DeepDive/Elementary: Large-scale knowledge-base construction via machine learning and statistical inference [[paper]](http://infolab.stanford.edu/hazy/papers/elementary_journal.pdf)
	* Feng Niu, Ce Zhang, Christopher Ré, and Jude Shavlik (University of Wisconsin-Madison, Stanford University)
	* IJSWIS'12

#### Schema-free Approaches (Open Information Extraction)

* Identifying relations for open information extraction [[paper]](https://www.aclweb.org/anthology/D11-1142.pdf)
	* Anthony Fader, Stephen Soderland, and Oren Etzioni (University of Washington)
	* EMNLP'11
* Open Language Learning for Information Extraction [[paper]](https://homes.cs.washington.edu/~mausam/papers/emnlp12a.pdf)
	* Mausam, Michael Schmitz, Robert Bart, Stephen Soderland, and Oren Etzioni (University of Washington)
	* EMNLP'12
*

* Learning Knowledge Graphs for Question Answering through Conversational Dialog [[paper]](https://homes.cs.washington.edu/~hannaneh/papers/knowbot.pdf)



## Lectures

### Tutorials
* Mining Knowledge Graphs from Text. [[link]](https://kgtutorial.github.io/)
	* Jay Pujara (USC), Sameer Singh (UCI)
	* WSDM'18 
* Constructing Domain-specific Knowledge Graphs. [[link]](https://usc-isi-i2.github.io/AAAI18Tutorial/)
	* Craig Knoblock (USC), Pedro Szekely (USC), Mayank Kejriwal (USC)
	* AAAI'18
*


## Datasets
* SemEval-2010 Task 8 [[paper]](http://www.aclweb.org/anthology/S10-1006) [[download]](https://docs.google.com/leaf?id=0B_jQiLugGTAkMDQ5ZjZiMTUtMzQ1Yy00YWNmLWJlZDYtOWY1ZDMwY2U4YjFk&sort=name&layout=list&num=50)
	* Multi-Way Classification of Semantic Relations Between Pairs of Nominals
* New York Times (NYT) Corpus [[paper]](http://www.riedelcastro.org//publications/papers/riedel10modeling.pdf) [[download]](https://catalog.ldc.upenn.edu/LDC2008T19)
	* This dataset was generated by aligning *Freebase* relations with the NYT corpus, with sentences from the years 2005-2006 used as the training corpus and sentences from 2007 used as the testing corpus.
* FewRel: Few-Shot Relation Classification Dataset [[paper]](https://arxiv.org/abs/1810.10147) [[Website]](http://zhuhao.me/fewrel)
	* This dataset is a supervised few-shot relation classification dataset. The corpus is Wikipedia and the knowledge base used to annotate the corpus is Wikidata.

For state of the art results check out [nlpprogress.com on relation extraction](https://nlpprogress.com/english/relationship_extraction.html)

[Back to Top](#contents)


## Videos and Lectures
* [Stanford University: CS124](https://web.stanford.edu/class/cs124/), Dan Jurafsky
	* (Video) [Week 5: Relation Extraction and Question](https://www.youtube.com/watch?v=5SUzf6252_0&list=PLaZQkZp6WhWyszpcteV4LFgJ8lQJ5WIxK&ab_channel=FromLanguagestoInformation)
* [Washington University: CSE517](https://courses.cs.washington.edu/courses/cse517/), Luke Zettlemoyer
	* (Slide) [Relation Extraction 1](https://courses.cs.washington.edu/courses/cse517/13wi/slides/cse517wi13-RelationExtraction.pdf)
	* (Slide) [Relation Extraction 2](https://courses.cs.washington.edu/courses/cse517/13wi/slides/cse517wi13-RelationExtractionII.pdf)
* [New York University: CSCI-GA.2590](https://cs.nyu.edu/courses/spring17/CSCI-GA.2590-001/), Ralph Grishman
	* (Slide) [Relation Extraction: Rule-based Approaches](https://cs.nyu.edu/courses/spring17/CSCI-GA.2590-001/DependencyPaths.pdf)
* [Michigan University: Coursera](https://ai.umich.edu/portfolio/natural-language-processing/), Dragomir R. Radev
	* (Video) [Lecture 48: Relation Extraction](https://www.youtube.com/watch?v=TbrlRei_0h8&ab_channel=ArtificialIntelligence-AllinOne)
* [Virginia University: CS6501-NLP](http://web.cs.ucla.edu/~kwchang/teaching/NLP16/), Kai-Wei Chang
	* (Slide) [Lecture 24: Relation Extraction](http://web.cs.ucla.edu/~kwchang/teaching/NLP16/slides/24-relation.pdf)


[Back to Top](#contents)


## Systems
* [DeepDive](http://deepdive.stanford.edu/kbc)

[Back to Top](#contents)
