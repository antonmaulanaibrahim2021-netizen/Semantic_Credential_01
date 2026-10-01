# Semantic Knowledge-Enhanced Digital Academic Credential Consistency Assessment

## Purpose

This repository provides the source code, experimental configurations, and evaluation results for a research study on semantic knowledge-enhanced machine learning for digital academic credential consistency assessment.

The main objective of this project is to develop and evaluate a machine learning framework that can assess the semantic consistency of digital academic credentials by incorporating relationship-aware knowledge features among academic attributes, including institution, academic program, education level, and accreditation status.

This research investigates whether semantic knowledge representation can improve automated credential consistency assessment compared with conventional credential attribute-based approaches. The framework evaluates multiple supervised learning algorithms under different experimental scenarios, including baseline classification, semantic feature enhancement, group-based validation, and cross-institution evaluation.

## Overview

Digital academic credentials contain interconnected semantic relationships between institutional, academic, and accreditation attributes. Traditional credential verification approaches mainly focus on authenticity, integrity, and cryptographic validation, while semantic consistency assessment remains challenging.

This project implements a semantic knowledge-enhanced machine learning framework using an anonymized credential dataset containing 1,724 records and controlled inconsistency cases. The framework evaluates the capability of supervised learning models to identify credential consistency patterns and analyze the contribution of semantic relationship features.

## Research Objectives

The objectives of this research are:

1. To develop a machine learning-based framework for digital academic credential consistency assessment.

2. To investigate the impact of semantic knowledge features on credential consistency classification performance.

3. To compare conventional credential attributes and semantic-enhanced representations using supervised machine learning algorithms.

4. To evaluate model robustness through group-based and cross-institution validation strategies.

5. To provide a reproducible implementation supporting future research in intelligent academic credential verification systems.

## Repository Structure
(struktur folder)

## Dataset Description
(deskripsi dataset 1,724 records)

## Experimental Design
(Experiment A dan B)

## Machine Learning Models
(Logistic Regression, DT, SVM, RF)

## Evaluation Metrics
(Accuracy, Precision, Recall, F1, ROC-AUC)

## Reproducibility

This repository provides the experimental implementation required to reproduce the machine learning experiments reported in this study.

### Environment Setup

The experiments were implemented using Python. To reproduce the results, create a Python environment and install the required dependencies:

```bash
git clone https://github.com/USERNAME/semantic-credential-analysis.git

cd semantic-credential-analysis

pip install -r requirements.txt

## Citation

If you use this repository, the experimental framework, source code, or findings presented in this work, please cite the associated manuscript:

```bibtex
@article{AuthorYearSemanticCredential,
  title     = {Semantic Knowledge-Enhanced Machine Learning Framework for Digital Academic Credential Consistency Assessment},
  author    = {Anton Maulana Ibrahim, Tole Sutikno, Rusdy Umar},
  journal   = {Data Science and Management},
  year      = {2026},
  note      = {Manuscript under review}
}
