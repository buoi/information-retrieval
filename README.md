# Information retrieval on SQuAD
IR + QA system on Wikipedia articles

This repository holds code for the Information Retrieval part of our project work for NLP2020 class by Paolo Torroni @unibo.

We tackle the IR problem with a classic tf-idf approach and with a contrastive Bi-Encoder model based on ELECTRA.  
An in depth description of the work can be found here: [QA-IR-report.pdf](https://github.com/buoi/question-answering/raw/main/QA-IR-SQUAD.pdf).

<img width="774" alt="Schermata 2022-04-21 alle 17 08 19" src="https://user-images.githubusercontent.com/38630200/164488733-1b0676e8-dcc8-4ba7-b795-06114b5f5f3e.png">


## Experiment plots
https://wandb.ai/veri/IR/reports/IR--Vmlldzo1Mzk3MDc
## Branches
- `main`: merged from the `tfidf` branch
- `tfidf`: tf-idf performances on SQuAD v1.1
- `electra`: neural model performances on SQuAD v1.1
- `deploy`: contains the end to end notebook that performs the IR + QA task and other files used to deploy the system, where the QA model is trained on SQuAD v2
