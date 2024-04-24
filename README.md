# Document Ranking Project

## Overview
This project focuses on the field of machine learning, particularly on ranking documents within search sessions. It utilizes a dataset formatted as a CSV file containing features that represent the relevance of documents to specific queries. Each entry in the dataset includes a `query_id` (representing the search session ID), features from `feature_0` to `feature_143` indicating various aspects of document relevance, and a `rank` indicating the relevance score of each document.

## Objective
The primary goals of this project were:
1. Load, inspect, and prepare the data.
2. Train a model that can accurately determine the `rank` of documents within the same `query_id` session.
3. Calculate ranking metrics, with a minimum requirement of calculating ndcg_5.
4. Organize and document the solution, then upload it to GitHub.

## Files
- **RankingDocuments.ipynb**: Jupyter notebook containing the entire solution, including data preparation, model training, and evaluation.
- **model.json**: Contains the trained machine learning model ready to be deployed or tested further.
