# Remote-Sensing-Classification-Multimodal-Dataset

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of multimodal datasets for remote sensing object classification.

## Table of Contents

- [Optical-DSM Datasets](#optical-dsm-datasets)
- [Optical-SAR Datasets](#optical-sar-datasets)
- [Optical-LiDAR Datasets](#optical-lidar-datasets)
- [Hyperspectral-MS Datasets](#hyperspectral-ms-datasets)

---

## Optical-DSM Datasets

> Datasets fusing optical remote sensing imagery with Digital Surface Models (DSM)

### [Potsdam Dataset](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx)

| Attribute | Value |
|-----------|-------|
| **Organization** | ISPRS |
| **Quantity** | 38 images |
| **Size** | 6000×6000 pixels |
| **Resolution** | 5 cm |
| **Modalities** | RGB, DSM, IRRG, RGBIR, Normalized DSM |

**Description:** High-resolution aerial imagery of Potsdam, Germany, including DSM data generated from dense image matching.

---

### [Vaihingen Dataset](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx)

| Attribute | Value |
|-----------|-------|
| **Organization** | ISPRS |
| **Quantity** | 33 images |
| **Size** | 2046×2046 pixels |
| **Resolution** | 9 cm |
| **Modalities** | DSM, IRRG |

**Description:** Aerial imagery of Vaihingen, Germany, used for 2D semantic labeling benchmarks.

---

### [N3C-California](https://github.com/IKDNet-pytorch)

| Attribute | Value |
|-----------|-------|
| **Type** | Optical-Point Cloud |
| **Quantity** | 10,800 images |
| **Size** | 512×512 pixels |
| **Resolution** | 1 meter |
| **Modalities** | RGB, Point Cloud, DSM |

**Description:** Large-scale optical and point cloud paired dataset for California region.

---

### [DKDFN Dataset](https://github.com/HunanMultimodalDataset)

| Attribute | Value |
|-----------|-------|
| **Type** | Multimodal Fusion |
| **Quantity** | 450 images |
| **Size** | 256×256 pixels |
| **Resolution** | 10 meters |
| **Modalities** | MS, SAR, DEM |

**Description:** Hunan multimodal dataset containing multispectral, SAR, and elevation data.

---

## Optical-SAR Datasets

> Datasets fusing optical remote sensing imagery with Synthetic Aperture Radar (SAR) data

### [WHU-OPT-SAR](https://github.com/WHU-OPT-SAR-dataset)

| Attribute | Value |
|-----------|-------|
| **Organization** | Wuhan University |
| **Quantity** | 1,005 images |
| **Size** | 3704×3704 pixels |
| **Resolution** | 5 meters |
| **Modalities** | RGBIR, SAR |

**Description:** Optical and SAR paired dataset released by Wuhan University.

---

### [DDHRNet Dataset](https://github.com/XD-MG/DDHRNet)

| Attribute | Value |
|-----------|-------|
| **Type** | Dual-stream Network Training Data |
| **Region** | Xi'an, Dongying, Pohang |
| **Resolution** | 1 meter |
| **Modalities** | Optical, SAR |
| **Source** | GF2 (Optical), GF3 (SAR) satellite data |

**Description:** Multi-region optical and SAR registration dataset.

---

### [MSAW Dataset](https://spacenet.ai)

| Attribute | Value |
|-----------|-------|
| **Platform** | SpaceNet |
| **Size** | 900×900 pixels |
| **Resolution** | 0.5 meters |
| **Modalities** | RGBIR, SAR |

**Description:** SpaceNet multimodal building detection dataset.

---

### [SEN12MS Dataset](https://mediatum.ub.tum.de)

| Attribute | Value |
|-----------|-------|
| **Coverage** | Most regions globally |
| **Quantity** | 180,748 images |
| **Size** | 256×256 pixels |
| **Resolution** | MS: 10m, SAR: 20m |
| **Modalities** | MS, SAR |
| **Features** | Covers all four seasons, large-scale deep learning training data |

---

## Optical-LiDAR Datasets

> Datasets fusing hyperspectral/optical remote sensing imagery with Light Detection and Ranging (LiDAR) data

### [MUUFL Gulfport](https://github.com/GatorSense/MUUFLGulfport)

| Attribute | Value |
|-----------|-------|
| **Type** | Hyperspectral + LiDAR |
| **Size** | 325×220 pixels |
| **Modalities** | Hyperspectral (HS), LiDAR |

**Description:** Hyperspectral and LiDAR paired data for Gulf Coast region, Florida.

---

### [Trento Dataset](https://github.com/Trento-dataset)

| Attribute | Value |
|-----------|-------|
| **Region** | Rural area of Trento, Italy |
| **Size** | 600×166 pixels |
| **Resolution** | 1 meter |
| **Modalities** | HSI, LiDAR |
| **Classes** | Apple trees, Buildings, Ground, Wood, Vineyard, Roads (6 classes) |

**Description:** Rural land cover classification benchmark dataset.

---

### [Houston2013](https://github.com/danfenghong/ISPRS_S2FL)

| Attribute | Value |
|-----------|-------|
| **Type** | Hyperspectral + LiDAR |
| **Size** | 1905×349 pixels |
| **Modalities** | HS, LiDAR |

**Description:** IEEE GRSS Data Fusion Contest 2013 dataset.

---

## Hyperspectral-MS Datasets

> Datasets combining hyperspectral and multispectral imagery

*(To be added - contributions welcome!)*

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This repository is licensed under [MIT License](LICENSE).

---

**Note:** Some dataset links may require registration or academic access. Please refer to the original sources for usage terms and citation requirements.
