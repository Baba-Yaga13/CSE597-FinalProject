Composed Image Retrieval: CSE 597 Course Project

This repository contains the implementation for the project "Composed Image Retrieval using Contrastive Learning and Task-oriented CLIP-based Features."

Overview

This project addresses the task of composed image retrieval, which involves retrieving target images similar to a reference image but modified based on a textual query. The project implements a state-of-the-art (SOTA) method, fine-tunes the model, and evaluates performance on benchmark datasets.

Structure

The repository includes the following files and directories:

Run.ipynb: Main file to execute the project.

Pretrained Model Files: Available within this repository in case the environment setup does not require cloning.

Source Code: Scripts for fine-tuning, feature extraction, and evaluation.

How to Run

Option 1: Use Run.ipynb (Cloning Required)

The Run.ipynb file contains all necessary commands to:

Clone the repository with the pretrained models and source code.

Setup the environment.

Execute the fine-tuning and evaluation steps.

Option 2: Use Local Files

The repository already includes all necessary files (pretrained models and source code). If you prefer using these files instead of cloning:

Skip the cloning commands in Run.ipynb.

Directly proceed to execute the fine-tuning and evaluation steps.

Requirements

The project requires the following dependencies:

Python 3.8+

PyTorch

torchvision

transformers

Additional libraries listed in requirements.txt

Install the dependencies using:

pip install -r requirements.txt

Datasets

The project uses:

FashionIQ

CIRR

Ensure the datasets are properly downloaded and paths are updated in the configuration.

Results

The implementation includes both basic and fine-tuned results. Fine-tuning showed significant improvements over the baseline results. Refer to the Results section in the Run.ipynb for detailed metrics.

Citation

If using this repository, cite the original paper:

Alberto Baldrati, et al., "Composed Image Retrieval using Contrastive Learning and Task-oriented CLIP-based Features," 2022.

Feel free to explore the repository and adapt it for your projects. For any queries, contact the author at yashovardhan@university.edu.

