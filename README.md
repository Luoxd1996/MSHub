# MSHub
MSHub is a comprehensive repository of state-of-the-art medical image segmentation models based on the [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) framework. Designed for researchers, developers, and healthcare professionals, MSHub aims to streamline the development and deployment of medical segmentation applications by providing a centralized hub for diverse and high-quality segmentation models. We have collected more than 13k 3D CT scans with manual annotation to model development to achieve this goal (most of them are private and first released for public use). Due to privacy protection, we trained and released ten nnUNet models for tumor and organ segmentation (not widely-studied tasks) to ease the annotation and model development cost for the MICCAI community. The main segmentation tasks are as follows:

| **Site (Public)**        | **Modality** | **Target**       | **Total Number (3D Scans)** | **Performance (DSC)** | **Pre-trained model link** | **Reference** | 
|-----------------|--------------|------------------|-------------------------------|-----------------------|-------------------------------|-----------------------|
|  Head and Neck (✖️)  | CT           | 43 Organs        | >3400                       | 0.83                  |coming soon | coming soon|
|  Head and Neck* (✖️)  | CT           | Pan-Tumor and Lymph  | >6800                        |     0.72       | coming soon|coming soon|
|  Head and Neck (✖️)  | MRI           | Pan-Tumor and Lymph  | >2000                        |     coming soon       | coming soon|coming soon|
|  Head and Neck (✖️)  | MR           | Nasopharyngeal Carcinoma Tumor  | >1000                        |     0.89       | [nnunetv1](https://drive.google.com/file/d/1gweae9uHaCRno1zKw_fhksYr_VDUaWg2/view?usp=drive_link)&[example](https://github.com/Luoxd1996/RobustNPC)|[GreenJournal](https://www.sciencedirect.com/science/article/pii/S016781402300018X)&[RedJournal](https://www.sciencedirect.com/science/article/pii/S0360301624036447)|
|  [Lung](https://www.cancerimagingarchive.net/collection/lidc-idri/) (✔️)  | CT           | Tumor | 1018                       |     coming soon       | coming soon|coming soon|
|  Esophageal (✖️)  | CT           | Tumor and Lymph  | > 400                        |     coming soon       | coming soon|coming soon|
|  Liver (✖️)  | CT           | Lesion  | >1300                        |     coming soon       | coming soon|coming soon|
|  Kidney (✖️)  | CT           | Lesion  | >200                        |     coming soon       | coming soon|coming soon|
|  Breast (✖️)  | CT           | Clinical Target Volume  | >2300                        |     coming soon       | coming soon|coming soon|
|  Stomach (✖️)  | CT           | Gastric Cancer   | > 500                       |     coming soon       | coming soon|coming soon|
|  Cervical (✖️)  | CT           | Tumor and Lymph   | > 400                       |     coming soon       | coming soon|coming soon|

\* means this dataset includes the public dataset [RADCURE](https://www.cancerimagingarchive.net/collection/radcure), where we re-delineated this dataset with all visible lymph nodes manually.
