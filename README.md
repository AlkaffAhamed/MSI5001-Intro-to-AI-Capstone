# MSI5001 Intro to AI Capstone Project

This repository contains our code files for the Capstone Project of module MSI5001 Introduction to AI: Concepts, Applications, and Evaluation. 

Team: 26

Team Members: A Alkaff Ahamed, Wong Kee Fong, Dev Akhbar

Submission Date: 4th November 2025

Guide: Dr. Prabhu Natarajan

## Instruction to Run Locally

**Note:** 

- Make sure you have a GPU computer, otherwise the training will be very long in CPU

**Steps:**

1. **Install Anaconda** from the official website: [https://www.anaconda.com/download](https://www.anaconda.com/download)

2. **Open Anaconda Prompt**** and **create the environment** using the file inside Supporting Materials Folder (`tf.yml`) 
   *(If the environment doesn't install, simplify the `tf.yml` file and try again)*

   ```sh
   conda env create -f tf.yml
   ```

3. **Activate** the environment 

   ```sh
   conda activate tf
   ```

4. **Run** Jupyter notebook 

   ```sh
   jupyter notebook
   # Alternatively if the jupyter is available in start menu, it can be used as well
   ```

5. **Open** the notebooks **from the Jupyter interface**

6. **Change the `BASE_DIR`** to where the dataset is in **every notebook** before running

7. **Run** the programs like running in colab

## Instruction to Run in Colab

1. **Upload** the Notebooks **with the dataset**
2. **Change the `BASE_DIR`** to where the dataset was uploaded 
3. **IMPORTANT:** Run the notebooks in order 
   - `01_preprocessing` → `02_outlier_removal` → `03_classical_ml` → `04_dl_spectro`
4. **Output file** from the **previous notebooks** must be **uploaded together with the dataset** 

