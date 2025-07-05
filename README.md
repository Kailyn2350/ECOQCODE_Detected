# ECOQCODE Detection - Fine-Tuned YOLO Models

## About The Project

This repository hosts a collection of YOLO (You Only Look Once) models that have been fine-tuned for the specific task of detecting ECOQCODEs. This work is part of an internship project at **Aires Holding**, with the goal of developing an advanced AI for micro-printing recognition.

The models contained here are the results of various training runs, each with its own set of configurations and performance metrics.

## Project Goal

The primary objective of this project is to create a robust and accurate object detection model capable of identifying and localizing ECOQCODEs in various images. This serves as a foundational step in a larger initiative to build an AI system for micro-printing analysis.

## Directory Structure

Each main directory in this repository represents a unique training experiment. Inside each, you will find the following standard YOLO training outputs:

*   `weights/`: Contains the trained model weights.
    *   `best.pt`: The model checkpoint that achieved the best performance on the validation set.
    *   `last.pt`: The model checkpoint from the very last epoch of training.
*   `results.csv`: A CSV file containing detailed metrics for each training epoch (precision, recall, mAP, etc.).
*   `results.png`: A visual plot of the core training metrics over time.
*   `confusion_matrix.png`: A visualization of the model's classification performance on the validation set.
*   `P_curve.png`, `R_curve.png`, `PR_curve.png`, `F1_curve.png`: Plots for Precision, Recall, Precision-Recall, and F1-score curves.
*   `val_batch*_labels.jpg` / `val_batch*_pred.jpg`: Sample images from the validation set showing the ground truth labels and the model's predictions.

## Author

*   **Intern:** [KIM KYUSEOK]
*   **Company:** Aires Holding