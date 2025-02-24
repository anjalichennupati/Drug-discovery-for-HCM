
# Target Based Drug Discovery for HCM
# Overview

This project focuses on computational drug discovery for Hypertrophic Cardiomyopathy (HCM) using machine learning techniques. The primary target is TNNI3, a gene linked to HCM. The study leverages molecular descriptors, IC50 filtering, and visualization techniques to identify potential drug candidates. A RandomForest ML model is implemented to predict pIC50 (-log10(IC50)) values and compare them with experimental data.




## Block Diagram

- The below block diagram gives an overview of the overall funtionality of the implemented project
 <p align="center">
  <img src="https://i.postimg.cc/qM0zCr5P/Picture7.png" alt="App Screenshot" width="600">
</p>

## Features

- **Bioactivity Data Preprocessing**: ensures the dataset is clean and consistent by filtering molecular data based on IC50 values. This step removes inconsistencies and prepares the data for descriptor calculation.

<p align="center">
  <img src="https://i.postimg.cc/Jhng2wHt/Picture1.jpg" alt="App Screenshot" width="300">
</p>

- **Chemical Space Visualization**: Molecular properties like MW, LogP, NumHDonors, and NumHAcceptors are visually plotted. This ensures better interpretation of compound characteristics and their potential efficacy. Boxplots categorize these properties based on bioactivity class for clearer insights.

<p align="center">
  <img src="https://i.postimg.cc/TwxkvZpr/Picture2.jpg" alt="App Screenshot" width="300">
    <img src="https://i.postimg.cc/wM7LCVcX/Picture3.jpg" alt="App Screenshot" width="300">

</p>

<p align="center">
  <img src="https://i.postimg.cc/L513WSpk/Picture4.jpg" alt="App Screenshot" width="300">
    <img src="https://i.postimg.cc/yYnDz580/Picture5.jpg" alt="App Screenshot" width="300">

</p>






- **ML Model Performance (RandomForest Predictions)**: The ML model is trained using a RandomForest algorithm to predict pIC50 values and evaluate drug potential. The model’s performance is assessed using regression plots that compare experimental and predicted values. This provides an understanding of how well the model generalizes bioactivity prediction.
<p align="center">
  <img src="https://i.postimg.cc/RVwj65Hn/Picture6.jpg" alt="App Screenshot" width="300">
</p>


## Tech Stack

**Database**: ChEMBL dataset for HCM with tnni3 as the target 

**Tools**: Python, Matplotlib, Seaborn

## Installation

1. **Install Dependencies**:
- This project was implemented on Google Colab
- Upload the required dataset files to Colab or mount Google Drive.
- Run the cells step by step to execute the workflow.

2. **PaDEL-Descriptor Calculator**: 
- padel.sh or padel.bat can be downloaded for your respective disease:
- Link: https://usegalaxy.eu/?tool_id=toolshed.g2.bx.psu.edu%2Frepos%2Fbgruening%2Fpadel%2Fpadel%2F2.21

## Running Tests

The project can be implemented and tested to verify funtionality

