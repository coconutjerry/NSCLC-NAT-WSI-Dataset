# NSCLC-NAT-WSI-Dataset
## Dataset Summary

The **NSCLC NAT WSI Dataset** is a curated collection of 2,544 digital pathology images derived from non-small cell lung cancer (NSCLC) patients who received neoadjuvant therapy (NAT) prior to surgery. The dataset includes both original images and augmented variants generated via standard data augmentation techniques such as flipping and mirroring. All samples were obtained from intraoperative frozen sections and scanned into whole slide images (WSIs), then resized for processing. This dataset is designed for research in computational pathology, particularly in the context of NSCLC following neoadjuvant treatment.
[![image]https://github.com/coconutjerry/NSCLC-NAT-WSI-Dataset/blob/main/image-Dataset.png](https://github.com/coconutjerry/NSCLC-NAT-WSI-Dataset/blob/main/image-Dataset.png)    

## Download

**Access Upon Request:** If you wish to use this dataset for academic research or other non-commercial purposes, please contact liujierui358@gmail.com to submit a request. Access will be granted upon review and approval.

## Dataset Structure

The dataset is organized into three main folders:

- **Images/**:
  Contains resized digital images of the original WSIs. These are the source images used for annotation and model input.
- **Mask/**:
  Contains expert-annotated masks highlighting the tumor bed regions.
- **SegmentationClass/**:
  Contains single-channel grayscale images suitable for use in semantic segmentation networks. Each pixel is labeled as either:
  - **0**: Background
  - **1**: Annotated tumor bed region

## Data Collection

- **Source**: Department of Pathology, a top-tier (Class III) hospital in China.
- **Collection Period**: Over the past five years.
- **Patient Cohort**: NSCLC patients who underwent neoadjuvant therapy before surgery.
- **Ethical Compliance**: All images are fully anonymized and contain no patient-identifiable information. The data collection process adhered to medical ethical standards and did not cause any harm to patients.

## Key Characteristics

- **Number of Images**: 2,544
- **Tumor Type**: Predominantly adenocarcinoma
- **Therapies Included**: Chemotherapy, radiotherapy, targeted therapy, immunotherapy
- **Annotation Team**: Medical students under professional supervision
- **Image Augmentations**: Flipping, mirroring

## Intended Use

This dataset is intended for academic and research purposes only, particularly in areas such as:

- Training and evaluation of deep learning models for medical image segmentation
- Studying histopathological changes in NSCLC after neoadjuvant therapy
- Developing automated tools for tumor bed detection and characterization

## Citation

If you use this dataset in your research, please cite it as:

> [Liu Jierui]. "NSCLC NAT WSI Dataset" [2025]. Available at: [Dataset link].
