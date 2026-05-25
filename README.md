# BIAPLS 2026 - DAY 3 - PM SESSION 

Materials for the Day 3 afternoon session of the [Intro to BioImaging Analysis with Python for Life Scientists](https://www.eurobioimaging.eu/news/evolve-distributed-in-person-training-course-intro-to-bioimaging-analysis-with-python-for-life-scientists/) course, focused on accessible deep learning tools for bioimage analysis.


---

## Environment setup 

### 1. Open a terminal

Make sure you have **conda** installed and available.


### 2. Create a new environment - dl_tools

```bash
conda create -y -n dl_tools -c conda-forge python=3.10
```

-- Wait for installation to finish --

### 3. Activate the environment

```bash
conda activate dl_tools
```

### 4. Install required packages with pip

```bash
python -m pip install "napari[all]"==0.6.6 cellpose[gui]==3.1.1.1 empanada-napari
```

-- Wait for installation to finish --