# Visual AI for Manufacturing with FiftyOne

This repository contains a collection of **11 interactive Jupyter notebooks** that demonstrate how to use [FiftyOne](https://voxel51.com/fiftyone) to accelerate workflows in **manufacturing, anomaly detection, defect inspection, and worker safety**.  

From **dataset exploration** to **embeddings, clustering, augmentations, 3D visualization, and video analytics**, these notebooks showcase how FiftyOne enables **data-centric AI development** in industrial and manufacturing contexts.  

---

## 📂 Repository Structure

| Notebook | Topic | Description |
|----------|-------|-------------|
| `01_dataset_exploration_MVTecAD.ipynb` | Dataset Exploration (MVTec AD) | Explore the MVTec Anomaly Detection dataset, visualize samples, and inspect metadata with FiftyOne. |
| `02_embeddings_MVTecAD.ipynb` | Embeddings | Generate embeddings for anomaly detection tasks and visualize them interactively. |
| `03_embeddings_clustering_MVTecAD.ipynb` | Embeddings Clustering | Perform clustering analysis on embeddings to group anomalies and normal samples. |
| `04_custom_embeddings_MVTecAD.ipynb` | Custom Embeddings | Use custom feature extractors to compute embeddings tailored for industrial data. |
| `05_model_evaluation_MVTecAD.ipynb` | Model Evaluation | Evaluate anomaly detection models with FiftyOne’s evaluation modules. |
| `06_albumentations_MVTecAD.ipynb` | Data Augmentation | Apply [Albumentations](https://albumentations.ai/) to enrich datasets and improve robustness. |
| `07_3D_Visualization_MVTec_3D.ipynb` | 3D Visualization | Visualize 3D sensor data and meshes with FiftyOne for advanced defect inspection. |
| `08_dataset_exploration_MVTecAD2.ipynb` | Extended Dataset Exploration | Dive deeper into dataset splits, statistics, and visual inspection workflows. |
| `09_dataset_exploration_VAD.ipynb` | Valeo Anomaly Dataset (VAD) |Large-scale dataset collected directly from an actual automotive production line |
| `10_dataset_exploration_PPE.ipynb` | PPE Detection | Explore datasets for **Personal Protective Equipment (PPE)** compliance monitoring. |
| `11_video_analytics_safe_unsafe.ipynb` | Video Analytics | Classify and analyze safe vs unsafe behaviors in video data. |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/paularamo/fiftyone-workshop-manufacturing.git
cd fiftyone-workshop-manufacturing
```

### 2. Create environment

We recommend using Python 3.9+ with conda or venv

```bash
conda create -n fiftyone-manufacturing python=3.9
conda activate fiftyone-manufacturing
```

Or venv

```bash
python3 -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install fiftyone torch torchvision albumentations
pip install jupyter matplotlib scikit-learn
```

Some notebooks may require additional packages such as open3d, timm, or pandas. Install them as needed:

```bash
pip install open3d timm pandas
```

---

## 📘 Usage

Launch Jupyter:
```bash
jupyter notebook
Open any notebook from the list and run the cells.
```

Open any notebook from the list and run the cells.

You can start with:

- `01_dataset_exploration_MVTecAD.ipynb` → to learn dataset exploration.  
- `05_model_evaluation_MVTecAD.ipynb` → to evaluate model results.  
- `11_video_analytics_safe_unsafe.ipynb` → for video-based safety monitoring.  


## 🔍 Example Workflows

- **Defect Inspection:** Use MVTec AD with embeddings and clustering to group normal vs defective parts.  
- **Model Debugging:** Evaluate predictions interactively with FiftyOne to identify failure cases.  
- **Safety Monitoring:** Detect PPE compliance and unsafe actions in manufacturing videos.  
- **3D Inspection:** Visualize industrial parts with 3D meshes and anomaly maps.  

## 🙌 Acknowledgments

- [MVTec Anomaly Detection Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad)  
- [Albumentations](https://albumentations.ai/)  
- [FiftyOne](https://voxel51.com/fiftyone) by Voxel51  

---

👉 This repo is designed to help researchers, engineers, and practitioners apply **Visual AI in manufacturing environments** using **data-centric workflows powered by FiftyOne**.  