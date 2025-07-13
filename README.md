# Well-Logs_Predictive_Models

## 📌 Introduction - Project Objective   
This work represents my Master's Thesis in Petroleum Engineering titled:
> Development of Supervised Machine Learning Models for the Prediction of Well-Logs & Application on Wells at São Francisco and Santos Basins, Brazil"


The objective of this research is to develop a Python code, from scratch, that implements supervised machine learning (ML) algorithms, specifically Random Forest (RF) and Gradient Boosting (GB), to build ML models for accurately predicting various types of well-logs. Two separate case studies are conducted to evaluate the functionality and effectiveness of the code. In both studies, the ML models are trained on a first well (training well) and tested on a second well (test well). The first case study focuses on the São Francisco onshore Brazilian basin. It serves as a preliminary exercise for model development and data familiarization. The goal is to predict two conventional well-logs: the calculated effective porosity and the measured compressional wave slowness logs. The second case study centers around the Santos offshore Brazilian basin, particularly the deep-water pre-salt carbonate reservoir area of the Itapu Oil Field. The attention of this research is primarily directed toward this second case study. The target is to predict high technological well-logs, including nuclear magnetic resonance (NMR) total, effective, and free fluid porosity logs.

## 📌 Well-Log Datasets Used
1. **São Francisco Basin Onshore Data** that are published by ANP (Agência Nacional de Petróleo). The two wells of interest are 1-BRSA-871-MG and 1-BRSA-948-MG. You can access these well-logs at [https://reate.cprm.gov.br/anp/TERRESTREen].
2. **Santos Basin Offshore Data** that are physically delivered by ANP, in hard drive form. The two wells of interest are 1-BRSA-1116-RJS and 3-BRSA-1215-RJS.

🚦These predictive ML models can be applied to various well-log datasets🚦

## 📌 3 Folders Containing Notebooks
1. 📗 Lithology_Visualization:
+ ```Lithology_Columns_SãoFrancisco_Santos_Basins.ipynb```
2. 📙 LogData_Collection_and_Visualization:
+ ```RequiredDataset_CompressionalWaveSlownessLogPrediction_São FranciscoBasin.ipynb```
+ ```RequiredDataset_EffectivePorosityLogPrediction_São FranciscoBasin.ipynb```
+ ```RequiredDataset_nmrPorosityLogsPrediction_SantosBasin.ipynb```
3. 📘 Logs_Prediction:
+ ```CompressionalWaveSlownessLog_Prediction.ipynb```
+ ```EffectivePorosityLog_Prediction.ipynb```
+ ```nmrPorosityLogs_Prediction_FirstAttempt.ipynb```
+ ```nmrPorosityLogs_Prediction_SecondAttempt.ipynb```

## 📌 Hardware and Software Used 
This research was conducted using a MacBook Pro (16", 2021) equipped with an M1 processor, and Python 3.9.12.

## 📌 Citation 
@phdthesis{de2023development,
  title={Development of Supervised Machine Learning Models for the Prediction of Well-Logs \& Application on Wells at São Francisco and Santos Basins, Brazil},
  author={De Pellegrini, Vittoria},
  year={2023},
  school={Politecnico di Torino}
}
