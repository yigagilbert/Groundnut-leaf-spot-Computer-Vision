# Groundnut Leaf Spot Dataset EDA Report

## Dataset Summary
- Total images: 273
- Class distribution:
  - Leafspot Scale 1: 37 images (13.55%)
  - Leafspot Scale 2: 40 images (14.65%)
  - Leafspot Scale 3: 48 images (17.58%)
  - Leafspot Scale 4: 27 images (9.89%)
  - Leafspot Scale 5: 56 images (20.51%)
  - Leafspot Scale 6: 65 images (23.81%)

## Image Properties
- Unique dimensions: 4
- Average file size: 6676.75 KB
- File formats:
  - .jpg: 273

## Image Quality
- Average brightness: 116.49
- Average contrast: 52.86
- Average blur score: 210.99

## Issues Detected
- duplicates: 0
- corrupted: 0
- very_low_brightness: 0
- very_high_brightness: 0
- very_blurry: 66
- unusual_aspect_ratio: 0
- outlier_size: 177

## Cleaning Recommendations
1. Consider removing or enhancing 66 blurry images.
2. Address class imbalance through augmentation of minority classes or sampling strategies.

## Visualizations
The following visualizations were generated during EDA:

- [class distribution](class_distribution.png)
- [image dimensions](image_dimensions.png)
- [aspect ratios](aspect_ratios.png)
- [file sizes](file_sizes.png)
- [file formats](file_formats.png)
- [brightness distribution](brightness_distribution.png)
- [contrast distribution](contrast_distribution.png)
- [blur distribution](blur_distribution.png)
- [brightness by class](brightness_by_class.png)
- [contrast by class](contrast_by_class.png)
- [rgb distribution](rgb_distribution.png)
- [rgb by class 3d](rgb_by_class_3d.png)
- [sample images](sample_images.png)
- [texture contrast](texture_contrast.png)
- [texture dissimilarity](texture_dissimilarity.png)
- [texture homogeneity](texture_homogeneity.png)
- [texture energy](texture_energy.png)
- [texture correlation](texture_correlation.png)
- [texture pca](texture_pca.png)
- [spot count by class](spot_count_by_class.png)
- [spot area by class](spot_area_by_class.png)
