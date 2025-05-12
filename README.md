# Caries Detection Dataset（CDD）
Our paper <strong>"Evaluation of dental caries using a deeplearning-based artificial intelligence algorithm" </strong>is under review, and we decide to public our dataset in advance. 

<h3 style="font-weight: bold; font-size: 1.2em; color: #000;">I. Introduction</h3>
The caries detection dataset was constructed by collecting approximately 5,000 images from community health centers and hospital settings, captured using smartphones and various camera-equipped electronic devices. After rigorous quality screening and curation, we selected 1,241 qualified images for annotation. These images exhibit diverse capture conditions, including both professionally assisted shots using oral instruments and non-professional captures taken at standard angles without specialized equipment. All annotations follow the PASCAL VOC format with XML files, using horizontal bounding boxes (xmin, ymin, xmax, ymax) to label both caries and non-caries regions.

The dataset was partitioned into training, validation, and test sets following an 8:1:1 ratio allocation:

Training set: 993 images (80%)

Validation set: 124 images (10%)

Test set: 124 images (10%)

This stratified split ensures consistent distribution of different capture conditions and annotation categories across all subsets while maintaining complete separation between the sets.

<div align="center">

<strong>Table 1</strong> <br>

| type          | Train | Validation | Test | Total |
|---------------|-------|------------|------|-------|
| Image Number  | 993  | 124        | 124  | 1241  |

</div>

<div align="center">
  <img src="Caries 1.png" alt="Caries Example" width="60%">
  <br>
  <strong>Caries 1</strong>
</div>
Caries 1 shows the standard effect of a doctor's caries tagging, in which a professional oral instrument is used to assist in photographing.

<div align="center">
  <img src="Caries 2.png" alt="Caries Example" width="60%">
  <br>
  <strong>Caries 2</strong>
</div>

Caries 2 shows the effect of some environmental noise in the picture taken by the doctor without a professional oral lock. This kind of picture can fully reflect the diversity of the picture and help improve the ability of the model to be photographed, uploaded and recognized by the mobile phone.

<div align="center">
  <img src="Caries 3.png" alt="Caries Example" width="60%">
  <br>
  <strong>Caries 3</strong>
</div>
Caries. 3 Compared with Caries. 1, it is shown that different dental hospitals may use different instruments and angles to collect standard dental caries images by themselves, and all such maps are trained with models to improve the generalization ability of the models for caries detection.

<h3 style="font-weight: bold; font-size: 1.2em; color: #000;">II. Annotations</h3>
We use horizontal bounding boxes (xmin,ymin,xmax,ymax) to annotate caries and non-caries.The annotations follows the VOC format with .xml files.

<h3 style="font-weight: bold; font-size: 1.2em; color: #000;">III. How to obtain</h3>
A subset of the CDD dataset is provided in this repository for demonstration purposes only. The full clinical caries dataset cannot be publicly released due to patient privacy protections under China's Personal Information Protection Law (PIPL) and ethical restrictions involving human subject data. Researchers requiring access to the complete dataset must obtain approval through the following steps:

Submit a formal data request to the corresponding authors (contact: houchao@sspu.edu.cn)
Receive ethics clearance from both the research team
Obtain institutional approval from Shanghai Stomatological Hospital
The full dataset will only be shared after completing all required compliance procedures.

You can get code at [Google Drive](https://drive.google.com/file/d/1CMCOMMSko2sGqVuSjXLByrTU_I7A9U3C/view?usp=sharing) or [Baidu Netdisk](https://pan.baidu.com/s/11LEZOqYPa6999wibRz38rA) with access code `sspu`.
