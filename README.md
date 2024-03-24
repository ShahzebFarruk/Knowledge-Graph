# Knowledge Graph + Text Classification
![image](https://user-images.githubusercontent.com/61950234/115834369-28a90000-a3e3-11eb-9b62-7767173400a7.png)

This project aims to utililize power of trivial text classsification and apply the output of text classification to Knowledge Graphs in order to better classifiy the topics.
This project scraps the text documents (Corpus) from Wikipedia and then used NER(using neuralcoref & Spacy Lib) to extract the topics and forms triplets in subject->relation->predicate pairs. This output is classified and along side the knowledge embbedings being calculate for the construction of Knowledge Graph.
## How to run the codes
Open the noetbook and run the cell.
You may need to install the requirements.

The Projct is divided into two parts for this repo purposes.
Part-1 is the below Google Colab links for KG Generation and triplets.
PART-2 is for the Knowledge Embeddings used PyKeen pipeline to achieve RotatE, TranS , etc.

### Code Links
1. Part-1 of the code is based upon [Auto-Generated Knowledge Graphs](https://towardsdatascience.com/auto-generated-knowledge-graphs-92ca99a81121).
### Other Link:
1. [Clinical Knowledge Graph](https://github.com/MannLabs/CKG) and paper [Clinical Knowledge Graph Integrates Proteomics Data into Clinical Decision-Making](https://www.biorxiv.org/content/10.1101/2020.05.09.084897v1)
2. [python-knowledge-graph](https://github.com/bdmarius/python-knowledge-graph/blob/master/knowledgegraph.py)
3. [Deep Learning with Knowledge Graphs](https://medium.com/octavian-ai/deep-learning-with-knowledge-graphs-3df0b469a61a)

## Colab Links (PART-1)
1. [KGCreation_test_wiki_extraction.ipynb](https://colab.research.google.com/drive/18Wls31YHwsHmUyp8g3bPV7qWjLPRLoQg?usp=sharing)
2. [KGCreation_wiki_extraction_1_0.ipynb](https://colab.research.google.com/drive/1CJ229lVm1KDpqLxXUpdKLHG1ufGD0_xt?usp=sharing)
3. [KGCreation_wiki_extraction_1_1.ipynb](https://colab.research.google.com/drive/1Es3Yh2EWQIWQSSeCwS2sG3qKP05-J28a?usp=sharing)
4. [KGCreation_wiki_extraction_1_1a.ipynb](https://colab.research.google.com/drive/1RqkaqGldt6ImH6PV7mXqb5iPgQWwFgQO?usp=sharing)
5. [KGCreation_wiki_extraction_1_1b.ipynb](https://colab.research.google.com/drive/1VBBiy-PaIGbSpFZbGmsKiJutipZjgPXh?usp=sharing)

## PART-2 See the repo folders
The idea of Graph Embeddings is being followed to be added in the end of the pipeline. For this we use the Lib [PyKEEN](https://github.com/pykeen/pykeen) (Python KnowlEdge EmbeddiNgs)

[KG_P2_Word_embeddings_v1](https://github.com/ShahzebFarruk/Knowledge-graph-part2/tree/main/KG_P2_Word_embeddings_v1) (pykeen demos and experiments)

[KG_P2_Word_embeddings_v2](https://github.com/ShahzebFarruk/Knowledge-graph-part2/tree/main/KG_P2_Graph_embeddings_v2) (part-2 solution)

### Pykeen References:
PyKEEN (Python KnowlEdge EmbeddiNgs) is a Python package designed to train and evaluate knowledge graph embedding models (incorporating multi-modal information).
1. [PyKeen Example Code](https://github.com/pykeen/pykeen/blob/master/notebooks/hello_world/Hello%20World!.ipynb)
#### The following Links were used from Pykeen for example coding purposes. 
1. [PyKeen Triples](https://pykeen.readthedocs.io/en/latest/reference/triples.html)
2. [Pykeen Pipeline](https://pykeen.readthedocs.io/en/latest/api/pykeen.pipeline.pipeline.html#pykeen.pipeline.pipeline)

#### Contd for our part2 scripts:
[KG_P2_Word_embeddings_v2](https://github.com/ShahzebFarruk/Knowledge-graph-part2/tree/main/KG_P2_Graph_embeddings_v2)  v2=Latest Code being used and contains the solution

[KG_P2_Word_embeddings_v1](https://github.com/ShahzebFarruk/Knowledge-graph-part2/tree/main/KG_P2_Word_embeddings_v1)  v1=contains the pykeen demos and experiments.

### Who do I talk to? ###
### Details ###
* Created on Wed Feb 28 19:06:18 2021
* @author: shahzeb
* IDE: Spyder(Python3.8)
* sshah184@uottawa.ca
