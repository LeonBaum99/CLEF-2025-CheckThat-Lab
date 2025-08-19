# CheckThat-Lab-at-CLEF-2025

The Conference and Labs of the Evaluation Forum (CLEF) contributes to the scientific advancement of information access systems. It hosts labs, such as the CheckThat lab focusing on fact checking. Refer to the official website at https://clef2025.clef-initiative.eu/index.php?page=Pages/labs.html.

## Project overview

This project addresses the information retrieval challenge CheckThat! Task 4b, which aims to retrieve the most relevant research papers mentioned in social media posts. The presented solutions and approaches were at the top of the competition's leaderboard. They were summarised in a paper and published in the CLEF 2025 proceedings. Find the publication here:

- *will be added once published in september 2025*

Further resources:
- The original materials to get started with the challenge can be found at: https://gitlab.com/checkthat_lab/clef2025-checkthat-lab/-/tree/main/task4/subtask_4b
- The official challenge website is: https://checkthat.gitlab.io/clef2025/task4/ 
- For challenge submissions and leaderboards refer to: https://codalab.lisn.upsaclay.fr/competitions/22359  

## File structure

- `data`
    - query files: contain the tweets that mention scientific resources split up in train, dev and test queries as well as the gold labels pointing to a single publication from the collection file
    - collection file: contains metadata of scientific publications
- `code` 
    - code that reproduces the experiments described in the paper
- `predictions`
    - includes the predictions obtained using various approaches


## Requirements
Use the following command to install the necessary dependencies before running the code:

```bash
pip install -r requirements.txt
```

## Reference

If you want to use this work in any kind, please cite the following information:

```bibtex
@InProceedings{clef-checkthat:2025:task4:AIRwaves,
author = {Ashbaugh, Cem and Baumgärtner, Leon and Greß, Tim and Sidorov, Nikita and Werner, Daniel},
title = "AIRwaves at CheckThat! 2025: Retrieving Scientific Sources for Implicit Claims on Social Media with Dual Encoders and Neural Re-Ranking",
year = {2025},
booktitle = "Working Notes of CLEF 2025 - Conference and Labs of the Evaluation Forum",
series = {CLEF~'2025},
address = {Madrid, Spain},
crossref = "clef2025-workingnotes"
}
```


 
     



