# RoboSurg: Surgical Skill Analysis and Medical Image Classification

## Overview

This repository contains machine learning implementations for surgical skill assessment and COVID-19 diagnosis from medical images. The project leverages kinematic surgical motion data and CT scans to develop classification systems for clinical applications.

## Features

### 🤖 Robotic Surgery Skill Classification

- Extract 22 motion parameters from surgical robot kinematics
- Analyse surgeon performance using metrics like:
  - Path length and completion time
  - Economy of motion (area and volume)
  - Motion smoothness and acceleration profiles
  - Tool coordination metrics
- Implement multiple classifiers:
  - Decision Tree ensembles with bagging
  - Random Forest with optimised tree count
  - K-Nearest Neighbors with customised distance metrics

### 🩻 COVID-19 CT Classification

- Diagnose COVID-19 from CT scans
- Implement advanced feature extraction with HOG
- Compare multiple classification approaches:
  - Linear and Quadratic Discriminant Analysis
  - Support Vector Machines with optimised kernels
- Handle class imbalance in medical datasets
- Comprehensive evaluation metrics

## Installation

```bash
# Clone repository
git clone https://github.com/username/robosurg.git
cd robosurg

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
