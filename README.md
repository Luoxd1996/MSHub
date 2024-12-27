# MSHub
MSHub is a comprehensive repository of state-of-the-art medical image segmentation models based on the [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) framework. Designed for researchers, developers, and healthcare professionals, MSHub aims to streamline the development and deployment of medical segmentation applications by providing a centralized hub for diverse and high-quality segmentation models. We have collected more than 13k 3D CT scans with manual annotation to model development to achieve this goal (most of them are private and first released for public use). Due to privacy protection, we trained and released ten nnUNet models for tumor and organ segmentation (not widely-studied tasks) to ease the annotation and model development cost for the MICCAI community. The main segmentation tasks are as follows:

| **Site (Public)**        | **Modality** | **Target**       | **Total Number (3D Scans)** | **Performance (DSC)** | **Pre-trained model link** | **Reference** | 
|-----------------|--------------|------------------|-------------------------------|-----------------------|-------------------------------|-----------------------|
|  Head and Neck (✖️)  | CT           | 43 Organs        | >3400                       | 0.83                  |coming soon | coming soon|
|  Head and Neck* (✖️)  | CT           | Pan-Tumor and Lymph  | >6800                        |     0.70       | [nnunetv2](https://drive.google.com/drive/folders/11L-TP2rve55v2BM59wJGR6s81H11FLuL?usp=sharing)|coming soon|
|  Head and Neck (✖️)  | MRI           | Pan-Tumor and Lymph  | >2000                        |     coming soon       | coming soon|coming soon|
|  Head and Neck (✖️)  | MR           | Nasopharyngeal Carcinoma Tumor  | >1000                        |     0.89       | [nnunetv1](https://drive.google.com/file/d/1gweae9uHaCRno1zKw_fhksYr_VDUaWg2/view?usp=drive_link)&[example](https://github.com/Luoxd1996/RobustNPC)|[GreenJournal](https://www.sciencedirect.com/science/article/pii/S016781402300018X)&[RedJournal](https://www.sciencedirect.com/science/article/pii/S0360301624036447)|
|  [Lung](https://www.cancerimagingarchive.net/collection/lidc-idri/) (✔️)  | CT           | Tumor | 1018                       |     0.43       | [nnunetv2](https://drive.google.com/drive/folders/1kTWSqD14M94HK6gf5N_t9wk0OydFz0Nf?usp=sharing)|[TCIA](https://www.cancerimagingarchive.net/collection/lidc-idri/)|
|  Esophageal (✖️)  | CT           | Tumor and Lymph  | > 400                        |     0.6       | [nnunetv2](https://drive.google.com/drive/folders/1f3i1sYpjMoqNLOTa4VXXGCWlKN8pP59n?usp=sharing)|coming soon|
|  Liver** (✖️)  | CT           | Lesion  | >1300                        |     0.8       | [nnunetv2](https://drive.google.com/drive/folders/15-vf6HHN37keZTDIr4KSoYd4tkvVpOqM?usp=sharing)|coming soon|
|  Kidney (✖️)  | CT           | Lesion  | >200                        |     0.81       | [nnunetv2](https://drive.google.com/drive/folders/1mgiZr5TTGB2ezrfObQl4qQJa1IgWr79w?usp=sharing)|coming soon|
|  Breast (✖️)  | CT           | Clinical Target Volume  | >2300                        |     0.75       | [nnunetv2](https://drive.google.com/drive/folders/1t5Afz5iLcanRVRUVqCy-hPIdJcMlSlXY?usp=drive_link)|coming soon|
|  Stomach (✖️)  | CT           | Gastric Cancer   | > 500                       |     0.58       | [nnunetv2](https://drive.google.com/drive/folders/1mrrCjC6BZ5bjnNCqd73mUk4ekRZnaTxE?usp=sharing)|coming soon|
|  Cervical (✖️)  | CT           | Tumor and Lymph   | > 400                       |     0.61       | [nnunetv2](https://drive.google.com/drive/folders/1t9go2EpuvWM4DZEfDG8d8n579w7yiPT2?usp=sharing)|coming soon|

\* means this dataset includes the public dataset [RADCURE](https://www.cancerimagingarchive.net/collection/radcure), where we re-delineated this dataset with all visible lymph nodes manually.

\** The intensity of the input CT volumes was truncated between -125 and 275 Hounsfield units.

## Acknowledgment and Statement
* We are optimising this project and improving these models' performance with scaling annotation data for public research, no second development and commercial use.
* Welcome to contribute your pre-trained model to this project, feel free to push your project link and reference papers.
* If you want to provide some computation source or data to enhance this project, please reach out to [Xiangde](https://luoxd1996.github.io) anytime.
* This project will be maintained by Xiangde Luo (Stanford), Zihao Luo (UESTC), He Li (UESTC), and Wenjun Liao (SCH). More details about this project will be posted later.
