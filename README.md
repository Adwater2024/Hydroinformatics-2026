# Hydroinformatics-2026 Assignment 1
# Streamflow Time-Series Analysis

## Description
Analysis of USGS streamflow data across different temporal scales for Assignment #1.

## Repository Structure

Hydroinformatics-2026/
 Data/                   # Streamflow data (NWIS) 
 notebooks/              # Jupyter notebooks
 homework_1.yml          # Conda environment
 README.md              # This file
.gitignore             # files ignored by git uploads

## Setup Instructions

### 1. Clone the repository
In bash
git clone https://github.com/Adwater2024/Hydroinformatics-2026.git
cd Hydroinformatics-2026


### 2. Create conda environment
In bash
conda env create -f homework_1.yml
conda activate homework_1


### 3. Data
Streamflow data is located in `Data/NWIS_Streamflow/` organized by state.

## Usage
In bash
# Activate environment
conda activate homework_1

## Author
Adam Cossey
University of Utah - Hydroinformatics 2026

## Assignment
Assignment #1: Reproducible Time-Series Analysis, Temporal Scaling, and Visualization
EOF
