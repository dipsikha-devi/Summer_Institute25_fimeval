# Summer_Institute25_fimeval
# 📦 fimeval

`fimeval` is a Python package designed for automatic evaluation of flood inundation maps from different and visualizing results. It is developed under Surface Dynamics Modeling Lab (SDML), Department of Geography and the Environment at The University of Alabama, United States.
 This guide provides step-by-step installation instructions for both macOS, Windows users and for Cloud sources like Google Colab and 2i2c.

---

## 🔧 Installation Instructions

### 1. ✅ Prerequisites

Before installing `fimeval`, ensure the following software are installed:

- **Python**: Version 3.10 or higher  
- **Anaconda**: For managing environments and dependencies  
- **GIS Software**: For Visulalisation
  - [ArcGIS](https://www.esri.com/en-us/arcgis/products/index) or [QGIS](https://qgis.org/en/site/)
- **Optional**:
  - [Google Earth Engine](https://earthengine.google.com/) account
  - Java Runtime Environment (for using GEE API)

---

### 2. 🐍 Install Anaconda

If Anaconda is not installed, download and install it from the [official website](https://www.anaconda.com/products/distribution).

---

### 3. 🌐 Set Up Virtual Environment

#### 💻 For Mac Users

Open **Terminal** and run:
```bash

# Create a new environment named 'fimeval'
conda create --name fimeval python=3.10

# Activate the environment
conda activate fimeval

# Install Jupyter Notebook
pip install notebook

# Install fimeval package
pip install fimeval

```

### ☁️ Google Colab Version

To use fimeval in Google Colab, follow the steps below:

## Upload Files
Upload all necessary input files (e.g., raster, shapefiles, model outputs) to your Google Drive.
## Open Google Colab
Go to Google Colab and sign in with a valid Google account.
## Mount Google Drive
In a new Colab notebook, mount the  Google Drive
```bash
pip install fimeval
```

# CIROH 2i2c JupyterHub Setup

1. Upload necessary files to the 2i2c environment.

2. Open a new terminal and create a new environment.

3. Install `fimeval` in the environment:

```bash
pip install fimeval




 
