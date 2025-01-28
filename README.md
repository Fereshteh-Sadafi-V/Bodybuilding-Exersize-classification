# Bodybuilding Exercise Classification (BEC) Project

Welcome to BEC project!

This is my final project for Artificial Intelligence course at University of Guilan, Iran.

## 1. Goal
In this project, we want to train a deep learning model for classifying bodybuilding exercise images into 3 classes (chestpress, deadlift, forearm).

## 2. Data
All data (about 630 original images) are collected from internet, and then data augmentation is done for increasing the dataset's size and diversity (20160 final images). All images are named after their corresponding data augmentation as you will see later in the notebook.

## 3. Training
I used transfer learning and worked with yolo11n-cls model from https://docs.ultralytics.com

## 4. Evaluation
* I calculate the metrics: precision, recall, f1_score, overall accuracy, macro-averaged precision, recall, f1-score and weighted-averaged precision, recall, f1-score for both validation dataset and test dataset in related sections.
* Also confusion matrix(original, normalized) for both datasets are available at: `BEC project/validation-yolo11ncls` and `BEC project/test-yolo11ncls`


**Note:** Please extract `logs-yolo11ncls`, `validation-yolo11ncls`, `test-yolo11ncls`, `data/train`, `data/val`, `data/test` into the same folder they already are.
