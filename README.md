# Remote-Sensing-Classification-Multimodal-Dataset

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](#english-version) | [中文](#中文版本)

---

## English Version

Awesome Multimodal Remote Sensing Datasets for Object Classification & Fusion

A curated list of high-quality multimodal remote sensing datasets for object classification, semantic segmentation, and multimodal fusion research. This list is designed to help researchers and developers quickly find suitable datasets for their projects.

### Table of Contents

- [Optical + DSM Datasets](#optical--dsm-datasets)
- [Optical + SAR Datasets](#optical--sar-datasets)
- [Optical / Hyperspectral + LiDAR Datasets](#optical--hyperspectral--lidar-datasets)
- [Hyperspectral + MS Datasets](#hyperspectral--ms-datasets)
- [Notes](#notes)
- [Contributing](#contributing)
- [License](#license)

---

### Optical + DSM Datasets

Datasets fusing optical remote sensing imagery with Digital Surface Models (DSM) for object classification and scene understanding.

#### [Potsdam Dataset](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx)

| Attribute | Value |
|-----------|-------|
| **Provider** | ISPRS (International Society for Photogrammetry and Remote Sensing) |
| **Image Count** | 38 images |
| **Image Size** | 6000×6000 pixels |
| **Resolution** | 5 cm |
| **Modalities** | RGB, DSM, IRRG, RGBIR, Normalized DSM |

**Description:** High-resolution aerial imagery of Potsdam, Germany, accompanied by DSM data generated through dense image matching. Suitable for high-precision urban object classification and semantic segmentation tasks.

---

#### [Vaihingen Dataset](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx)

| Attribute | Value |
|-----------|-------|
| **Provider** | ISPRS |
| **Image Count** | 33 images |
| **Image Size** | 2046×2046 pixels |
| **Resolution** | 9 cm |
| **Modalities** | DSM, IRRG |

**Description:** Aerial imagery of Vaihingen, Germany, widely used as a benchmark dataset for 2D semantic labeling and remote sensing object classification research.

---

#### [N3C-California](https://github.com/IKDNet-pytorch)

| Attribute | Value |
|-----------|-------|
| **Type** | Optical + Point Cloud |
| **Image Count** | 10,800 images |
| **Image Size** | 512×512 pixels |
| **Resolution** | 1 meter |
| **Modalities** | RGB, Point Cloud, DSM |

**Description:** Large-scale paired dataset of optical imagery and point clouds covering the California region, suitable for large-scale object classification and 3D scene reconstruction tasks.

---

#### [DKDFN Dataset](https://github.com/HunanMultimodalDataset)

| Attribute | Value |
|-----------|-------|
| **Type** | Multimodal Fusion |
| **Image Count** | 450 images |
| **Image Size** | 256×256 pixels |
| **Resolution** | 10 meters |
| **Modalities** | MS (Multispectral), SAR (Synthetic Aperture Radar), DEM (Digital Elevation Model) |

**Description:** Multimodal dataset from Hunan, China, integrating multispectral, SAR, and elevation data, suitable for multi-source remote sensing data fusion and object classification research.

---

### Optical + SAR Datasets

Datasets combining optical remote sensing imagery with Synthetic Aperture Radar (SAR) data, enabling research under complex weather and lighting conditions.

#### [WHU-OPT-SAR](https://github.com/AmberHen/WHU-OPT-SAR-dataset)

| Attribute | Value |
|-----------|-------|
| **Provider** | Wuhan University |
| **Image Count** | 100 pairs |
| **Image Size** | ~5556×3704 pixels |
| **Resolution** | 5 meters |
| **Modalities** | RGBIR, SAR |
| **Source** | GF-1 (Optical), GF-3 (SAR) |

**Description:** Paired optical and SAR dataset covering Hubei Province, China. Categories include farmland, urban, village, water, forest, road, and others.

---

#### [DDHRNet Dataset](https://github.com/XD-MG/DDHRNet)

| Attribute | Value |
|-----------|-------|
| **Type** | Dual-stream Network Training Data |
| **Coverage Regions** | Xi'an (China), Dongying (China), Pohang (South Korea) |
| **Resolution** | 1 meter |
| **Modalities** | Optical, SAR |
| **Data Source** | GF-2 (Optical Satellite), GF-3 (SAR Satellite) |

**Description:** Co-registered optical and SAR dataset covering multiple regions, designed for training dual-stream deep learning models (DDHRNet). Categories include buildings, roads, farmland, water, and vegetation.

---

#### [MSAW Dataset](https://spacenet.ai)

| Attribute | Value |
|-----------|-------|
| **Platform** | SpaceNet |
| **Image Size** | 900×900 pixels |
| **Resolution** | 0.5 meters |
| **Modalities** | RGBIR, SAR |

**Description:** Multimodal dataset focused on building detection, provided by SpaceNet, suitable for object detection and semantic segmentation tasks in urban areas.

---

#### [SEN12MS Dataset](https://dataserv.ub.tum.de/s/m1474000)

| Attribute | Value |
|-----------|-------|
| **Coverage** | Most global land areas |
| **Image Count** | 180,662 patch triplets |
| **Image Size** | 256×256 pixels |
| **Resolution** | MS: 10 meters, SAR: 20 meters |
| **Modalities** | MS (Multispectral), SAR |
| **Features** | Covers seasonal imagery across different regions, large-scale dataset suitable for deep learning model training |

**Description:** Large-scale dataset containing corresponding Sentinel-1 dual-pol SAR data, Sentinel-2 multi-spectral images, and MODIS-derived land cover maps. All patches are fully georeferenced and distributed across all inhabited continents during all meteorological seasons [^18^].

---

### Optical / Hyperspectral + LiDAR Datasets

Datasets integrating optical/hyperspectral imagery with LiDAR (Light Detection and Ranging) data, enabling high-precision object classification and 3D feature extraction.

#### [MUUFL Gulfport](https://github.com/GatorSense/MUUFLGulfport)

| Attribute | Value |
|-----------|-------|
| **Type** | Hyperspectral + LiDAR |
| **Image Size** | 325×220 pixels |
| **Modalities** | HS (Hyperspectral), LiDAR |
| **Coverage Region** | Gulfport, Florida, USA |

**Description:** Paired hyperspectral and LiDAR airborne dataset, including campus subimages (at 3500ft and 6700ft elevation) with coregistered LiDAR DEMs, target ground truth information, and detection/scoring code. The dataset also includes geo-tagged photographs, scene labels, and technical reports. DOI: [10.5281/zenodo.1186326](https://doi.org/10.5281/zenodo.1186326) (MIT License).

**Citation Note:** Please cite the relevant technical reports when using this dataset (see repository for detailed citation information).

---

#### [Trento Dataset](https://github.com/tyust-dayu/Trento)

| Attribute | Value |
|-----------|-------|
| **Coverage Region** | Rural area of Trento, Italy |
| **Image Size** | 600×166 pixels |
| **Resolution** | 1 meter |
| **Modalities** | HSI (Hyperspectral Imaging), LiDAR |
| **Object Classes** | 6 classes (Apple trees, Buildings, Ground, Wood, Vineyards, Roads) |

**Description:** Benchmark dataset for rural land cover and object classification, suitable for evaluating hyperspectral-LiDAR fusion algorithms.

---

#### [Houston2013](https://machinelearning.ee.uh.edu/?page_id=459)

| Attribute | Value |
|-----------|-------|
| **Type** | Hyperspectral + LiDAR |
| **Image Size** | 1905×349 pixels |
| **Resolution** | 2.5 meters |
| **Modalities** | HS (144 bands, 380-1050nm), LiDAR DSM |

**Description:** Dataset from the [IEEE GRSS 2013 Data Fusion Contest](https://machinelearning.ee.uh.edu/2013-ieee-grss-data-fusion-contest/), widely used as a benchmark for hyperspectral and LiDAR data fusion and object classification research. Data can be requested via the official website subject to terms and conditions [^12^].

---

### Hyperspectral + MS Datasets

Multimodal datasets integrating hyperspectral and multispectral imagery, suitable for spectral feature analysis and object classification tasks.

*(To be updated with more datasets - contributions welcome!)*

---

### Notes

- Some dataset URLs may require access permissions or registration; please refer to the official links for detailed download instructions.

- For dataset usage, please comply with the corresponding license agreements and cite the relevant papers/technical reports as required.

- **SEN12MS Download:** The dataset can be downloaded via `wget` or `rsync` using the following credentials:
  - Username: `m1474000`
  - Password: `m1474000`
  - Server: `dataserv.ub.tum.de` [^18^]

---

### Contributing

Contributions to expand this list are welcome! Please submit a pull request with the following information for each new dataset:

- Dataset name and official URL (valid and complete)
- Key metadata (provider, image count, size, resolution, modalities)
- Brief description and applicable research tasks
- Citation information (if available)

---

### License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 中文版本

用于目标分类与融合的优质多模态遥感数据集集合

本文档整理了高质量的多模态遥感数据集，适用于目标分类、语义分割及多模态融合研究。旨在帮助研究人员和开发者快速找到适合自身项目的数据集。

### 目录

- [光学+DSM数据集](#光学dsm数据集-1)
- [光学+SAR数据集](#光学sar数据集-1)
- [光学/高光谱+LiDAR数据集](#光学高光谱lidar数据集-1)
- [高光谱+多光谱数据集](#高光谱多光谱数据集-1)
- [注意事项](#注意事项)
- [贡献指南](#贡献指南)
- [许可证](#许可证)

---

### 光学+DSM数据集

融合光学遥感影像与数字表面模型（DSM）的数据集，适用于目标分类和场景理解任务。

#### [波茨坦数据集（Potsdam Dataset）](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx)

| 属性 | 数值 |
|------|------|
| **提供方** | ISPRS（国际摄影测量与遥感学会） |
| **影像数量** | 38幅 |
| **影像尺寸** | 6000×6000像素 |
| **分辨率** | 5厘米 |
| **模态** | RGB、DSM、IRRG、RGBIR、归一化DSM |

**描述：** 德国波茨坦地区高分辨率航空影像，配套通过密集影像匹配生成的DSM数据。适用于高精度城市目标分类和语义分割任务。

---

#### [魏因海姆数据集（Vaihingen Dataset）](https://www.isprs.org/education/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx)

| 属性 | 数值 |
|------|------|
| **提供方** | ISPRS |
| **影像数量** | 33幅 |
| **影像尺寸** | 2046×2046像素 |
| **分辨率** | 9厘米 |
| **模态** | DSM、IRRG |

**描述：** 德国魏因海姆地区航空影像，广泛用作二维语义标注和遥感目标分类研究的基准数据集。

---

#### [N3C-加利福尼亚数据集（N3C-California）](https://github.com/IKDNet-pytorch)

| 属性 | 数值 |
|------|------|
| **类型** | 光学+点云 |
| **影像数量** | 10,800幅 |
| **影像尺寸** | 512×512像素 |
| **分辨率** | 1米 |
| **模态** | RGB、点云、DSM |

**描述：** 覆盖加利福尼亚地区的大规模光学影像与点云配对数据集，适用于大规模目标分类和三维场景重建任务。

---

#### [DKDFN数据集](https://github.com/HunanMultimodalDataset)

| 属性 | 数值 |
|------|------|
| **类型** | 多模态融合 |
| **影像数量** | 450幅 |
| **影像尺寸** | 256×256像素 |
| **分辨率** | 10米 |
| **模态** | 多光谱（MS）、合成孔径雷达（SAR）、数字高程模型（DEM） |

**描述：** 中国湖南地区多模态数据集，集成多光谱、SAR和高程数据，适用于多源遥感数据融合和目标分类研究。

---

### 光学+SAR数据集

融合光学遥感影像与合成孔径雷达（SAR）数据的数据集，可支持复杂天气和光照条件下的研究。

#### [WHU-OPT-SAR数据集](https://github.com/AmberHen/WHU-OPT-SAR-dataset)

| 属性 | 数值 |
|------|------|
| **提供方** | 武汉大学 |
| **影像数量** | 100对 |
| **影像尺寸** | ~5556×3704像素 |
| **分辨率** | 5米 |
| **模态** | RGBIR、SAR |
| **来源** | 高分一号（光学）、高分三号（SAR） |

**描述：** 覆盖中国湖北省的光学与SAR配对数据集。类别包括农田、城市、村庄、水域、森林、道路和其他。

---

#### [DDHRNet数据集](https://github.com/XD-MG/DDHRNet)

| 属性 | 数值 |
|------|------|
| **类型** | 双流网络训练数据 |
| **覆盖区域** | 中国西安、中国东营、韩国浦项 |
| **分辨率** | 1米 |
| **模态** | 光学、SAR |
| **数据来源** | 高分二号（光学卫星）、高分三号（SAR卫星） |

**描述：** 覆盖多个区域的配准光学与SAR数据集，专为双流深度学习模型（DDHRNet）训练设计。类别包括建筑物、道路、农田、水域和植被。

---

#### [MSAW数据集](https://spacenet.ai)

| 属性 | 数值 |
|------|------|
| **平台** | SpaceNet |
| **影像尺寸** | 900×900像素 |
| **分辨率** | 0.5米 |
| **模态** | RGBIR、SAR |

**描述：** 专注于建筑物检测的多模态数据集，由SpaceNet提供，适用于城市区域的目标检测和语义分割任务。

---

#### [SEN12MS数据集](https://dataserv.ub.tum.de/s/m1474000)

| 属性 | 数值 |
|------|------|
| **覆盖范围** | 全球大部分陆地区域 |
| **影像数量** | 180,662个图像三元组 |
| **影像尺寸** | 256×256像素 |
| **分辨率** | 多光谱（MS）：10米，SAR：20米 |
| **模态** | 多光谱（MS）、SAR |
| **特点** | 涵盖不同区域的季节性影像，提供大规模数据集，适用于多模态遥感目标分类的深度学习模型训练 |

**描述：** 大规模数据集，包含对应的Sentinel-1双极化SAR数据、Sentinel-2多光谱影像和MODIS土地覆盖图。所有图像块均经过地理配准，分布在所有有人居住的大陆，并覆盖所有气象季节 [^18^]。

---

### 光学/高光谱+LiDAR数据集

融合光学/高光谱影像与激光雷达（LiDAR）数据的数据集，可实现高精度目标分类和三维特征提取。

#### [MUUFL Gulfport数据集](https://github.com/GatorSense/MUUFLGulfport)

| 属性 | 数值 |
|------|------|
| **类型** | 高光谱+LiDAR |
| **影像尺寸** | 325×220像素 |
| **模态** | 高光谱（HS）、LiDAR |
| **覆盖区域** | 美国佛罗里达州格尔夫波特 |

**描述：** 高光谱与LiDAR航空配对数据集，包含校园子影像（海拔3500英尺和6700英尺），配有配准的LiDAR数字高程模型（DEMs）、目标真值信息和检测/评分代码。数据集还包含地理标记照片、场景标签和技术报告。DOI: [10.5281/zenodo.1186326](https://doi.org/10.5281/zenodo.1186326)（MIT许可证）。

**引用说明：** 使用本数据集时，请引用相关技术报告（详见仓库中的详细引用信息）。

---

#### [特伦托数据集（Trento Dataset）](https://github.com/tyust-dayu/Trento)

| 属性 | 数值 |
|------|------|
| **覆盖区域** | 意大利特伦托农村地区 |
| **影像尺寸** | 600×166像素 |
| **分辨率** | 1米 |
| **模态** | 高光谱成像（HSI）、LiDAR |
| **目标类别** | 6类（苹果树、建筑、地面、木材、葡萄园、道路） |

**描述：** 农村土地覆盖和目标分类的基准数据集，适用于评估高光谱-LiDAR融合算法。

---

#### [Houston2013数据集](https://machinelearning.ee.uh.edu/?page_id=459)

| 属性 | 数值 |
|------|------|
| **类型** | 高光谱+LiDAR |
| **影像尺寸** | 1905×349像素 |
| **分辨率** | 2.5米 |
| **模态** | 高光谱（144波段，380-1050nm）、LiDAR DSM |

**描述：** 来自[IEEE GRSS 2013数据融合竞赛](https://machinelearning.ee.uh.edu/2013-ieee-grss-data-fusion-contest/)的数据集，广泛用作高光谱与LiDAR数据融合及目标分类研究的基准。数据可通过官方网站申请获取，需遵守使用条款 [^12^]。

---

### 高光谱+多光谱数据集

融合高光谱和多光谱影像的多模态数据集，适用于光谱特征分析和目标分类任务。

（将持续更新更多数据集，欢迎贡献！）

---

### 注意事项

- 部分数据集URL可能需要访问权限或注册，请参考官方链接获取详细下载说明。

- 使用数据集时，请遵守相应的许可证协议，并按要求引用相关论文/技术报告。

- **SEN12MS下载方式：** 可通过以下方式使用`wget`或`rsync`下载：
  - 用户名：`m1474000`
  - 密码：`m1474000`
  - 服务器：`dataserv.ub.tum.de` [^18^]

---

### 贡献指南

欢迎大家贡献内容以扩展本列表！请提交拉取请求（Pull Request），并为每个新数据集提供以下信息：

- 数据集名称和官方URL（有效且完整）
- 关键元数据（提供方、影像数量、尺寸、分辨率、模态）
- 简要描述和适用的研究任务
- 引用信息（如有）

---
