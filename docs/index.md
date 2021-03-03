# NLP-Notes:

This Repository contains Notebooks and Notes on NLP

## Opensource Model Details:

### Domain Specific SQUAD2 Finetuned Model:

| models | Architecture | EM | F1 | Model Size |
| --- | --- | --- | --- |  --- | 
| [ktrapeznikov/biobert_v1.1_pubmed_squad_v2](https://huggingface.co/ktrapeznikov/biobert_v1.1_pubmed_squad_v2) | BioBert | 75.97068980038743 | 79.37043950121722 | 413.2mb |
| [ktrapeznikov/scibert_scivocab_uncased_squad_v2](https://huggingface.co/ktrapeznikov/scibert_scivocab_uncased_squad_v2) | SciBert | 75.07790785816559 | 78.47735207283013 | 419.4mb|


### Available Pretrained SQUAD2 Models:

| models | Architecture | EM | F1 | Model Size |
| --- | --- | --- | --- |  --- | 
| [ktrapeznikov/albert-xlarge-v2-squad-v2](https://huggingface.co/ktrapeznikov/albert-xlarge-v2-squad-v2) | albert-xlarge | **84.41842836688285** | **87.4628460501696** | 224mb |
| [roberta-base-squad2](https://huggingface.co/deepset/roberta-base-squad2) | Roberta-base | 79.97136359807968 | 83.00449234495325 | 474.3mb |
| [xlm-roberta-large-squad2](https://huggingface.co/deepset/xlm-roberta-large-squad2) | xlm-roberta-large | 79.45759285774446 | 83.79259828925511 | 2.1Gb |
| [twmkn9/albert-base-v2-squad2](https://huggingface.co/twmkn9/albert-base-v2-squad2) | albert-base | 78.71010200723923 |  81.89228117126069 | **44.6mb** |
| [electra-base-squad2](https://huggingface.co/deepset/electra-base-squad2) | Electra-base | 77.30144024256717 | 81.35438272008543 | 415.4mb |
| [microsoft/MiniLM-L12-H384-uncased](https://huggingface.co/deepset/minilm-uncased-squad2)| minilm-uncased | 76.13071675229513 | 79.49786500219953 | 127.3mb |
| [T5-base-for-BioQA](https://huggingface.co/ozcangundes/T5-base-for-BioQA) | T5-base | 76.13071675229513 | 79.49786500219953 | 850.4mb |
| [google/mobilebert-uncased](https://huggingface.co/mrm8488/mobilebert-uncased-finetuned-squadv2) | Mobilebert | 75.37 | 78.48 | 94mb |
| [xlm-roberta-base-squad2](https://huggingface.co/deepset/xlm-roberta-base-squad2) | xlm-roberta-base | 73.91560683904657 | 77.14103746689592 | 1Gb |
| [twmkn9/bert-base-uncased-squad2](https://huggingface.co/twmkn9/bert-base-uncased-squad2) | bert-base | 72.35932872655479 |  75.75355132564763 | 417.7mb |
| [twmkn9/distilroberta-base-squad2](https://huggingface.co/twmkn9/distilroberta-base-squad2) | distilroberta-base | 70.9279368213228 |  74.60439802429168 | 313.3 |
| [twmkn9/distilbert-base-uncased-squad2](https://huggingface.co/twmkn9/distilbert-base-uncased-squad2) | distilbert-base | 64.88976637051661 |  68.1776176526635 | 253.2mb |


## Domain Specific Language Model:

| models | Architecture | Language Modeling Domain | Model Size |
| --- | ---  |  --- | --- | 
| [microsoft/SportsBERT](https://huggingface.co/microsoft/SportsBERT) | BERT | sports articles | 357.5mb |
| [microsoft/BiomedNLP-PubMedBERT-base-uncased](https://huggingface.co/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract-fulltext) | BERT | Abstracts from PubMed and full-text articles from PubMedCentral |  420.1mb | 


 
## Tricks and Tips:

### Huggingface Trick:
1)  Download all files in Huggingface model directly 

![download image](/images/Directly%20Download.jfif)

2) Parallel Model Training:


![Parallel Model Training](/images/Parallel%20Model%20Training.jfif)

### General Tricks:

1) QUAIL Dataset: A better question answering Benchmark


![QUAIL dataset](/images/QUILDataset.jfif)

2) Stratified K Fold sampling for Multilabel by Abhishek Thakur:


![Stratified Fold](/images/stratified-fold%20for%20Multilabel%20Classification.jfif)

## Links and Blogs:

[AI Hub](https://aihub.cloud.google.com/u/0/s)

Word Embedding:
* [What is Word Embedding](https://machinelearningmastery.com/what-are-word-embeddings/)
* [Word Embeddings Transform Text Numbers](https://monkeylearn.com/blog/word-embeddings-transform-text-numbers/)
* [king man woman queen why](https://p.migdal.pl/2017/01/06/king-man-woman-queen-why.html)
* [word2vec-tutorial-the-skip-gram-model](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)
* [word2vec-tutorial-part-2-negative-sampling/](http://mccormickml.com/2017/01/11/word2vec-tutorial-part-2-negative-sampling/)

RNN Blogs:
* [sampling-strategies-for-recurrent-neural-networks](https://medium.com/machine-learning-at-petiteprogrammer/sampling-strategies-for-recurrent-neural-networks-9aea02a6616f)

LSTM:
* [Understanding LSTM](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* [LSTM Implementation](https://mlexplained.com/2019/02/15/building-an-lstm-from-scratch-in-pytorch-lstms-in-depth-part-1/)
* [time-series-prediction-lstm-recurrent-neural-networks-python-keras](https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/)
* [time-series-forecasting-long-short-term-memory-network-python](https://machinelearningmastery.com/time-series-forecasting-long-short-term-memory-network-python/)
* [multivariate-time-series-forecasting-lstms-keras](https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/)
* [multi-step-time-series-forecasting-long-short-term-memory-networks-python/](https://machinelearningmastery.com/multi-step-time-series-forecasting-long-short-term-memory-networks-python/)
* [Exploring LSTM](http://blog.echen.me/2017/05/30/exploring-lstms/)

Attention:

* [visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)

Transformers:
* [illustrated-transformer](http://jalammar.github.io/illustrated-transformer/)
* [transformers-attention-in-disguise](https://www.mihaileric.com/posts/transformers-attention-in-disguise/)
* [attention](http://nlp.seas.harvard.edu/2018/04/03/attention.html)
