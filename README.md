# CheckThat-Lab-at-CLEF-2025
Lab at CLEF 2025Subtask 4b (Scientific Claim Source Retrieval)

## Project overview

Documentation of Group 20 in the course Advanced Information Retrieval (AIR) at TU Wien. It aims to address the information retrieval challenge CheckThat! Task 4b, which aims to retrieve the most relevant research papers mentioned in social media posts.

- The original materials to get started with the challenge can be found at: https://gitlab.com/checkthat_lab/clef2025-checkthat-lab/-/tree/main/task4/subtask_4b
- The official challenge website is: https://checkthat.gitlab.io/clef2025/task4/ 
- For challenge submissions and leaderboards refer to: https://codalab.lisn.upsaclay.fr/competitions/22359  

## File structure

- Data folder
    - query files - contain the tweets that mention scientific resources:
        - data\subtask4b_query_tweets_train.tsv
        - data\subtask4b_query_tweets_dev.tsv
        - data\subtask4b_query_tweets_test_gold.tsv
    - collection file - contains scientific resources:
        - subtask4b_collection_data.pkl
- Code folder
    - jupyter notebooks that implement the approaches
        - Sparse Retrieval BM25     
        - Neural Representation Learning
        - Neural Reranking
- Predictions folder
    - includes the predicted papers for the different query sets

requirements.txt
A text file containing all necessary Python packages required to run the project scripts. Use the following command to install these dependencies:

```bash
pip install -r requirements.txt

Python Version 3.10.16

## Reference

If you want to use this work in any kind, please cite the following information:


 
     



