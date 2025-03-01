# Caries Detection Dataset（CDD）
Our paper "Dual-Attention YOLOv5: A Deep Learning Framework for High-Precision Detection of Pediatric Dental Caries in Clinical Imagery" is under review, and we decide to public our dataset in advance. 

I. Introduction
The caries detection dataset is a dataset of about 2000 images, all of which were taken by smartphones or other electronic devices with camera functions. The images were taken from different angles, such as those taken with professional oral instruments and at standard angles, or those taken in an environment without professional oral instruments.We use horizontal bounding boxes (xmin,ymin,xmax,ymax) to annotate caries and non-caries.The annotations follows the VOC format with .xml files.
We split the dataset into training set, validation set, and test set according to the ratio of 8:1:1. The detailed statistics of the dataset division are listed in Table 1.

<div align="center">

<strong>Table 1</strong> <br>

| type          | Train | Validation | Test | Total |
|---------------|-------|------------|------|-------|
| Image Number  | 1600  | 200        | 200  | 2000  |

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

II. Annotations
We use horizontal bounding boxes (xmin,ymin,xmax,ymax) to annotate caries and non-caries.The annotations follows the VOC format with .xml files.

III. How to obtain
A subset of the CDD dataset is provided in this repository for demonstration purposes only. The full clinical caries dataset cannot be publicly released due to patient privacy protections under China's Personal Information Protection Law (PIPL) and ethical restrictions involving human subject data. Researchers requiring access to the complete dataset must obtain approval through the following steps:

Submit a formal data request to the corresponding authors (contact: houchao@sspu.edu.cn)
Receive ethics clearance from both the research team
Obtain institutional approval from Shanghai Stomatological Hospital
The full dataset will only be shared after completing all required compliance procedures.
You can get code at [Google Drive](https://drive.google.com/file/d/1CMCOMMSko2sGqVuSjXLByrTU_I7A9U3C/view?usp=sharing) or [Baidu Netdisk](https://pan.baidu.com/s/11LEZOqYPa6999wibRz38rA) with access code `sspu`.
