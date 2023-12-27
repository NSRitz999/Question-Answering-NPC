# Question-Answering-NPC
The goal of this NLP project is to enhance player immersion by giving NPCs the ability to answer any questions given a context passage. This project is BERT-based and was trained using the SQuAD dataset and a custom NPC dataset.

# Training
The following three BERT models were used: BERT-base-uncased, DistilBERT-base-uncased, and RoBERTa-base. All models were trained on an A100 GPU. Additionally, the models were conducted in two major phases. The first phase was normal training on the SQuAD dataset. The second phase was LoRA fine-tuning on a custom NPC dataset.
