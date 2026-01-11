# 🧠Functional connectivity changes Following Post-Stroke Rehabilitation

# Overview
This project explores resting-state functional connectivity changes before and after stroke rehabilitation using an atlas-based ROI approach. The analysis focuses on motor-related cortical regions to assess network-level changes associated with recovery.

The project is intended as a methodological demonstration and exploratory analysis, not a definitive clinical inference. 
# Datasets
✅Source: OpenNeuro (ds003999)

✅Subjects: 5

✅Sessions: Pre-rehabilitation and Post-rehabilitation

✅Modality: Resting-state fMRI

# Methods
## Preprocessing ## 
Preprocessed resting-state fMRI scans, with motion correction and spatial normalization already applied.

## ROI Definition ##

Atlas: Harvard–Oxford Cortical Atlas (2mm)

## Motor ROIs selected based on anatomical labels ##

✅Precentral gyrus

✅Postcentral gyrus

✅Supplementary Motor Area

## Connectivity Analysis ##

✅Time series extraction: NiftiLabelsMasker

✅Standardization: z-score (sample-wise)

✅Connectivity metric: Pearson correlation

✅Connectivity matrices computed per subject

✅Mean connectivity computed separately for pre and post sessions

# Visualizations

✅Connectivity matrices

✅Glass brain projection of connectivity change

✅Network-level motor connectivity visualization

# Results (Exploratory)

✅Mean motor network connectivity increased post-rehabilitation

✅Average within-motor connectivity change: ~0.09 (correlation units)

These findings are descriptive and intended to illustrate connectivity analysis workflows rather than establish statistical significance.
# Limitations

✅ Small sample size (n=5) limits statistical power

✅ No specific rehabilitation protocol examined

✅ Study characteristics could affect statistical output

✅ Length of rehabilitation not clearly stated
# Future Directions

✅Subject-level statistical testing

✅Inclusion of motion and physiological confounds

✅Larger participant cohort to validate findings

✅Longitudinal tracking to assess persistence of changes

✅Correlation with clinical outcome measures and Comparison across different rehabilitation approaches
# Technologies

✅Python

✅Nilearn


✅NumPy

✅Matplotlib

✅Google Colab

✅DataLad

# Author
Dr. Yonatan Yotora

General Practitioner | Neuroscience Research Aspirant
