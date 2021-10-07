# Brain Tumor Radiogenomic Classification

### Motivation

A malignant tumor in the brain is a life-threatening condition - with the worst prognosis, with median survival being less than a year.
MGMT promoter is a presence of a specific genetic sequence in the tumor - strong predictor of responsiveness to chemotherapy.
genetic analysis of cancer requires surgery to extract a tissue sample -  determine the genetic characterization of the tumor
Depending upon the results and type of initial therapy chosen, a subsequent surgery may be necessary.
If an accurate method to predict the genetics of the cancer through imaging (i.e., radiogenomics) alone could be developed, this would potentially minimize the number of surgeries and refine the type of therapy required.
predict the genetic subtype of the tumor.

### Stucture of data
Each independent case has a dedicated folder identified by a five-digit number. Within each of these “case” folders, there are four sub-folders, each of them corresponding to each of the structural multi-parametric MRI (mpMRI) scans, in DICOM format. The exact mpMRI scans included are:
* Fluid Attenuated Inversion Recovery (FLAIR)
* T1-weighted pre-contrast (T1w)
* T1-weighted post-contrast (T1Gd)
* T2-weighted (T2)


