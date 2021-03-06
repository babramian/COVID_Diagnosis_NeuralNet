# COVID_Diagnosis_NeuralNet

Jupyter notebooks files containing code for a neural network meant to diagnose patients for COVID-19.

# INCLUDED FILES:
  - Covid_Diagnosis_Neural_Net : contains code for training and saving a baseline neural network
  - Covid_NN : Contains code for training and saving a slightly more complex and accurate neural network
  - Covid_preprocessing : Contains code for preprocessing dirty data found online (one hot, normalization, resampling)
  - COVID_Diagnosis_Pipeline : Contains code for the full data ingestion pipeline (preprocessing, model loading, creating and saving predictions)

# ACCURACY RATES:
  - Saw highs of ~86% prediction accuracy

# DATA:
@dataset{2020covidclinicaldata,
  author =       {Carbon Health and Braid Health},
  title =        {Coronavirus Disease 2019 (COVID-19) Clinical Data Repository},
  howpublished = {Accessed from \url{https://covidclinicaldata.org/.}},
  year =         2020,
  version =      {10-20-2020}
}
