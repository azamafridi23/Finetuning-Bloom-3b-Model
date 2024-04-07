
# Finetuning LLama2 using PEFT (LoRA)

This repository provides guidelines and resources for finetuning the Bloom 3b (Large Language Model) using the PEFT (Parameter Efficient Finetuning) technique, specifically the LoRA (Low-resource Adaptation) variant.

# Dataset:
### Name: squad-v2
### Link: https://huggingface.co/datasets/rajpurkar/squad_v2
### Description: 
- Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.

- SQuAD 2.0 combines the 100,000 questions in SQuAD1.1 with over 50,000 unanswerable questions written adversarially by crowdworkers to look similar to answerable ones. To do well on SQuAD2.0, systems must not only answer questions when possible, but also determine when no answer is supported by the paragraph and abstain from answering.

# Usage:
- Clone the Repository
- Open the "Simple_LoRA_Implementation.ipynb" notebook in jupyter 
- Install the required libraries mentioned in the jupyter notebook
- Run all the cells.