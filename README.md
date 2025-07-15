# Brain Stroke Classification using Deep Learning

This repository contains the final project for the course *Honours Class Data Science*, completed by Group 5. The goal of the project was to develop a deep learning model to classify brain scans into three clinically relevant categories: ischemic stroke, hemorrhagic stroke, and normal brain.

## Project Description

This project investigates the use of deep learning for stroke classification based on brain CT imaging. The goal is to automatically identify three stroke categories:

- **Ischemic stroke** – caused by a blocked blood vessel  
- **Hemorrhagic stroke** – caused by bleeding in or around the brain  
- **Normal brain** – no signs of stroke  

Accurate classification is important, as each type of stroke requires a different treatment.

A pretrained **ResNet18** model was fine-tuned on labeled axial brain CT scans. Model performance was evaluated using accuracy, precision, recall, and confusion matrices, with the F1-score as the primary metric. Training curves and prediction examples are also included. To better understand incorrect predictions, Grad-CAM was applied as an explainable AI method to highlight the image regions that influenced the model's output.

The ResNet18 model achieved an accuracy of **97%** and performed well in distinguishing between ischemic and hemorrhagic strokes. These results indicate that deep learning models can support stroke diagnosis and triage in clinical settings.

Further details on the methodology, training process, and results are provided in the [written report](https://semdegroot.github.io/CT_Classification/Report_HCDS_Group5.pdf).

## Repository Contents

- `group_5_brain_stroke.ipynb`: Jupyter Notebook containing all code.
- `Report_HCDS_Group5.pdf`: Final report with a complete description of the project background, goals, methods, results, and discussion.

## Report Access

The report can be accessed via [https://semdegroot.github.io/CT_Classification/Report_HCDS_Group5.pdf](https://semdegroot.github.io/CT_Classification/Report_HCDS_Group5.pdf)
