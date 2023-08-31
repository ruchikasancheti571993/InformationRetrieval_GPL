
# Workflow

# We start by indexing documents into a document store, and then perform searches with queries encoded by a retriever model. The retrieved contexts and the initial query are passed to a generator to produce an answer.


# InformationRetrieval_GPL

Introduction to GPL: GPL, which stands for Generative Pseudo Labeling, is a technique used to build models that can understand unstructured text data and respond to natural language queries about that data. It is described as a promising approach that combines various techniques and allows for the intelligent interpretation of text data.

Core Functionality: GPL's core functionality involves taking unstructured text data and using it to create models capable of comprehending the text. These models can then provide intelligent responses to questions or queries posed in natural language.

Potential Applications: GPL has significant potential across various industries and applications, with the ability to adapt to numerous use cases. It can be utilized to build high-performance language models using only plain text data.

Two Usage Modes: GPL can be applied in two primary ways:

Fine-Tuning Pretrained Models: GPL can be used as a technique to fine-tune pretrained models such as BERT. This involves taking a pretrained model and adjusting it to better understand specific domains or topics.
Domain Adaptation for Bi-Encoder Models: GPL can also be used for domain adaptation of bi-encoder models like SBERT. This allows existing sentence transformers to adapt to new topics or domains, even when labeled datasets for the new domain are scarce.
Importance of Domain Adaptation: Domain adaptation is emphasized as a valuable concept. It involves adapting models trained on existing datasets to understand new domains or topics lacking labeled data. This adaptation is particularly relevant for addressing events or developments that occurred after a model's training data cutoff, as illustrated by the example of pre-2019 models not being aware of COVID-19.

