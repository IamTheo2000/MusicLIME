# MusicLIME: Explainable Multimodal Music Understanding

This repository contains the code implementation for the paper **"MusicLIME: Explainable Multimodal Music Understanding"**. It provides all necessary resources and guidance for recreating our experiments and exploring explainable AI (XAI) in the context of music understanding.

## Repository Structure

The repository is organized into four main folders:

1. **Dataset - Related**
2. **Model - Related**
3. **MusicLIME & GlobalAggregates (XAI related)**
4. **Results**

### 1. Dataset - Related

This folder contains notebooks and scripts focused on dataset preparation. 

- If you're interested in recreating the datasets we used, such as refining **Music4All** and **AudioSet**, this is where to start.
- Inside, you’ll find detailed processes on how to preprocess the datasets, including filtering, refining, and aligning data for use in our models.

### 2. Model - Related

This folder is dedicated to training models for multimodal music understanding.

- If you would like to skip dataset creation and directly start with **training models**, study the contents here.
- It contains:
  - Information about the models used.
  - Notebooks detailing the training process.
  - Code to extract features such as spectrograms and lyrics, matched with their corresponding IDs and labels.
  
We also provide **state dictionaries** for the trained models, allowing you to bypass the training process and directly explore the next steps.

### 3. MusicLIME & GlobalAggregates (XAI related)

Here you’ll find the code for implementing explainability on multimodal music understanding using **MusicLIME**.

- The folder includes methods for generating **local explanations** and the process of **global aggregation** of these explanations to understand model behavior on a larger scale.
- The code is designed to explain both audio and lyric modalities using **multimodal explanations**.

### 4. Results

In this folder, we present the outcomes of our experiments.

- **Model metrics**: Performance metrics for the models we trained.
- **Global Aggregations**: Results of applying global aggregation on local explanations.
- **Cherry-picked Examples**: Selected local explanations showcasing the explainability features of the models.

## Recreating Experiments

You can recreate our experiments from various points, depending on your focus:

1. **Dataset Creation**: Start from the **Dataset - Related** folder to recreate and refine the **Music4All** and **AudioSet** datasets.
   
2. **Model Training**: If you already have spectrograms, lyrics, and labels, you can skip the dataset creation and go directly to the **Model - Related** folder to train the models.

3. **Explainability (XAI)**: If you want to explore explainable AI directly, use the pretrained model state dictionaries and focus on the **MusicLIME & GlobalAggregates** folder for multimodal explanations and aggregation methods.

### Contact
For any questions or issues regarding the code, please feel free to open an issue or reach out to us at theodorossotirou@gmail.com
