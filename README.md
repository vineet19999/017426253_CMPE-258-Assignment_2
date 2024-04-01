# 0174426253_CMPE-258-Assignment_2
# CMPE 258 Assignment 2 Overview

## Introduction
This assignment is a part of the curriculum for the CMPE 258 course, aimed at the development and training of deep learning models. This particular task requires students to engage with various datasets and employ different model architectures, with a focus on using PyTorch.

## Pre-requisites
To successfully run this project, the following installations are necessary:
- Python (version 3.8 or newer)
- The PyTorch library along with torchvision
- Visual Studio Code (VSCode) for an integrated development environment

## Initial Setup
To begin, clone the project repository to your local device using Git commands.

## Execution Instructions
The project is configured to run within VSCode, leveraging settings specified in the `.vscode/launch.json` file.

### Execution Steps:
1. Launch VSCode and open the project's folder.
2. Navigate to the 'Run and Debug' section (accessible via `Ctrl+Shift+D`).
3. From the dropdown menu, select your desired configuration for execution. Available options include:
   - `Python: Current File` to execute the open Python script.
   - `Python: MyTorchTrainer` to run the `myTorchTrainer.py` file with designated arguments for model training.
4. Click the 'Run' button or press `F5` to initiate the program.

### Parameter Adjustments
For custom runs of `myTorchTrainer.py`, adjust the `args` array within the `launch.json` configuration for `Python: MyTorchTrainer`. Parameters include:
- `--data_name`: Specifies the dataset name (e.g., `PISTACHIO DATASET`).
- `--data_type`: Defines the dataset category (e.g., `torchvisiondataset`).
- `--data_path`: Indicates the directory where data is stored.
- `--model_name`: Identifies the model for use (e.g., `mlpmodel1`).
- `--learningratename`: Describes the learning rate schedule (e.g., `StepLR`).
- `--optimizer`: Determines the optimization algorithm (e.g., `Adam`).

## Project Contributors
The project has been developed and is maintained by VINEET SAMUDRALA.
