# Automated Retail Shelf Monitoring Analysis
This repository contains a single Google Colab Notebook that demonstrates a complete workflow for analyzing retail shelf images. The project uses data stored in Google Drive for easy and reliable access.

---

## ✅ Completed Tasks

This project successfully implements the entire data analysis pipeline, including:

1.  **Comparison Script:** Developed a Python script to compare detected products from a simulated model against a ground-truth planogram.
2.  **Shelf Analysis Metrics:** Created and calculated key metrics for shelf analysis:
    - Out-of-Stock Percentage
    - Planogram Compliance Score
    - Number of Misplaced Items
3.  **Interactive Dashboard:** Built a dashboard using Streamlit that allows a user to upload a shelf image and see the analysis results visually.
4.  **Manager Summary Reports:** Generated text and PDF reports for store managers, highlighting critical issues like empty shelves and major compliance deviations.
5.  **Performance Tracking:** Created a system to track model performance over time as new shelf images are analyzed and visualized the results in a trend chart.

---

## 🚀 How to Run This Project

This project is designed to be run in Google Colab. Follow these steps for the best experience.

### Step 1: Get the Dataset

This project uses the **SKU-110K** dataset. You must download the annotation files to your computer before you begin.
* **Download Link:** [SKU-110K Official GitHub Repository](https://github.com/eg4000/SKU110K_CVPR19)

### Step 2: Set Up Your Google Drive

1.  **Upload Data:** On your own Google Drive, create a folder structure like `My Drive/Colab_Datasets/SKU-110K_data/`. Upload the `annotations_test_corrected.csv` file (and any others you need) into this folder.
2.  **Make a Copy of the Notebook:** Open the `Automated_Retail_Shelf_Monitoring.ipynb` notebook from this repository in Google Colab, then go to `File` > `Save a copy in Drive`. This saves the notebook to your own Drive and makes it editable.

### Step 3: Run the Notebook

1.  **Open Your Copy:** Open the copy of the notebook you just saved to your Google Drive.
2.  **Connect to Drive:** Run the very first code cell. It will ask you to authorize access to your Google Drive. Follow the prompts.
3.  **Update Data Path:** In that same first cell, **make sure the `DATA_FOLDER_PATH` variable points to the folder where you saved the data in Step 2.**
    ```python
    # Example:
    DATA_FOLDER_PATH = '/content/drive/MyDrive/Colab_Datasets/SKU-110K_data/'
    ```
4.  **Execute Remaining Cells:** Run the rest of the notebook cells in order from top to bottom to perform the analysis, generate reports, and launch the dashboard.

---

## 🔗 Colab Notebook Link
[Automated_Retail_Shelf_Monitoring.ipynb](https://colab.research.google.com/drive/1QSD-9TiykV2T6ulWVNaLgSMx254KSAiF?usp=sharing)

---

## ⚙️ Key Technologies

- Python
- Google Colab & Google Drive
- Pandas & NumPy
- Matplotlib
- Streamlit
- FPDF2
- PyTorch/Torchvision
