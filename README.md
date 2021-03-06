# EAT Classification Demo @ ISWC 2021

## Description

Understanding what a person is asking via a question is one of the first steps that humans use to find the corresponding answer. The same is true for Knowledge Graph Question Answering (KGQA) systems. In this regard, expected answer type (EAT) classification is an important part of the Question-Answering pipeline within such systems.
Our previous research on EAT classification [[1](https://github.com/Perevalov/eat_classification_ksem2021), [2](http://ceur-ws.org/Vol-2774/paper-01.pdf)] was mainly focused on data augmentation techniques including multilingual data.
In this [demo](https://webengineering.ins.hs-anhalt.de:41009/eat-classification), we extend our approach presented within [SMART Task @ ISWC 2020](https://smart-task.github.io) by predicting the most specific EAT and fetching its hierarchy from [DBpedia](http://mappings.dbpedia.org/server/ontology/classes/).
The provided functionality enables end-users to get the EAT predictions for [104 languages](https://github.com/google-research/bert/blob/master/multilingual.md#list-of-languages), see confidence of the prediction, and leave feedback.
In addition, the API enables researchers and developers to integrate the EAT classification into their systems.

## Quick Links

* [Online Demo](https://webengineering.ins.hs-anhalt.de:41009/eat-classification)
* [Open API](https://webengineering.ins.hs-anhalt.de:41020/docs)
* [SMART Task webpage](https://smart-task.github.io)
* [Extended multilingual datasets](https://github.com/Perevalov/iswc-classification/tree/master/datasets/DBpedia)
* [Original datasets](https://github.com/smart-task/smart-dataset)
