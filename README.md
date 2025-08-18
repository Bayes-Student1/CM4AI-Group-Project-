2025 CM4AI at UAB
-----------------------------------------------------------------------------------------------

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0f648033-7bb3-4f70-9d8f-9084a690e306" />

This repo is related to the participation in the [2025 CM4AI at UAB ](https://www.uab.edu/medicine/informatics/news-events/events/cm4ai-codefest-at-uab)

### Our Team
- Rebecca Bernal
- Morgan Smith
- Arash Abadi
- Jedediah Smith
- Mona Shabana

### Project
AI-Based Multi-Channel Deep Learning Pipeline for HPA Cell Segmentation

### Goal
Our objective is to evaluate alternate 'SubCell' image embedding methods for immunofluorescence images by comparing two approaches: 
1. Direct embedding – applying SubCell embeddings without segmentation.
2. Segmentation-based embedding – performing cell/nuclei segmentation prior to embedding.

### Created By
Rebecca Bernal on August 15th, 2025


### This Repo includes: 
1. Data
    - Raw Immunofluorescence Data used for analysis (HPA Cell Segmentation)
2. Full CM4AI Script_RBernal.ipynb
    - consists of the full python code that was written during day 1 and day 2 of the Code Fest.
3. HPA Cell Segmentation Script.ipynb
     - subset of the 'Full CM4AI Script_RBernal.ipynb' script.
     - prints only the HPA Cell Segmentaion with Multiple Channels section
4. Segmentation_results2
    - results for the HPA Cell Segmentation with Multiple Channels


-----------------------------------------------------------------------------------------------


Day 1 - August 10th, 2025
-----------------------------------------------------------------------------------------------
Installed 'Visual Studios Code', Anaconda,

Note that due to storage issues a subset of the raw IF data was used N=536. 134 in each untreated and treated (Vorinostat, Paclitaxed). 33 in each 'blue', 'red', 'green', and 'yellow' folder.

Reading:
- [CM4AI Overview Pre-Print](https://www.biorxiv.org/content/10.1101/2024.05.21.589311v1)
- [Cell Mapping Pipeline](https://academic.oup.com/bioinformatics/article/41/6/btaf205/8159056)

Agenda:
The official CM4AI Cell Map Pipeline Code was used to perform the direct embedding.
- [GitHub Repository](https://github.com/idekerlab/cellmaps_pipeline)
        - [notebooks](https://github.com/idekerlab/cellmaps_pipeline/blob/main/notebooks/step-by-step-guide-run-cellmaps-pipeline.ipynb)
- [Documentation](https://cellmaps-pipeline.readthedocs.io/en/latest/)












