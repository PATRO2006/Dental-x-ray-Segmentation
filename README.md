# Automated Dental Caries Segmentation (Hack4Health – Image Track)

## Overview
This project focuses on automated segmentation of dental structures and carious lesions from dental X-ray images using deep learning–based semantic segmentation. The system aims to assist dentists by providing accurate, reliable, and early detection of dental caries.

## Problem Statement
Manual identification of carious regions in dental X-rays is time-consuming and prone to inter-observer variability. This project proposes an automated approach to precisely segment carious regions, even in challenging conditions such as low contrast, noise, and overlapping anatomical structures.

## Dataset
- Total images: 1,132 dental X-ray images  
- Caries images: 566  
- Non-caries images: 566  
- Each image has a corresponding binary segmentation mask

## Methodology
1. Data preprocessing and normalization  
2. Train-test split of images and masks  
3. Deep learning–based semantic segmentation model  
4. Model training with Dice loss / IoU-based evaluation  
5. Performance evaluation using standard metrics  

## Evaluation Metrics
- Dice Similarity Coefficient  
- Intersection over Union (IoU)  
- Precision  
- Recall  
- F1-score  
- Sensitivity and Specificity  

## Results
The model demonstrates strong segmentation performance with steadily improving IoU and Dice scores across epochs. Validation results closely follow training trends, indicating good generalization and minimal overfitting.

## Deliverables
- Original dental X-ray images  
- Ground truth masks  
- Predicted segmentation outputs  
- Overlay and side-by-side visualizations  
- Epoch-wise IoU and Dice coefficient charts  

## Conclusion
The proposed system successfully automates dental caries segmentation, reducing manual effort and supporting early and reliable clinical diagnosis. This solution has strong potential for real-world healthcare applications.

## Team
Hack4Health – Image Track
