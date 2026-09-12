MRS-Glioblastoma-Metabolite-Analysis
Multivoxel magnetic resonance spectroscopy analysis of metabolite patterns associated with glioblastoma multiforme.

This repository presents a research project investigating metabolic differences between tumoral and normal brain voxels in patients with glioblastoma multiforme (GBM) using multivoxel magnetic resonance spectroscopy (MRS).

The study focused on the analysis of brain metabolites and metabolite ratios that may help differentiate tumoral from normal brain voxels.

 Research Question
Which metabolites and metabolite ratios obtained from multivoxel proton magnetic resonance spectroscopy can help differentiate glioblastoma tumor voxels from normal brain voxels?

 Study Focus
- Glioblastoma multiforme (GBM)
- Magnetic resonance spectroscopy (MRS)
- Multivoxel MRS
- Brain metabolites
- Tumoral and normal voxels
- Neurochemical profiles
- Metabolite ratios
- Medical imaging

 Study Design
MRS data were collected from 8 patients diagnosed with glioblastoma multiforme.
Multivoxel MRS was performed using a 3 Tesla Siemens MRI scanner with a Point-Resolved Spectroscopy (PRESS) protocol.

Acquisition parameters included:
- TE = 135 ms
- TR = 1570 ms
- 1024 data points
A total of 170 tumoral voxels and 205 normal voxels were analyzed.

 MRS Processing
The MRS imaging region was determined using SIVIC, an open-source software framework for processing and visualization of MR spectroscopy data.
The MRS signals were processed and fitted using TARQUIN with the LCModel algorithm.

The analyzed metabolites included:
- NAA
- Phosphocholine (Pcho)
- Creatine (Cr)
- Lactate (Lac)
- Glutamine (Gln)
- Glutamate (Glu)
- N-Acetylaspartylglutamate (NAAG)
- Taurine (Tau)
- Glycine (Gly)

The area under the fitted metabolite signals was calculated using trapezoidal numerical integration in MATLAB.

 Statistical Analysis
Statistical analysis was performed to compare metabolite levels and metabolite ratios between tumoral and normal voxels.

The analysis included:
- Kolmogorov-Smirnov test
- Independent Samples t-test
- Mann-Whitney U test
- Pearson correlation
- ROC curve analysis

Statistical analysis was performed using SPSS.

 Main Findings
Several metabolites and metabolite ratios showed significant differences between tumoral and normal voxels.

Higher levels in normal voxels were observed for:
- Creatine (Cr)
- Glutamate (Glu)
- N-Acetylaspartate (NAA)
- N-Acetylaspartylglutamate (NAAG)
- Gly/Tau ratio

Higher levels in tumoral voxels were observed for:
- Glycine (Gly)
- Glutamine (Gln)
- Taurine (Tau)
- Lac/Cr
- Pcho/Cr
- Pcho/NAA
- Lac/NAA
- Gln/Glu

The Pcho/Cr ratio showed the highest diagnostic value among the evaluated parameters, with an area under the ROC curve (AUC) of 0.915.

 Research Workflow
Multivoxel MRS
        ↓
MRS Region Determination
        ↓
SIVIC Processing
        ↓
Metabolite Signal Fitting
        ↓
TARQUIN / LCModel
        ↓
Metabolite Quantification
        ↓
MATLAB Numerical Integration
        ↓
Statistical Analysis
        ↓
Tumoral vs. Normal Voxels
        ↓
ROC Analysis
        ↓
Diagnostic Metabolite Patterns

Software and Tools
•	SIVIC 
•	TARQUIN 
•	LCModel algorithm 
•	MATLAB 
•	SPSS 
Publication
Mansoory, M. S., Faramarzi, A., Khoshgard, K., & Mozafari, H. (2020).
Analysis of Glioblastoma Multiforme Tumor Metabolites Using Multivoxel Magnetic Resonance Spectroscopy.
Avicenna Journal of Medical Biotechnology, 12(2), 107–115.
Read the article
PubMed
Author
Ayob Faramarzi
Biomedical Engineering | Neuroimaging | fMRI | MRS | Brain Connectivity
