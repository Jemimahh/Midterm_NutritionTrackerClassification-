# Food Classification

**Course:** ITAI 1378 — Computer Vision  
**Team Member:** Jemima  
**Project Tier:** Tier 1  

---

## Problem Statement

Manually logging food for calorie and nutrition tracking is tedious and error-prone. Most people give up or mis-estimate portions because looking up each item takes real effort.



## Solution Overview

A single-image food classifier that identifies the food item in a photo and returns the food name plus estimated nutritional information (calories, protein, carbs, fat). Built using transfer learning on EfficientNet-B0, fine-tuned on the Food Image Classification Dataset from Kaggle.




## Dataset

- **Source:** [Food Image Classification Dataset — Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/food-image-classification-dataset)
- **Size:** ~20,000 images across 20 food categories
- **Labels:** Folder-per-class structure (e.g. `/pizza/`, `/sushi/`)
- **Split:** 80% train / 20% validation
- **Augmentation:** Random horizontal flip, ±15° rotation, color jitter (train split only)

See [`data/README.md`](data/README.md) for full dataset setup instructions.





