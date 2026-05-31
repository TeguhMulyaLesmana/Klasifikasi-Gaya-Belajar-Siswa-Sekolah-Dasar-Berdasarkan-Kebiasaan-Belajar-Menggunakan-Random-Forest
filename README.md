# Learning Style Classification Using Random Forest

## Overview

This project implements a Random Forest algorithm to classify elementary school students' learning styles based on their learning habits. The classification categories are:

* Visual
* Auditory
* Kinesthetic

This study was conducted as part of an undergraduate thesis in Informatics Engineering at Universitas Muhammadiyah Sukabumi.

## Research Objective

The purpose of this project is to identify students' learning styles using learning habit data, helping teachers better understand students' learning preferences.

## Dataset

The dataset consists of learning habit indicators collected through questionnaires. To protect privacy, personally identifiable information has been removed from the published dataset.

Features used:

* Intensitas_Belajar
* Fokus_Belajar
* Disiplin_Belajar
* Interaksi_Belajar
* Teknologi
* Lingkungan_Belajar
* Waktu_Efektif

Target:

* Gaya_Belajar (Visual, Auditory, Kinesthetic)

## Methodology

1. Data preprocessing
2. Label encoding
3. Train-test split
4. Random Forest Classification
5. Hyperparameter tuning using RandomizedSearchCV
6. Cross-validation
7. Model evaluation using confusion matrix and classification metrics

## Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab

## Repository Structure

* Data_siswa.csv : Dataset
* Klasifikasi_gaya_belajar.ipynb : Research notebook
* Klasifikasi_gaya_belajar.py : Python implementation
* README.md : Project documentation

## Author

Teguh Mulya Lesmana

Bachelor Thesis Project
Informatics Engineering
Universitas Muhammadiyah Sukabumi
