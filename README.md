# Bot Detection Experiments

This repository contains the code and datasets used for experiments on bot detection and classification. The dataset utilized in this project is sourced from the following paper:

> Tommaso Fagni, Fabrizio Falchi, Marco Gambini, Alberto Martella, and Maurizio Tesconi. 2021. TweepFake: About Detecting Deepfake Tweets. *PLOS ONE, 16(5):e0251415*.  
> Dataset link: [Kaggle - Twitter Deep Fake Text](https://www.kaggle.com/datasets/mtesconi/twitter-deep-fake-text/data)

## Dataset

The dataset includes pre-split training, validation, and test files, which can be found in the `dataset` folder.

### Task 1: Human vs. Bot Classification
The first task focuses on distinguishing between human-generated and bot-generated tweets.

### Task 2: RNN vs. GPT-2 Classification
The second task involves classifying bot-generated tweets to identify whether they are created using RNN-based or GPT-2-based methods.

## Code and Execution

All experiments for both tasks are implemented in the Jupyter notebook:
- **Notebook**: `task1_human_vs_bot_and_task2_rnn_vs_gpt2.ipynb`

Each step has already been executed, so you can directly view the results without needing to rerun the code.

## Citation

If you use this dataset or reference this project, please cite the original dataset paper as follows:

T. Fagni, F. Falchi, M. Gambini, A. Martella, and M. Tesconi.  
**TweepFake: About Detecting Deepfake Tweets.**  
*PLOS ONE, 16(5):e0251415, 2021.*  
DOI: [10.1371/journal.pone.0251415](https://doi.org/10.1371/journal.pone.0251415)
