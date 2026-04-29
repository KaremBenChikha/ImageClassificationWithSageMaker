# Image Classification with SageMaker

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_SageMaker-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

Simple image classification using AWS SageMaker to train and deploy a model in the cloud.

## Overview

This project demonstrates how to build and train an image classification model using Amazon SageMaker. The Jupyter notebook runs on AWS infrastructure with data stored in S3.

## Contents

- `ImageClassification.ipynb` — Main training notebook

## Architecture

- **Compute**: AWS SageMaker (managed ML instances)
- **Storage**: Amazon S3
- **Runtime**: Jupyter Notebook via AWS Console

## Usage

1. Upload the notebook to AWS SageMaker
2. Configure the S3 bucket for training data
3. Run all cells

## Dependencies

- AWS account with SageMaker access
- S3 bucket for data storage
