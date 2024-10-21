## This repository contains the solution to the two-part challenge for INNOV8: The Space Saga, where we classify alien species based on intercepted communications and design a system to predict troop betrayal in an intergalactic war.

## Project Breakdown
Part 1: Alien Communication Classification
Part 2: Predicting Troop Betrayal

# Part 1: Alien Communication Classification
## Objective
The task is to predict the species of aliens from intercepted messages and their associated attributes such as the number of fingers and whether they have a tail. The goal is to build a machine learning model that accurately predicts the species for a new set of intercepted communications.

## Solution
Dataset: data.csv includes the messages, number of fingers, and tail presence for various alien species. The task is to classify these based on the features provided.
Test Data: test.csv contains messages for which we need to predict the species.
Output: The predictions are saved in result.csv.
Approach
Data Preprocessing:

Text data (alien messages) is processed using techniques like tokenization and vectorization (e.g., TF-IDF or CountVectorizer).
Features such as "number of fingers" and "tail presence" are handled appropriately (scaling or encoding).
Modeling:

Various classification algorithms like Random Forest, SVM, and Gradient Boosting were explored.
The best-performing model was selected based on cross-validation and accuracy on a validation set.
Evaluation:

The model was evaluated based on prediction accuracy on a hold-out validation set.
Hyperparameters were fine-tuned to improve performance.
Final Predictions:

The final species predictions for test.csv are stored in result.csv

# Part 2: Predicting Troop Betrayal
## Objective
The goal is to design a decision-making system that predicts which soldiers in an army are likely to betray their faction based on factors such as greed, temptation, and respect.

## Approach
Feature Engineering:

Based on various hypotheses, relevant factors were identified that could indicate betrayal (e.g., historical behavior, interaction with other soldiers, level of respect).
These factors were converted into quantifiable features for the decision-making system.
Workflow:

A scalable system was designed to rank soldiers based on their betrayal risk. This system adapts as new data is added over time, ensuring better predictions.
No Code Submission:

Since Part 2 focused on the thought process and system design, the submission includes a detailed PDF report outlining the approach.
