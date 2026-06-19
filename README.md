# 🖼️ Detect AI vs Human Generated Images

![Computer Vision](https://img.shields.io/badge/-Computer%20Vision-1a1b26?style=flat-square&logoColor=c0caf5) ![Binary Classification](https://img.shields.io/badge/-Binary%20Classification-1a1b26?style=flat-square&logoColor=c0caf5) ![Deepfake Detection](https://img.shields.io/badge/-Deepfake%20Detection-1a1b26?style=flat-square&logoColor=c0caf5) ![CNN](https://img.shields.io/badge/-CNN-1a1b26?style=flat-square&logoColor=c0caf5) ![PyTorch](https://img.shields.io/badge/-PyTorch-1a1b26?style=flat-square&logoColor=c0caf5)

![Banner](./banner.png)

> [!IMPORTANT]
> **Host:** `Kaggle Community`  
> **Platform Link:** [Kaggle Competition](https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images)  
> **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/detect-ai-vs-human-generated-images/data)  
> **Domain:** `Deepfake & AI Image Detection`

## 📖 Overview

Developing classifiers to distinguish AI-generated images from real human photographs. Used CNNs and deep fake detection techniques to identify subtle visual artifacts.

## ⚙️ Standard Pipeline Workflow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'background': '#0f0f12', 'primaryColor': '#1a1b26', 'edgeLabelBackground':'#11111b', 'tertiaryColor': '#1a1b26'}}}%%
flowchart LR
    A[Data Gathering] --> B[Preprocessing & EDA]
    B --> C[Model Training]
    C --> D[Inference & Submission]
    style A fill:#1e1e24,stroke:#7aa2f7,stroke-width:2px,color:#c0caf5
    style B fill:#1e1e24,stroke:#bb9af7,stroke-width:2px,color:#c0caf5
    style C fill:#1e1e24,stroke:#f7768e,stroke-width:2px,color:#c0caf5
    style D fill:#1e1e24,stroke:#9ece6a,stroke-width:2px,color:#c0caf5
```

## 🗂️ Notebook Architecture & Inventory

### 📂 Preprocessing & EDA
*Data cleaning, feature engineering, and exploratory data analysis.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **Preprocessing** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/Preprocessing/v1.ipynb), [v10](./Preprocessing%20%26%20EDA/Preprocessing/v10.ipynb), [v11](./Preprocessing%20%26%20EDA/Preprocessing/v11.ipynb), [v12](./Preprocessing%20%26%20EDA/Preprocessing/v12.ipynb), [v13](./Preprocessing%20%26%20EDA/Preprocessing/v13.ipynb), [v2](./Preprocessing%20%26%20EDA/Preprocessing/v2.ipynb), [v3](./Preprocessing%20%26%20EDA/Preprocessing/v3.ipynb), [v4](./Preprocessing%20%26%20EDA/Preprocessing/v4.ipynb), [v5](./Preprocessing%20%26%20EDA/Preprocessing/v5.ipynb), [v6](./Preprocessing%20%26%20EDA/Preprocessing/v6.ipynb), [v7](./Preprocessing%20%26%20EDA/Preprocessing/v7.ipynb), [v8](./Preprocessing%20%26%20EDA/Preprocessing/v8.ipynb), [v9](./Preprocessing%20%26%20EDA/Preprocessing/v9.ipynb) | `Avg 20 KB` | `OpenCV` |

### 📂 Inference & Submission
*Prediction pipeline and Kaggle submission file generation.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📁 **EfficientNet_Inference** | Multi-Version Script | [v1](./Inference%20%26%20Submission/EfficientNet_Inference/v1.ipynb), [v10](./Inference%20%26%20Submission/EfficientNet_Inference/v10.ipynb), [v11](./Inference%20%26%20Submission/EfficientNet_Inference/v11.ipynb), [v12](./Inference%20%26%20Submission/EfficientNet_Inference/v12.ipynb), [v13](./Inference%20%26%20Submission/EfficientNet_Inference/v13.ipynb), [v14](./Inference%20%26%20Submission/EfficientNet_Inference/v14.ipynb), [v15](./Inference%20%26%20Submission/EfficientNet_Inference/v15.ipynb), [v16](./Inference%20%26%20Submission/EfficientNet_Inference/v16.ipynb), [v17](./Inference%20%26%20Submission/EfficientNet_Inference/v17.ipynb), [v18](./Inference%20%26%20Submission/EfficientNet_Inference/v18.ipynb), [v2](./Inference%20%26%20Submission/EfficientNet_Inference/v2.ipynb), [v3](./Inference%20%26%20Submission/EfficientNet_Inference/v3.ipynb), [v4](./Inference%20%26%20Submission/EfficientNet_Inference/v4.ipynb), [v5](./Inference%20%26%20Submission/EfficientNet_Inference/v5.ipynb), [v6](./Inference%20%26%20Submission/EfficientNet_Inference/v6.ipynb), [v7](./Inference%20%26%20Submission/EfficientNet_Inference/v7.ipynb), [v8](./Inference%20%26%20Submission/EfficientNet_Inference/v8.ipynb), [v9](./Inference%20%26%20Submission/EfficientNet_Inference/v9.ipynb) | `Avg 10 KB` | `PyTorch, OpenCV` |
| 📁 **EfficientNet_Inference_2** | Multi-Version Script | [v1](./Inference%20%26%20Submission/EfficientNet_Inference_2/v1.ipynb), [v10](./Inference%20%26%20Submission/EfficientNet_Inference_2/v10.ipynb), [v11](./Inference%20%26%20Submission/EfficientNet_Inference_2/v11.ipynb), [v12](./Inference%20%26%20Submission/EfficientNet_Inference_2/v12.ipynb), [v13](./Inference%20%26%20Submission/EfficientNet_Inference_2/v13.ipynb), [v14](./Inference%20%26%20Submission/EfficientNet_Inference_2/v14.ipynb), [v15](./Inference%20%26%20Submission/EfficientNet_Inference_2/v15.ipynb), [v16](./Inference%20%26%20Submission/EfficientNet_Inference_2/v16.ipynb), [v17](./Inference%20%26%20Submission/EfficientNet_Inference_2/v17.ipynb), [v18](./Inference%20%26%20Submission/EfficientNet_Inference_2/v18.ipynb), [v19](./Inference%20%26%20Submission/EfficientNet_Inference_2/v19.ipynb), [v2](./Inference%20%26%20Submission/EfficientNet_Inference_2/v2.ipynb), [v20](./Inference%20%26%20Submission/EfficientNet_Inference_2/v20.ipynb), [v21](./Inference%20%26%20Submission/EfficientNet_Inference_2/v21.ipynb), [v22](./Inference%20%26%20Submission/EfficientNet_Inference_2/v22.ipynb), [v23](./Inference%20%26%20Submission/EfficientNet_Inference_2/v23.ipynb), [v24](./Inference%20%26%20Submission/EfficientNet_Inference_2/v24.ipynb), [v25](./Inference%20%26%20Submission/EfficientNet_Inference_2/v25.ipynb), [v26](./Inference%20%26%20Submission/EfficientNet_Inference_2/v26.ipynb), [v27](./Inference%20%26%20Submission/EfficientNet_Inference_2/v27.ipynb), [v28](./Inference%20%26%20Submission/EfficientNet_Inference_2/v28.ipynb), [v29](./Inference%20%26%20Submission/EfficientNet_Inference_2/v29.ipynb), [v3](./Inference%20%26%20Submission/EfficientNet_Inference_2/v3.ipynb), [v30](./Inference%20%26%20Submission/EfficientNet_Inference_2/v30.ipynb), [v31](./Inference%20%26%20Submission/EfficientNet_Inference_2/v31.ipynb), [v32](./Inference%20%26%20Submission/EfficientNet_Inference_2/v32.ipynb), [v33](./Inference%20%26%20Submission/EfficientNet_Inference_2/v33.ipynb), [v34](./Inference%20%26%20Submission/EfficientNet_Inference_2/v34.ipynb), [v35](./Inference%20%26%20Submission/EfficientNet_Inference_2/v35.ipynb), [v36](./Inference%20%26%20Submission/EfficientNet_Inference_2/v36.ipynb), [v4](./Inference%20%26%20Submission/EfficientNet_Inference_2/v4.ipynb), [v5](./Inference%20%26%20Submission/EfficientNet_Inference_2/v5.ipynb), [v6](./Inference%20%26%20Submission/EfficientNet_Inference_2/v6.ipynb), [v7](./Inference%20%26%20Submission/EfficientNet_Inference_2/v7.ipynb), [v8](./Inference%20%26%20Submission/EfficientNet_Inference_2/v8.ipynb), [v9](./Inference%20%26%20Submission/EfficientNet_Inference_2/v9.ipynb) | `Avg 34 KB` | `PyTorch, OpenCV` |

---

## 🚀 Navigation & Usage Guidelines

> [!TIP]
> 1. **EDA & Preprocessing**: Verify data loaders, actigraphy or DICOM image transformations before model training.
> 2. **Training & Optimization**: Check model definition parameters and training logs to reproduce network weights.
> 3. **Inference & Post-Processing**: Run final pipelines to verify predictions and check submission formats.


---

> *"When the eyes can no longer believe what they see, truth becomes a shadow."*
>
> — **Vigneshwaran S**
