# Projects

## Research projects at UNIMIB - 2022..2023
The projects mainly involved Fine-grained Entity Typing (FET), an NLP task that aims to identify the specific type of an entity mentioned in a text (e.g., in _"[Barack Obama] won the election in 2008"_, _[Barack Obama]_ can be classified as _person/president_) according to a type hierarchy.
The projects include a wide number of experiments on benchmark datasets, involving different encoding strategies (i.e., BERT-based fine-tuned with adapters, ELMo, GloVe), prompt-based methods, Neuro-Symbolic Integration, and other state-of-the-art approaches.

The experiments have been executed through the [Entity Typing Framework](https://github.com/NooneBug/entity_typing_framework), a framework co-developed with [@NooneBug](https://github.com/NooneBug) based on PyTorch Lightning CLI. The framework is module-oriented and can be easily integrated with new input encoders, neural classifiers, loss functions, inference strategies, loggers, data loaders, and training/validation/test routines. Each implementation of the above mentioned components can be combined in several ways by simply defining `config.yaml` files. The metrics and training stats of each run are automatically logged to [wandb.ai](https://wandb.ai/site).

The most relevant experiments have been carried out in the following scenarios:
1. [Full-fledged](https://github.com/christianbernasconi96/et_standard_experiments) (milions of training examples available)
2. Zero/[Few-shot class incremental learning](https://github.com/christianbernasconi96/et_specialization_experiments)
3. [Few-shot domain adaptation](https://github.com/christianbernasconi96/et_cross_dataset_experiments)

## "Datalake per Giustizia" - 2022
"Datalake per Giustizia" is an italian national project involving the application of different NLP techniques to process, manage, and extract information from legal italian documents (e.g., anonymization, NER, NEL, clustering, relation extraction, etc.). My main focus was on the model specialization in low data scenario to reduce the labeling and retraining costs. Zero-shot and few-shot Fine-grained Entity Typing experiments have been carried out to study the adaptation of a BERT-based neural network to classify new fine-grained types added to the type ontology. More in detail, experiments involve the use of prompt-based methods, Neuro-Symbolic Integration techniques, and other state-of-the-art approaches to exploit the knowledge of known types to favor the learning process of new types.

_**NOTE:** Paper being written. The code will be soon publicly available on a dedicated repository._

## Neuro-Symbolic Fine-grained Entity Typing with KENN - 2021
Project for the Master Thesis in Computer Science. This work aims to exploit the type dependencies of a Fine-grained Entity Typing (FET) dataset by injecting prior knowledge into a FET Neural Network. More in detail, the hierarchical type dependencies (e.g., specialization of types) are encoded into logical rules to be injected into a neural model through the Neuro-Symbolic Integration framework KENN. The project covers many analysis and experiments on two state-of-the-art FET datasets, with an architecture designed to use BERT-based encoders and Neural Networks combined with a logical component.

The thesis and final presentation are available on the [repository](https://github.com/christianbernasconi96/MasterThesis).

## Question Answering: Structured vs Unstructured - 2021
The project aims to explore and compare Open-Domain Question Answering approaches over both structured (Knowledge Graph) and unstructured (Free-text) data. In particular, the project involves the use of BERT, Neural Networks, Named Entity Recognition, Named Entity Linking, and part-of-speech tagging.

The code and presentation are available on the [repository](https://github.com/christianbernasconi96/QuestionAnsweringComparison).

## Toxic Comments Classification Challenge - 2021
The project faces a multilabel classification problem on textual data. In particular, the project experiments different neural architectures, involving LSTM, GRU, and CNN. Moreover, several techniques of text preprocessing, data augmentation, and text encoding (e.g., BERT) are involved. 

The code, report, and presentation are available on the [repository](https://github.com/christianbernasconi96/ToxicCommentChallenge).

## Personalized Search Engine - 2021
The project consists in an implementation of a personalized search engine using Elastic Search on dinamically collected tweets. More in detail, the project involves different text preprocessing operations, customized search modalities, and automatic generation of a user profile based on the information extracted from its tweets.

The code, report, and presentation are available on the [repository](https://github.com/christianbernasconi96/PersonalizedSearchEngine).

## Clothing Recommendation - 2021
The project has the main goal to retrieve clothes that are similar to a provided photo. More in detail, Neural Networks are involved both to extract features and to classify an image. For the retrieval, the images are indexed through Approximate Nearest Neighbors algorithms.

The code and presentation are available on the [repository](https://github.com/christianbernasconi96/ClothingRecommendation).

## Amazon's Products Analysis - 2020
The project aims to analayze a network of Amazon's products and covers several topics, including Sentiment Analysis on the reviews, Information Extraction from the descriptions of the products, and network analysis to detect communities and discover insights about the products. Various information is extracted from text to describe a community of products (e.g., Named Entity Recognition to find the most frequent entities).

The code, report, and presentation are available on the [repository](https://github.com/christianbernasconi96/ProductNetworkAnalysis).

## FEIII 2016 Challenge - 2020
The project is based on the [FEII2016 challenge](https://ir.nist.gov/feiii/2016-challenge.html) and aims to explore different Record Linkage techniques. In particular, the project involves different text elaboration steps, followed by a classification step performed by supervised/unsupervised ML approaches.

The code, report, and presentation are available on the [repository](https://github.com/christianbernasconi96/FEII2016Challenge).

## Automatic Generation and Check of Constraints on RDF Graphs - 2019
Project for the Bachelor Thesis in Computer Science. The project has the goal to automatically generate SHACL constraints to validate an RDF graph by detecting the presence of data inconsistencies that need to be manually fixed.

The thesis and final presentation are available on the [repository](https://github.com/christianbernasconi96/BachelorThesis).
