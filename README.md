# Denoising of Old Album and Mural Photographs using GAN Techniques
This is a research project where we used a comparative approach, combining two popular deep learning models (GANs) used for image denoising. We have included our research paper and code files with the dataset.

## Overview
Image denoising is the task of recovering a clean image from a noisy one. This project compares two GAN-based approaches, **Pix2Pix GAN** and **GFP GAN**, and evaluates them on the same dataset under the same conditions.

## Repository Structure
```
.
├── README.md          # Project documentation
├── Final draft.docx   # Research paper
├── train.py           # Training script
└── <dataset-folder>/  # Dataset
```

## Requirements
`--epochs 500 
 --batch_size 16`

## Dataset


## Results
| Model       | PSNR      | SSIM     |
|------------ |---------- |----------|
| Pix2Pix GAN | 31.295    | 0.571    |
| GFP GAN     | 33.580    | 0.057    |

## Authors
- Pranav K R
- Arjun A
- Aswin Krishnan
- Muhammed Ilham Moosa
