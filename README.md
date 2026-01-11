# Functional connectivity changes in stroke patients Before and After Rehabilitation: A Pilot Nilearn-Based fMRI Analysis

# 1. Executive summary
Stroke rehabilitation induces neuroplastic changes within the motor network. In this pilot study, I used
publicly available resting-state fMRI datasets (n=5) to compare pre- and post-rehabilitation functional
connectivity patterns using Python and Nilearn. Connectivity matrices were computed using the HarvardOxford atlas, focusing on motor-related regions. By comparing connectivity matrices before and after
treatment, I identified mild increases in motor network integration, suggesting neural plasticity underlying
recovery.
# 2. Methods
2.1 Participants
- OpenNeuro dataset ID ds003999, the first 5 patients who underwent pre- and post-rehabilitation
interventions.
- Preprocessed resting-state fMRI scans, with motion correction and spatial normalization already applied.
2.2 Analysis Pipeline
1. Data Processing: I leveraged established neuroimaging tools (Nilearn) and adapted existing analysis
pipelines to address my research question about rehabilitation effects on brain connectivity.
2. Connectivity Analysis: Computed functional connectivity matrices
3. Statistical Testing: Compared pre- vs post-rehabilitation connectivity
4. Visualization: Created brain maps and network matrices heatmaps
5. Tools: Python, Google Colab, Nilearn 0.10+, Harvard-Oxford atlas
