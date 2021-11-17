# Awesome Knowledge Graph Construction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of knowledge graph construction resources. [Last update: Jan 2020]

## Contents
* [Research Trends and Surveys](#research-trends-and-surveys)
* [Papers](#papers)
	* [Curated Approaches](#curated-approaches)
	* [Collaborative Approaches](#collaborative-approaches)
	* [Automated Semi-structured Approaches](#automated-semi-structured-approaches)
	* [Automated Unstructured Approaches](#automated-unstructured-approaches)
		* [Schema-based Approaches](#schema-based-approaches)
		* [Open Information Extraction](#open-information-extraction)
* [Lectures](#lectures)
	* [Tutorials](#tutorials)
	* [Videos and Slides](#videos-and-slides)
* [Datasets](#datasets)
* [Systems and Tools](#systems-and-tools)


## Research Trends and Surveys

* From Information to Knowledge: Harvesting Entities and Relationships from Web Sources (Weikum et al, 2010) [[paper]](https://people.mpi-inf.mpg.de/~weikum/pods2010-weikum&theobald.pdf)
* Advances in Automated Knowledge Base Construction (Suchanek et al, 2012) [[paper]](https://pdfs.semanticscholar.org/709e/64be9cc9eb7c8b29bf49237cd2df835efd24.pdf)
* TAC-Knowledge Base Population challenge (Ji et al) [[2019]](https://blender.cs.illinois.edu/paper/ji2019kbp.pdf) [[2017]](http://nlp.cs.rpi.edu/paper/kbp2017.pdf) [[2016]](http://nlp.cs.rpi.edu/paper/kbp2016.pdf) [[2015]](https://pdfs.semanticscholar.org/955a/78a8a5e4e31d10ffc827f365bd4c4f30d563.pdf)
* A Survey on Open Information Extraction (Niklaus el al 2018) [[paper]](https://www.aclweb.org/anthology/C18-1326.pdf)

## Papers

### Curated Approaches 

Triples are collected by domain experts.

* CYC: A Large-scale Investment in Knowledge Infrastructure [[paper]](https://www.cc.gatech.edu/~isbell/classes/reading/papers/lenat95cyc.pdf)
	* Brief introduction: A universal schema of roughly 105 general concepts spanning human reality. 
	* Authors: Douglas B. Lenat
	* Venue: Communications of the ACM, 1995
* WordNet: A Lexical Database for English [[paper]](http://l2r.cs.uiuc.edu/Teaching/CS598-05/Papers/miller95.pdf)
	* Brief introduction: WordNet is an online lexical database under program control.
	* Authors: GA Miller (Princeton University)
	* Venue: Communications of the ACM, 1995
* The Unified Medical Language System (UMLS): integrating biomedical terminology [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/)
	* Brief introduction: A biomedical vocabularies developed by the US National Library of Medicine. The UMLS integrates over 900000 concepts, as well as 12 million relations among these concepts.
	* Authors: Olivier Bodenreider (Lister Hill National Center for Biomedical Communications)
	* Venue: Nucleic acids research, 2004

### Collaborative Approaches

Triples are collected by volunteers.

* Wikidata: a free collaborative knowledgebase [[paper]](http://ws.nju.edu.cn/courses/ke/reading/3_wikidata.pdf)
	* Wikidata is a collaborative knowledge base, collecting structured data to provide support for Wikipedia, Wikimedia Commons.
	* Authors: DENNY VRANDECˇIC´ and  MARKUS KRÖTZSCH 
	* Venue: Communications of the ACM, 2014
* Freebase: a collaboratively created graph database for structuring human knowledge [[paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.538.7139&rep=rep1&type=pdf)
	* Brief introduction: Freebase is a  tuple knowledge base used to structure general human knowledge, which is collaboratively created, structured, and maintained.
	* Authors: Kurt Bollacker, Colin Evans, Praveen Paritosh, Tim Sturge, Jamie Taylor (Metaweb Technologies, Inc)
	* Venue: SIGMOD'08

### Automated Semi-structured Approaches

Triples are collected from the semi-structured data source via some rule based methods.

* YAGO: A Core of Semantic Knowledge [[paper]](https://www2007.org/papers/paper391.pdf)
	* Brief introduction: Triples are automatically extracted from Wikipedia and unified with WordNet, using a combination of rule-based and heuristic methods.
	* Authors: Fabian M. Suchanek, Gjergji Kasneci, Gerhard Weikum (Max-Planck-Institut)
	* Venue: WWW'07
* YAGO2: A spatially and temporally enhanced knowledge base from Wikipedia [[paper]](https://www.sciencedirect.com/science/article/pii/S0004370212000719)
	* Brief introduction: An extension of the YAGO knowledge base, in which triples are anchored in both time and space. YAGO2 is built automatically from Wikipedia, GeoNames, and WordNet.
	* Authors: Johannes Hoffart, Fabian M. Suchanek, Klaus Berberich and Gerhard Weikum (Max-Planck-Institut)
	* Venue: Artificial Intelligence, 2013
* DBpedia: A Nucleus for a Web of Open Data [[paper]](https://www.cis.upenn.edu/~zives/research/dbpedia.pdf)
	* Brief introduction: Extract triples from Wikipedia encyclopedia based on a templated pattern matching method.
	* Authors: S. Auer, C. Bizer, G. Kobilarov, J. Lehmann, R. Cyganiak, and Z. Ives (University of Pennsylvania & Universit¨at Leipzig)
	* Venue: The Semantic Web'07
* CERES: Distantly Supervised Relation Extraction from the Semi-Structured Web [[paper]](http://www.vldb.org/pvldb/vol11/p1084-lockard.pdf)
	* Brief introduction: Propose an automatic knowledge extraction framework that improves the distant supervision assumption for triples extraction.
	* Authors: Colin Lockard, Xin Luna Dong, Arash Einolghozati and Arash Einolghozati
	* Venue: VLDB'18

### Automated Unstructured Approaches

Triples are extracted from unstructured data via data-driven techniques

#### Schema-based Approaches

* NELL: Toward an Architecture for Never-Ending Language Learning [[paper]](http://www.cs.cmu.edu/~acarlson/papers/carlson-aaai10.pdf)
	* Brief introduction: Continuously extract extract new knowledge from the Web through self-learning on a small number of samples.
	* Authors: Andrew Carlson, Justin Betteridge, Bryan Kisiel, Burr Settles, Estevam R. Hruschka Jr., and Tom M. Mitchell (CMU)
	* Venue: AAAI'10
* PROSPERA: Scalable knowledge harvesting with high precision and high recall [[paper]](http://www.nakashole.com/papers/2011-wsdm-prospera.pdf)
	* Brief introduction: Reconcile precision, recall and scalability by extended n-gram patten matching.
	* Authors: Ndapandula Nakashole, Martin Theobald, Gerhard Weikum (Max Planck Institute)
	* Venue: WSDM'11
* DeepDive/Elementary: Large-scale knowledge-base construction via machine learning and statistical inference [[paper]](http://infolab.stanford.edu/hazy/papers/elementary_journal.pdf)
	* Brief introductions: Propose a Markov logic-based  model and architecture for knowledge base construction (KBC) by integrating different kinds of data resources and KBC techniques.
	* Authors: Feng Niu, Ce Zhang, Christopher Ré, and Jude Shavlik (University of Wisconsin-Madison, Stanford University)
	* Venue: IJSWIS'12
* Knowledge Vault: A Web-scale Approach to Probabilistic Knowledge Fusion [[paper]](https://www.cs.ubc.ca/~murphyk/Papers/kv-kdd14.pdf)
	* Brief introduction:  Build Knowledge Vault, a Web-scale probabilistic knowledge base that combines extractions from Web content with prior knowledge derived from existing knowledge repositories based on distant supervision method.
	* Authors: Xin Luna Dong et al (Google)
	* Venue: KDD'14
* Sealing Pipeline Leaks and Understanding Chinese [[paper]](https://www.cs.princeton.edu/~danqic/papers/tac2016.pdf)
	* Brief introudction: Propose a combinational system consists of several ruled-based relation extractors and a distantly supervised extractor.
	* Authors: Yuhao Zhang, Arun Chaganty, Ashwin Paranjape, Danqi Chen, Jason Bolton, Peng Qi, Christopher D. Manning (Stanford University)
	* Venue: TAC'16
* CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases [[paper]](https://arxiv.org/pdf/1610.08763.pdf)
	* Brief introduction: Joint extraction of typed entities and relations with labeled data obtained from knowledge bases with distant supervision.
	* Authors: Xiang Ren, Zeqiu Wu, Wenqi He, Meng Qu, Clare R. Voss, Heng Ji, Tarek F. Abdelzaher, Jiawei Han (UIUC & Army Research Laboratory)
	* Venue: WWW'17
* Discovering Implicit Knowledge with Unary Relations [[paper]](https://www.aclweb.org/anthology/P18-1147.pdf)
	* Brief introduction: Extract the implicit relation in text through coverting binary relations to unary relations.
	* Authors: Michael Glass, Alfio Gliozzo (IBM Research)
	* Venue: ACL'18



#### Open Information Extraction

* Open Information Extraction from the Web [[paper]](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-429.pdf)
	* Brief introduction: First paper for open information extraction with a rule based method.
	* Authors: Michele Banko, Michael J Cafarella, Stephen Soderland, Matt Broadhead and Oren Etzioni (University of Washington)
	* Venue: AAAI'07
* Identifying relations for open information extraction [[paper]](https://www.aclweb.org/anthology/D11-1142.pdf)
	* Brief introduction: Introduce syntactic and lexical constraints on binary relations expressed by verbs to reduce the uninformative and incoherent extractions.
	* Authors: Anthony Fader, Stephen Soderland, and Oren Etzioni (University of Washington)
	* Venue: EMNLP'11
* Open Language Learning for Information Extraction [[paper]](https://homes.cs.washington.edu/~mausam/papers/emnlp12a.pdf)
	* Brief introduction: An extention of OpenIE by adding noun, adjectives mediated relation, as well as taking context into consideration.
	* Authors: Mausam, Michael Schmitz, Robert Bart, Stephen Soderland, and Oren Etzioni (University of Washington)
	* Venue: EMNLP'12
* Neural Open Information Extraction [[paper]](https://arxiv.org/pdf/1805.04270.pdf)
	* Brief introduction: Propose a neural encoder-decoder OpenIE framework. The model is trained with highly confident binary extractions bootstrapped from a state-of-the-art Open IE system, therefore can generate highquality tuples without any hand-crafted patterns.
	* Authors: Lei Cui, Furu Wei, and Ming Zhou (MSRA)
	* Veune: ACL'18
* COMET: Commonsense Transformers for Automatic Knowledge Graph Construction [[paper]](https://arxiv.org/pdf/1906.05317.pdf)
	* Brief introduction: Commonsense knowledge graph construction by using existing tuples as a seed set of knowledge for training. Using this seed set, a pre-trained language model (ELMO) learns to adapt its learned representations to knowledge generation, and produces novel tuples.
	* Authors: Antoine Bosselut, Hannah Rashkin, Maarten Sap, Chaitanya Malaviya, Asli Celikyilmaz and Yejin Choi (University of Washington)
	* Venue: ACL'19


## Lectures

### Tutorials
* Mining Knowledge Graphs from Text. [[link]](https://kgtutorial.github.io/)
	* Jay Pujara (USC), Sameer Singh (UCI)
	* WSDM'18 
* Constructing Domain-specific Knowledge Graphs. [[link]](https://usc-isi-i2.github.io/AAAI18Tutorial/)
	* Craig Knoblock (USC), Pedro Szekely (USC), Mayank Kejriwal (USC)
	* AAAI'18

### Videos and Slides
* [Stanford University: CS124](https://web.stanford.edu/class/cs124/), Dan Jurafsky
	* (Video) [Week 5: Relation Extraction and Question](https://www.youtube.com/watch?v=5SUzf6252_0&list=PLaZQkZp6WhWyszpcteV4LFgJ8lQJ5WIxK&ab_channel=FromLanguagestoInformation)
* [Washington University: CSE517](https://courses.cs.washington.edu/courses/cse517/), Luke Zettlemoyer
	* (Slide) [Relation Extraction 1](https://courses.cs.washington.edu/courses/cse517/13wi/slides/cse517wi13-RelationExtraction.pdf)
	* (Slide) [Relation Extraction 2](https://courses.cs.washington.edu/courses/cse517/13wi/slides/cse517wi13-RelationExtractionII.pdf)
* [New York University: CSCI-GA.2590](https://cs.nyu.edu/courses/spring17/CSCI-GA.2590-001/), Ralph Grishman
	* (Slide) [Relation Extraction: Rule-based Approaches](https://cs.nyu.edu/courses/spring17/CSCI-GA.2590-001/DependencyPaths.pdf)
* [Michigan University: Coursera](https://ai.umich.edu/portfolio/natural-language-processing/), Dragomir R. Radev
	* (Video) [Lecture 48: Relation Extraction](https://www.youtube.com/watch?v=TbrlRei_0h8&ab_channel=ArtificialIntelligence-AllinOne)




## Datasets
* New York Times (NYT) Corpus [[paper]](http://www.riedelcastro.org//publications/papers/riedel10modeling.pdf) [[download]](https://catalog.ldc.upenn.edu/LDC2008T19)
	* This dataset was generated by aligning *Freebase* relations with the NYT corpus, with sentences from the years 2005-2006 used as the training corpus and sentences from 2007 used as the testing corpus.
* FewRel: Few-Shot Relation Classification Dataset [[paper]](https://arxiv.org/abs/1810.10147) [[Website]](http://zhuhao.me/fewrel)
	* This dataset is a supervised few-shot relation classification dataset. The corpus is Wikipedia and the knowledge base used to annotate the corpus is Wikidata.
* TupleInf Open IE Dataset [[Website]](http://data.allenai.org/tuple-ie/)
	* The TupleInf Open IE dataset contains Open IE tuples extracted from 263K sentences that were used by the solver in "Answering Complex Questions Using Open Information Extraction".



## Systems and Tools
* DeepDive (Christopher Ré el al, Stanford University) [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5361060/pdf/nihms826683.pdf) [[System]](http://deepdive.stanford.edu/kbc)
* Open Information Extraction (Stanford University NLP) [[System]](https://nlp.stanford.edu/software/openie.html)

## Reference
* [Srihari](https://cedar.buffalo.edu/~srihari/CSE674/Chap22/22.1%20Knowledge%20Graphs.pdf)


[Back to Top](#contents)
