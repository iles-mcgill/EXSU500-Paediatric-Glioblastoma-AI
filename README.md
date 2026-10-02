# EXSU500-Paediatric-HGGs-AI
Automated 3D Multi-Class Image Segmentation of Pediatric High-Grade Gliomas from Multiparametric Magnetic Resonance Imaging (MRI) for Neurosurgical Navigation.

**Team Members:** Itzel Priscilla Aguilar-Valdez, Steven Gill, Iles Ousmer, Ansar Tlemussov

**Problem:**
Pediatric high-grade gliomas (pHGGs) are among the most aggressive tumors of the central nervous system, with five-year survival remaining below 20% (Fathi Kazerooni et al., 2026). For surgically accessible tumors, achieving maximal safe resection is clinically important. A comprehensive systematic review and meta-analysis of 37 studies encompassing 1,387 pediatric patients revealed that gross-total resection correlated with a 31% reduction in 1-year mortality risk (RR 0.69, 95% CI 0.56-0.83) and a 26% decrease in 2-year mortality risk (RR 0.74, 95% CI 0.67-0.83) in comparison to subtotal resection (Hatoum et al., 2022). Nonetheless, this association differed based on tumor site and was not evident for midline tumors, emphasizing that resection must remain anatomically and functionally safe (Hatoum et al., 2022).

Accurate delineation of tumor extent and its heterogeneous subregions on magnetic resonance imaging (MRI) is thus crucial for tumor characterization and treatment planning. However, manual three-dimensional tumor segmentation requires expert input, is time-consuming, and is susceptible to inter-observer variability. Prior studies assessing volumetric segmentation of high-grade gliomas indicated that expert manual segmentation took around 16 minutes per case, with significant discrepancies among expert segmentation. Meanwhile, semi-automated techniques markedly decreased the time needed for subsequent manual adjustments to an average of less than 2 minutes per case (Odland et al., 2015).

Automated segmentation has significant importance in pediatric neuro-oncology, a field where large, standardized imaging resources have traditionally been scarce. The BraTS-PEDs dataset offers multiparametric MRI data from 457 pediatric patients diagnosed with high-grade gliomas, predominantly DMGs, gathered from several institutions and consortia (Fathi Kazerooni et al., 2026). Of these patients, 257 comprise the training cohort and possess expert-validated voxel-level annotations that delineate enhancing tumor, non-enhancing tumor/core, cystic or necrotic components, and peritumoral edema (Fathi Kazerooni et al., 2026).

Our project therefore aims to develop and compare automated 3D multi-class segmentation models to identify and delineate distinct tumor subregions from multiparametric MRI, with the goal of improving the efficiency and consistency of tumor delineation.

**Task Type:**
Multi-class 3D Image Segmentation
Input: Multiparametric brain MRI (T1, contrast-enhanced T1, T2, and T2-FLAIR).  
Output: Voxel-wise segmentation of pediatric high-grade glioma subregions, which include enhancing tumor (ET), non-enhancing tumor (NET), cystic component (CC), and peritumoral edema (ED)

**Data Set:**
Name: BraTS-PEDs - The Brain Tumor Segmentation in Pediatric Magnetic Resonance Imaging 
Source: The Cancer Imaging Archive (TCIA)
Subjects: 457
Dataset Size: 32.7 GB

**Link to Data Set:** [TCIA BraTS-PEDs Collection](https://www.cancerimagingarchive.net/collection/brats-peds/)
