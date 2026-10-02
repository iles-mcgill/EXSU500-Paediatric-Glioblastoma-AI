# EXSU500-Paediatric-HGGs-AI
Automated 3D Multi-Class Image Segmentation of Paediatric High-Grade Gliomas from Multiparametric Magnetic Resonance Imaging (MRI) for Neurosurgical Navigation.

**Team Members:** Itzel Priscilla Aguilar-Valdez, Steven Gill, Iles Ousmer, Ansar Tlemussov

**Problem:**
Paediatric central nervous system tumours, particularly high-grade gliomas, have a dismal prognosis, with a five-year survival rate historically sitting below 20% (TCIA, 2025). The surgical treatment of these tumours is exceptionally challenging because high-grade gliomas are diffuse and highly infiltrative. This makes it incredibly difficult to identify precise tumour margins during surgery, where the accidental resection of healthy neural networks can lead to severe neurological deficits or death.

Accurate delineation of tumor extent and its heterogeneous subregions on magnetic resonance imaging (MRI) is thus crucial for tumor characterization and treatment planning. However, manual three-dimensional tumor segmentation requires expert input, is time-consuming, and is susceptible to inter-observer variability (Odland et al., 2015).

Our project therefore focuses on the automated 3D image segmentation of paediatric high-grade gliomas to generate precise, patient-specific anatomical maps that could potentially support preoperative neurosurgical planning and intraoperative image-guided navigation.

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
