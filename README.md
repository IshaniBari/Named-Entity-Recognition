# Named-Entity-Recognition

### Task - 
NER on WIESP (Workshop on Information Extraction from Scientific Publications) dataset. 

### Dataset Description - 
Dataset contains text fragments from astrophysics papers, provided by the NASA Astrophysical Data System with manually tagged astronomical facilities and other entities of interest (e.g., celestial objects). It is in JSON Lines format (each line is a json dictionary). <br>
Each entry consists of a dictionary with the following keys:<br>
<ul>
<li>"unique_id": a unique identifier for this data sample.
<li>"tokens": the list of tokens (strings) that form the text of this sample. 
<li>"ner_tags": the list of NER tags (in IOB2 format)<br>
</ul>
The train data has 1753 sentences having NER tags and ids for each sentence tokens. While the test dataset has 1366 sentences.

##### Link to the dataset -  https://huggingface.co/datasets/fgrezes/WIESP2022-NER


### Summary – 
As part of the final project of the AI-3 course at Univ.AI, we used the WIESP dataset to build simple RNN and Bidirectional LSTM models using embeddings from scratch as well as pre-trained Word2Vec embeddings to name entities in the test data based on train data. 
