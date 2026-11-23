# LLM Preference Classification
# Overview
This project explores the development of a machining learning model capable of prediciting human preferences between two responses genereated by LLMs (large language models).

Using the data from the Kaggle LLM Classification Finetuning Competition, the goal is to predict whether or not a user prefers Response A or Response B from different LLM models. 

# Objectives
- Perform exploratory data anaylsis (EDA).
- Develop a baseline classification model.
- Fine-tune a pretrained transformer model.
- Evalute model performance using multiclass log loss.
- Generate predicitions for Kaggle submission.

# Dataset
Source: [Kaggle - LLM Classication Finetuning](https://www.kaggle.com/competitions/llm-classification-finetuning/)
The dataset contains the user prompt, as well as the response from both LLMs, and the user's preference.

# Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- ?

# Project Structure
- notebooks/ Data exploration and model expirimentation
- src/ Resuable python scripts
- reports/ Expirement logs and findings
- models/ Model configurations and checkpoints

# Progress
- [x] Project set-up
- [] Dataset exploration
- [] Data preprocessing
- [] Baseline model
- [] Transformer fine tuning
- [] Model evaluation
- [] Kaggle submission