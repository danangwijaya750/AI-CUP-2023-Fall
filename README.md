# AI Cup Source Code Documentation

## Project Title
AI CUP 2023 Fall Competition

## Description
Privacy and Medical Data Standardization Competition: Decoding Clinical Cases, Letting Data Tell the Story Competition.

## Team Information
  - Team name: TEAM_3879(Codalab account: Xiuyu223)
  - Private leaderboard: 0.864657 / Rank 8
  - Members: 
    - [侯秀瑜(Sally)](https://github.com/Xiuyu223)  
    - [曾繁斌(Royce)](https://github.com/trueroyce) 
    - [柯函君(Chloe)](https://github.com/hanchunkk)
    - [Danang Wijaya](https://github.com/danangwijaya750/)

## Table of Contents

- [AI Cup Source Code Documentation](#ai-cup-source-code-documentation)
  - [Project Title](#project-title)
  - [Description](#description)
  - [Team Information](#team-information)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Train and evaluate Task 1 Model](#train-and-evaluate-task-1-model)
  - [Task 1 Inference](#task-1-inference)
  - [Task 2 Inference from Task 1](#task-2-inference-from-task-1)
  - [Others Code](#others-code)

## Prerequisites
    torch == 2.1.1
    transformers == 4.35.2
    datasets == 2.15.0
    torch-crf == 0.7.2 

## Installation
    $ git clone https://github.com/danangwijaya750/AI-CUP-2023-Fall.git
    $ cd AI-CUP-2023-Fall
    $ pip install -r requirements.txt
    

## Train and evaluate Task 1 Model
  Train and Evaluate source code for Task 1  :
  - [Task1_CRF_training_single.ipynb](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Task1_CRF_training_single.ipynb)
  - [Task1_CRF_training_new.ipynb](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Task1_CRF_training_new.ipynb)

## Task 1 Inference
  Inference for Task 1 model :
  - [Task1_CRF_inference_single.ipynb](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Task1_CRF_inference_single.ipynb)

## Task 2 Inference from Task 1
   Task 2 Solution code :
  - [Task2.ipynb](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Task2.ipynb)
  
## Others Code 
  - [Result anlysis for Task 1](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Result_analysis.ipynb)
  - [Find Problem from predicted Task 1](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Find_problem.ipynb)
  - [Final Voting from all predicted models](https://github.com/danangwijaya750/AI-CUP-2023-Fall/blob/master/src/Final_voting.ipynb)