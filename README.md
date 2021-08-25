# ephin-experiments
event prediction experiments with ephin and other information network embedding methods

## GraphEmbeddings
GraphEmbeddings submodule based on https://github.com/shenweichen/GraphEmbedding but the used algorithms works with tf 2.x
### install
inside GraphEmbeddings directory from this repository run
```
python setup.py install
```

## gcn
GCN submodule based on https://github.com/dbusbridge/gcn_tutorial

## networks
all the events represented in the context sub-netwokrs were extracted from the GDELT project (https://www.gdeltproject.org/) and are represented as networkx (https://networkx.org) pickle5 graphs. all the networks have DistilBERT-multilingual (https://huggingface.co/distilbert-base-multilingual-cased) embedding for the events, and other objects available from the GDELT project database. you can download them at:
https://drive.google.com/drive/folders/1_Wz9O4Nzr8JgjzbMzMHI54M3LITG7PCZ?usp=sharing

### networks like these are required to the experiments, so download them (or create yours) to an accessible directory on your machine and update the path on the code. 

## wip
for now: data readings with .parquet and single dataframe for BERT and other atributes for the news.
as well as other improvements like new experiments, methods, data and usability features with the research progress.
