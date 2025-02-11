# HRA-AMAP Assessment: Bilateral Kidney Analysis

This repository contains my work as part of the **HRA-AMAP** assessment, where I performed 3D analysis and visualization of kidney models. The repository includes separate analysis of the **Left Kidney**, **Right Kidney**, and **Bilateral Symmetry** analysis, using **GLB model files** (Male Left and Male Right Kidney) from the [Human Atlas 3D Reference Library](https://humanatlas.io/3d-reference-library?version=2.2&organ=All%20Organs).

## Assignment Overview

I focused on the analysis of kidney models using the **AMAP framework**, as outlined in the official [AMAP GitHub repository](https://github.com/cns-iu/hra-amap). The following tasks were completed:

1. **Left Kidney Analysis**  
2. **Right Kidney Analysis**  
3. **Bilateral Symmetry Analysis** (Combining Left and Right Kidneys for Comparative Symmetry)

## Tasks Completed

### 1. **Download GLB Model Files**
   - Downloaded the **Male Left Kidney** and **Male Right Kidney** GLB models from the **Human Atlas 3D Reference Library** for analysis and visualization.

### 2. **Setup HRA-AMAP Repository**
   - Successfully set up the **AMAP GitHub repository** on my local machine and ensured all dependencies were installed.

   - Instructions for setup:
     ```bash
     git clone https://github.com/cns-iu/hra-amap.git
     cd hra-amap
     ```

### 3. **Analysis and Execution of Jupyter Notebooks**

   - **Left Kidney Analysis**:  
     I performed a comprehensive analysis of the **Male Left Kidney** GLB model, focusing on structure, morphology, and key 3D properties using various AMAP tools. The analysis includes visualizing the kidney's 3D surface, identifying significant structures, and generating projections for further research.

   - **Right Kidney Analysis**:  
     Similar to the Left Kidney analysis, I analyzed the **Male Right Kidney** GLB model to compare the morphological differences, providing detailed insights into anatomical features, and visualizing the model in 3D.

   - **Bilateral Symmetry Analysis**:  
     In this notebook, I combined both the **Left and Right Kidney** models to perform a **Bilateral Symmetry Analysis**. This analysis compares both kidneys for symmetry, helping to highlight the congruency of their anatomical structures. The process includes generating visualizations to clearly demonstrate symmetry and asymmetry.

### 4. **Create a Personal Repository**
   - Created my own GitHub repository to submit the completed analysis and results.
   - Committed and pushed the modified versions of the notebooks with the results of all the analyses.

### 5. **Visualization and Documentation**
   - **Left and Right Kidney Visualizations**: Generated 2D snapshots and 3D visualizations to capture key features of both kidney models. The output provides clear visual comparisons of the two kidneys' structures.
   - **Bilateral Symmetry Visualization**: Generated 3D projections and side-by-side comparison visualizations to highlight symmetry between the two kidneys.

   - The **README file** contains detailed documentation of the analysis steps, issues encountered during execution, and the proposed optimizations for improving the process.

## Results and Visualizations

### **Left Kidney**:
- Detailed 3D visualization showcasing the morphology and structural features of the Left Kidney.
- Key observations and visual interpretations have been included in the notebook.

### **Right Kidney**:
- Similar 3D visualizations, with a focus on understanding the anatomical uniqueness of the Right Kidney.
  
### **Bilateral Symmetry**:
- A final notebook combines the analyses of both kidneys to perform a bilateral symmetry check, with graphical results and visual representations highlighting symmetry or asymmetry.

## Challenges Faced & Resolutions

- **Data Compatibility**: Encountered minor issues with incompatible GLB files during the initial setup, which were resolved by ensuring proper model compatibility.
- **3D Rendering Issues**: Faced difficulties displaying the 3D models in Jupyter due to graphical rendering conflicts, which were overcome by switching to a more compatible rendering backend.
  
## Suggested Optimizations

- **Optimization 1**: Implementing more efficient rendering algorithms for large 3D models to speed up the visualization and reduce memory usage.
- **Optimization 2**: Potential use of multi-threading or parallel processing for rendering large model projections more efficiently.
- **Optimization 3**: Consideration of incorporating **machine learning techniques** to automate feature detection and enhance model comparison.

