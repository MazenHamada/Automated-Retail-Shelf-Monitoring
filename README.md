# Automated Retail Shelf Monitoring Analysis
This repository contains a single Google Colab Notebook that demonstrates a complete workflow for analyzing retail shelf images. The project uses data stored in Google Drive for easy and reliable access.

---

## 🚀 How to Run This Project

This project is designed to be run in Google Colab. Follow these steps for the best experience.

### Step 1: Get the Dataset

This project uses the **SKU-110K** dataset. You must download the annotation files to your computer before you begin.
* **Download Link:** [SKU-110K Official GitHub Repository]([https://github.com/eg4000/SKU-110K](https://github.com/eg4000/SKU110K_CVPR19))

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

## ⚙️ Key Technologies

- Python
- Google Colab & Google Drive
- Pandas & NumPy
- Matplotlib
- Streamlit
- FPDF2
- PyTorch/Torchvision
