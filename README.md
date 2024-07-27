# Forensic-DNA-profiling-classifier
# DNA Analysis for Disaster Victim Identification

## Overview

This repository contains the implementation of a comprehensive framework for DNA analysis post-natural disasters. Our method combines DNA sequencing, machine learning classification, and gene matching to expedite the identification of disaster victims.

## Abstract

Our work streamlines DNA analysis post-natural disasters by comparing Short Tandem Repeat (STR) regions. This method integrates DNA sequencing, machine learning classification, and gene matching on a diverse real-world dataset. We applied correlation matrices and feature selection to understand dataset features, and utilized confusion matrices for training and testing. The integration of Convolutional Neural Networks (CNNs), Naïve Bayes classifiers, and other techniques enhances classification and analysis, determining the matching percentage of unknown DNA against a known dataset. Our framework expedites DNA analysis, simplifying disaster victim identification, saving time and resources, and addressing complex DNA mixtures in disaster scenarios.

## Keywords

- Short Tandem Repeat regions
- Convolutional Neural Networks
- Naïve Bayes classifier
- Smith-Waterman algorithm
- DNA profiling

## Introduction

In the aftermath of natural disasters, DNA analysis and machine learning are pivotal in reuniting victims with their loved ones. This project collects DNA samples from disaster victims and employs advanced analysis and machine learning algorithms to achieve its primary goal of identification.

### Goals

- **DNA Sequence Classification:** Leveraging deep learning, particularly Convolutional Neural Networks, to navigate challenges in genomic data analysis and provide precise and efficient identification of victims.
- **Feature Extraction:** Utilizing CNNs for automated feature extraction from complex datasets, including DNA sequences.
- **Evaluation:** Rigorous evaluation using diverse DNA sequences for automating DNA analysis.
- **Victim Identification:** Combining DNA analysis and machine learning to expedite victim identification, restoring closure, and providing comfort to grieving families.

### Methods

- **Short Tandem Repeat (STR) Analysis:** STR regions within DNA sequences are highly variable among individuals, making them useful for DNA profiling and forensic identification. By analyzing variations in the number of repeats at specific STR loci, unique genetic profiles are created for individuals.
- **Smith-Waterman Algorithm:** A dynamic programming algorithm used for local sequence alignment in bioinformatics. It compares two sequences to find the optimal local alignment, crucial for accurately identifying and comparing DNA sequences.
- **Naïve Bayes Classifier:** Enhances the project's ability to classify and profile DNA samples, contributing to overall identification accuracy.

## Technologies Used

- **DNA Sequencing**
- **Machine Learning**
- **Convolutional Neural Networks (CNNs)**
- **Naïve Bayes Classifier**
- **Smith-Waterman Algorithm**

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/DNA-Analysis-Disaster-Victim-Identification.git
    ```

2. Navigate to the project directory:
    ```bash
    cd DNA-Analysis-Disaster-Victim-Identification
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Detailed instructions on how to run the analysis will be provided here. This section should include commands and explanations on how to:

1. Prepare and preprocess DNA samples.
2. Train machine learning models.
3. Perform DNA matching using the Smith-Waterman algorithm.
4. Evaluate the results using confusion matrices and other metrics.



