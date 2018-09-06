# Tracking Progress in Vietnamese NLP 

![](resources/icon.png)

This document aims to track the progress in Vietnamese Natural Language Processing and give an overview of the state-of-the-art (SOTA) across the most common NLP tasks and their corresponding datasets.

It aims to cover both traditional and core NLP tasks such as dependency parsing and part-of-speech tagging as well as more recent ones such as reading comprehension and natural language inference. The main objective is to provide the reader with a quick overview of benchmark datasets and the state-of-the-art for their task of interest, which serves as a stepping stone for further research. To this end, if there is a place where results for a task are already published and regularly maintained, such as a public leaderboard, the reader will be pointed there.

### Table of contents

* ![](resources/preprocess.png) Preprocess / Sentence Boundary Disambiguation / Language Detection / Spelling Correction
* Word Segmentation / Part-of-Speech Tagging / Chunking / Parsing
* Representation
* Text Classification / Sentiment Analysis
* [Named Entity Recognition](tasks/named_entity_recognition.md) / Relationship Extraction
* Coreference Resolution / Slotfilling / Entity Linking
* Knowledge Representation and Reasoning
* Semantics / Semantic Role Labeling
* [Machine Translation](tasks/machine_translation.md) / Automatic Summarization
* Language Generation / Question Answering / Dialog Systems and Chatbots
* Automatic Speech Recognition / Text To Speech / [Speech Classification](tasks/speech_classification.md)
* Optical Text Recognition

### Contributing

If you would like to add a new result, you can do so with a pull request (PR). 
In order to minimize noise and to make maintenance somewhat manageable, results reported
in published papers will be preferred (indicate the venue of publication in your PR);
an exception may be made for influential preprints. The result should include the name
of the method, the citation, the score, and a link to the paper and should be added
so that the table is sorted (with the best result on top).

If your pull request contains a new result, please make sure that "new result" appears
somewhere in the title of the PR. This way, we can track which tasks are the most
active and receive the most attention.

In order to make reproduction easier, we recommend to add a link to an implementation 
to each method if available. You can add a `Code` column (see below) to the table if it does not exist.
In the `Code` column, indicate an official implementation with [Official](http://link_to_implementation).
If an unofficial implementation is available, use [Link](http://link_to_implementation) (see below).
If no implementation is available, you can leave the cell empty.

| Model           | Score  |  Paper / Source | Code | 
| ------------- | :-----:| --- | --- | 
| |  |  | [Official](http://link_to_implementation) | 
| |  |  | [Link](http://link_to_implementation) |

To add a new dataset or task, follow the below steps. Any new datasets
should have been used for evaluation in at least one published paper besides 
the one that introduced the dataset.

1. Fork the repository.
2. If your task is completely new, create a new file and link to it in the table of contents above.
If not, add your task or dataset to the respective section of the corresponding file (in alphabetical order).
3. Briefly describe the dataset/task and include relevant references. 
4. Describe the evaluation setting and evaluation metric.
5. Show how an annotated example of the dataset/task looks like.
6. Add a download link if available.
7. Copy the below table and fill in at least two results (including the state-of-the-art)
  for your dataset/task (change Score to the metric of your dataset).
8. Submit your change as a pull request.
  
| Model           | Score  |  Paper / Source | Code | 
| ------------- | :-----:| --- | --- | 
|  |  |  | | 

