# Radiology-Report-Generation

1) DATA COLLECTION

The following 4 sources are finalized for collecting data focussed on Chest X Rays

1) https://stanfordaimi.azurewebsites.net/datasets/8cbd9ed4-2eb9-4565-affc-111cf4f7ebe2
2) https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university
3) https://nihcc.app.box.com/v/ChestXray-NIHCC
4) https://physionet.org/content/mimic-cxr/2.1.0/  

The datasets from each of the sources is uploaded to google drive. 

The first three sources are selected to be used to build an initial model, which is then fine-tuned on the last source to adapt the pre-trained model to the new data distribution.

2) SELECTION OF INITIAL TECH STACK

Google colab is selected as the starting tool for Exploratory Data Analysis (EDA), Data Preprocessing and model building because of the following reasons:

◻️Handling of huge dataset size

The final dataset (initial) that is compiled from three different data sources is a huge dataset ~ 200GB. One of the most efficient workarounds is to upload it all on a google drive and access it in google colab, which potentially saved us from overwhelming the local systems.

◻️Handling of GPU/TPU usage

Allowed us to make use of cloud GPU/TPU service for model building.
