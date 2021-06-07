# ParaQA
## A Question Answering Dataset with Paraphrase Responses for Single-Turn Conversation
The dataset was created using a semi-automated framework for generating diverse paraphrasing of the answers using techniques such as back-translation. The existing datasets for conversational question answering over KGs (single-turn/multi-turn) focus on question paraphrasing and provide only up to one answer verbalization. However, ParaQA contains 5000 question-answer pairs with a minimum of two and a maximum of eight unique paraphrased responses for each question. We complement the dataset with baseline models and illustrate the advantage of having multiple paraphrased answers through commonly used metrics such as BLEU and METEOR. ParaQA dataset is publicly available on a persistent [URI](https://figshare.com/projects/ParaQA/94010) for broader usage and adaptation in the research community.

## Generation Framework & Baseline models
Alongside the dataset, we provide the framework for generating multiple paraphrase response and the baseline models. Due to the free distributed license agreement, you can find them in [another repository](https://github.com/barshana-banerjee/ParaQA_Experiments).

## License
The dataset is under [Attribution 4.0 International (CC BY 4.0)](LICENSE)

## Cite
```bash
@InProceedings{10.1007/978-3-030-77385-4_36,
author="Kacupaj, Endri
and Banerjee, Barshana
and Singh, Kuldeep
and Lehmann, Jens",
editor="Verborgh, Ruben
and Hose, Katja
and Paulheim, Heiko
and Champin, Pierre-Antoine
and Maleshkova, Maria
and Corcho, Oscar
and Ristoski, Petar
and Alam, Mehwish",
title="ParaQA: A Question Answering Dataset with Paraphrase Responses for Single-Turn Conversation",
booktitle="The Semantic Web",
year="2021",
publisher="Springer International Publishing",
address="Cham",
pages="598--613",
abstract="This paper presents ParaQA, a question answering (QA) dataset with multiple paraphrased responses for single-turn conversation over knowledge graphs (KG). The dataset was created using a semi-automated framework for generating diverse paraphrasing of the answers using techniques such as back-translation. The existing datasets for conversational question answering over KGs (single-turn/multi-turn) focus on question paraphrasing and provide only up to one answer verbalization. However, ParaQA contains 5000 question-answer pairs with a minimum of two and a maximum of eight unique paraphrased responses for each question. We complement the dataset with baseline models and illustrate the advantage of having multiple paraphrased answers through commonly used metrics such as BLEU and METEOR. The ParaQA dataset is publicly available on a persistent URI for broader usage and adaptation in the research community.",
isbn="978-3-030-77385-4"
}
```
