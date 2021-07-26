# Doti
This repo is about the projects in Doti, namely chatbot and sentiment analysis with pain levels. For chatbot, the dataset is collected by experts, with sentence pairs of patients' enquiry and clinicians' responses. The dataset contains 1000 samples and covers five main areas of reasons related to backpain, such as food habits, exercise and social activities. The benchmark of the model is transformer and the embedding technique is GloVe. As some of the state-of-the-art deep learning models are miscalibrated, we propose calibration techniques of label smoothing and tempreture scaling to prevent the model being over confident. Due to the efficiency of the transfer learning techniques, we also apply ULMFiT and Self Distillation in our work. The results show that out proposed methods outperform the baseline model and generate longer and more accurate sentences. //
For sentiment analysis, as we do not have the sufficient dataset of descriptions on the backpain levels, we train the tweet sentiment data first. The dataset contains about 14k samples with classes of positive, negative and neutual. The benchmark for this model is LSTM. As the dataset is highly imbalanced, we propose a new loss function as Focal Loss to tackel this issue. The results show that the accuracy is improved by around 4% with our proposed model.//
In the future, we will work on the recommandation system and Q&A auto generation. 
