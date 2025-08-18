2025 CM4AI at UAB
-----------------------------------------------------------------------------------------------

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0f648033-7bb3-4f70-9d8f-9084a690e306" />

This repo is related to the participation in the [2025 CM4AI at UAB ](https://www.uab.edu/medicine/informatics/news-events/events/cm4ai-codefest-at-uab)

### Our Team
- Rebecca Bernal (UT San Antonio)
- Morgan Smith (UT San Antonio)
- Arash Abadi (UAB)
- Jedediah Smith (UAB)
- Mona Shabana (UAB)

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


Day 1 - August 14th, 2025
-----------------------------------------------------------------------------------------------
Installed 'Visual Studios Code', Anaconda,

Note that due to storage issues a subset of the raw IF data was used N=536. 134 in each untreated and treated (Vorinostat, Paclitaxed). 33 in each 'blue', 'red', 'green', and 'yellow' folder.

Background Materials:
- [CM4AI Overview Pre-Print](https://www.biorxiv.org/content/10.1101/2024.05.21.589311v1)
- [Cell Mapping Pipeline](https://academic.oup.com/bioinformatics/article/41/6/btaf205/8159056)
- [Cell Maps for AI (CM4AI) - Introduction & Overview](https://www.youtube.com/watch?v=wiGgof7gY3w)
- [The Cell Maps Pipeline](https://www.youtube.com/watch?v=AK2eQbOys2I)
- [CM4AI Data - Immunofluorescence (IF)](https://www.youtube.com/watch?v=Ys5rFvMMtE4)

Agenda:

The official CM4AI Cell Map Pipeline Code was used to perform the direct embedding.
- [GitHub Repository](https://github.com/idekerlab/cellmaps_pipeline)
        - [notebooks](https://github.com/idekerlab/cellmaps_pipeline/blob/main/notebooks/step-by-step-guide-run-cellmaps-pipeline.ipynb)
- [Documentation](https://cellmaps-pipeline.readthedocs.io/en/latest/)

Explored the data using [CM4AI Tutorial Immunofluorescense](https://github.com/CM4AI/cm4ai-tutorial-immunofluorescence/tree/main). Click on src:

- explore the data: [eda.ipynb](https://github.com/CM4AI/cm4ai-tutorial-immunofluorescence/blob/main/src/eda.ipynb)
- generate embedding with cellmaps image embedder: [generate_embeddings.py](https://github.com/CM4AI/cm4ai-tutorial-immunofluorescence/blob/main/src/generate_embeddings.py)
- GENERATE A PROTEIN SIMILARITY GRAPH BASED ON THE EMBEDDING AND VISUALIZE RESULTS: [generate_graph.ipynb](https://github.com/CM4AI/cm4ai-tutorial-immunofluorescence/blob/main/src/generate_graph.ipynb)
  

-----------------------------------------------------------------------------------------------


Day 2 - August 15th, 2025
-----------------------------------------------------------------------------------------------
Now that the direct embedding has been performed. The goal is to perform cell/nuclei segmentation prior to embedding.

First, to test my segmentaion script, I ran HPA Cell Segmentaion using only the first 10 images form 'Paclitaxel' medication and 'Blue' folder. If the HPA Cell Segmentation runs with the subset dataset (n=10) then run with the full set of images. 

Agenda: 

clone [HPA Cell Segmentation](https://github.com/CellProfiling/HPA-Cell-Segmentation.git) GitHub

Using ChatGPT the following script was derived to perform HPA Cell Segmentation. Which runs nuclei segmentation on images in DATA_DIR using HPA-Cell-Segmentation and saves results to ANALYSIS_DIR/segmentation_results.

Now that the above script was successful, the objective is to perform HPA Cell Segmentation on multiple channels (red, yellow, blue, green). View 'HPA Cell Segmentation Script.ipynb' for detailed notes.


-----------------------------------------------------------------------------------------------


Futher work - August 16 - 21, 2025
-----------------------------------------------------------------------------------------------
Rebecca: Currently rerunning the segmentation and renaming the files VS Code

Morgan: Cropping and subcellular visualization on the stacked images (all colors on new dataset) via Google Colab (possibly Visual Studio Code)
- https://github.com/morgansmith27 

Jebediah: Subcell tutorial working to change data
- https://github.com/OriginalBrick/cm4ai-codefest
  
Arash: Project management and github maintanence
- https://github.com/arashabadi/cm4ai_codefest2025
  
Mona: Background/Significance for powerpoint
Editing google slides/powerpoint for everyone


-----------------------------------------------------------------------------------------------


Virtual Presentation - August 22, 2025
-----------------------------------------------------------------------------------------------

https://docs.google.com/presentation/d/190pZ3yB4t-PpOOlBwdOuzx1AJcnQugEER8N1m3eJME8/edit?usp=sharing 












