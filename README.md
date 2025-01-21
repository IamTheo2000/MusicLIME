<img src="https://github.com/user-attachments/assets/17728824-8713-4627-8d0f-03588df02f83" alt="cropmusiclime_logo_final" width="200">
# MusicLIME: Explainable Multimodal Music Understanding

This repository contains the code implementation for the paper **"MusicLIME: Explainable Multimodal Music Understanding"**. It provides all necessary resources and guidance for recreating our experiments and exploring explainable AI (XAI) in the context of music understanding.
The paper can be accessed on [arXiv](https://arxiv.org/abs/2409.10496).

If you use this work, please cite it as follows:

```bibtex
@misc{sotirou2024musiclimeexplainablemultimodalmusic,
      title={MusicLIME: Explainable Multimodal Music Understanding}, 
      author={Theodoros Sotirou and Vassilis Lyberatos and Orfeas Menis Mastromichalakis and Giorgos Stamou},
      year={2024},
      eprint={2409.10496},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2409.10496}, 
}
```
## Repository Structure

The repository is organized into four main folders:

1. **Dataset - Related**
2. **Model - Related**
3. **MusicLIME & GlobalAggregates (XAI related)**
4. **Results**

### 1. Dataset - Related

This folder contains notebooks and scripts focused on dataset preparation. 

- If you're interested in recreating the datasets we used, that is refining **Music4All** and **AudioSet**, this is where to start.
- Inside, you’ll find detailed processes on how to preprocess the datasets, including filtering, refining, and augmenting data for use in our models.
- We also provide audio spectrograms and lyrics matched with ids both in google drive and as kaggle datasets.

### 2. Model - Related

This folder is dedicated to training models for multimodal music understanding.

- If you would like to skip dataset creation and directly start with **training models**, study the contents here.
- It contains:
  - Information about the models used.
  - Notebooks detailing the training process.
  
We also provide **state dictionaries** for the trained models, allowing you to bypass the training process and directly explore the next steps.

### 3. MusicLIME & GlobalAggregates (XAI related)

Here you’ll find the code for implementing explainability on multimodal music understanding using **MusicLIME**.

- The folder includes methods for generating **local explanations** and the process of **global aggregation** of these explanations to understand model behavior on a larger scale.
- The code is designed to explain both audio and lyric modalities using **multimodal explanations**.

### 4. Results

In this folder, we present the outcomes of our experiments.

- **Model metrics**: Performance metrics for the models we trained.
- **Global Aggregations**: Results of applying global aggregation on local explanations.

### Contact
For any questions or issues regarding the code, please feel free to open an issue or reach out to us at theodorossotirou@gmail.com
