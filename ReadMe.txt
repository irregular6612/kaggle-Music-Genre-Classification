2024 Outta-3rd Competition P3 Notebook
Music Genre Classification


Url : https://www.kaggle.com/competitions/2024-outta-basic-p-2/overview
Dataset : https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
(w/ .csv files, only use orignal music files)

Task-type: sequence classification(NLP)
Model: CNN, DNN

Short Summary:
- Classify the music genre to 10 classes(jazz, blues, rock ...)
- Feature extracting: 1. tempogram, 2. melspectrogram, 3. chromagram
- 1. tempogram: rthymical feature -> use Conv1d
- 2 & 3. Spectral features -> use fully connected layer(linear)

Compare:
- training time: simple DNN requires less time than CNN even if it is a 1-dimensional computation.

Result:
- train_acc: 1.0
- test_acc: 0.83
- rank: 12/42

Key Point:
- lr scheduler
- gradient clipping

#need to find a better way or new idea...
Last edited: 24/09/06