# Deep Learning Module

This repository contains Deep Learning theory notebooks and hands-on exercises part of the CEI (Centro de Estudios de Investigación) Master's (AI module). 

## Structure

```
dl/
├── theory/                         # Conceptual & guided notebooks
│   ├── nlp/                        # Natural Language Processing
│   │   ├── 1_NLP.ipynb                                 # Unit 1: Text preprocessing (tokenization, stopwords, stemming, lemmatization)
│   │   ├── 1_2_NLP_ElQuijote.ipynb                     # Unit 1: Applied NLP on "El Quijote"
│   │   ├── 1_3_NLP_Biblia.ipynb                        # Unit 1: Applied NLP on the Bible
│   │   ├── NLP_Clase2_Representacion_por_frecuencias.ipynb  # Unit 2: Frequency representations (regex, BoW, TF-IDF)
│   │   └── NLP__Frequency_BoW_TF_IDF.ipynb             # Unit 2: BoW & TF-IDF exercises
│   ├── computer_vision/            # Computer Vision (classical)
│   │   ├── S1_CV_preprocessing.ipynb                   # Image loading, color spaces, histograms, filters, edges
│   │   ├── S2_CV_threshold_otsu.ipynb                  # Thresholding, Otsu method, morphological cleanup
│   │   ├── S3_CV_haar_detection.ipynb                  # Object detection with Haar Cascades (face detection)
│   │   └── S5_1_CV_worksheet_análisis_de_blobs.ipynb   # Blob analysis (DoH, morphological operators)
│   ├── deep_learning/              # DL Fundamentals
│   │   ├── deep_learning_1.ipynb                       # Breast Cancer classification (ML baseline)
│   │   └── lab1_ml_to_dl_breast_cancer_keras_viz.ipynb # ML-to-DL bridge (LogReg = single neuron)
│   └── gans/                       # Generative Adversarial Networks
│       └── dcgan.ipynb                                 # DCGAN on MNIST (TensorFlow tutorial)
│
├── exercises/                      # Hands-on labs & assignments
│   ├── nlp/                        # NLP exercises
│   │   ├── Unit3_Exercises_Word_Embeddings.ipynb       # Unit 3: Word embedding similarity, PCA, t-SNE, analogies
│   │   ├── Unit3_Exercises_Gensim_HandsOn_Examples.ipynb # Unit 3: Gensim Word2Vec/Doc2Vec hands-on
│   │   ├── LAB1_Doc2Vec_Music_1950_2019.ipynb          # Lab: Word2Vec & Doc2Vec on song lyrics
│   │   └── LAB2_Songs_analysis_1950_2019.ipynb         # Lab: Genre profiling & temporal trends in music
│   ├── computer_vision/            # CV exercises
│   │   ├── S4_Excercise_CV.ipynb                       # Integrative: photo restoration + face detection
│   │   ├── S5_4_Exercise_Car_Counter.ipynb             # Blob-based car counter from video frames
│   │   └── S6_Exercise_CV_OCR.ipynb                    # OCR pipeline with EasyOCR
│   ├── deep_learning/              # DL exercises
│   │   ├── diamonds_prices_exercise.ipynb              # Regression/classification on diamonds dataset
│   │   └── signs_cnn_exercise.ipynb                    # CNN sign-language classifier (Keras)
│   ├── autoencoders/               # Autoencoder exercises
│   │   ├── autoencoder-Keras_clasif_Fashion-MNIST with RF.py   # Stacked AE (Keras) + Random Forest
│   │   └── autoencoder-Pytorch_clasif_MNIST-RandomForest.py    # Stacked AE (PyTorch) + Random Forest
│   └── mlops/                      # Experiment tracking
│       └── wandb_iris_sklearn_mvp.ipynb                # W&B integration with sklearn
│
├── datasets/                       # Data files (.csv, .h5)
├── images/                         # Static images referenced by notebooks
├── summary.ipynb                   # Quick-reference cheat sheet of key concepts
├── requirements.txt
└── readme.md
```

## Setup

1. Create and activate a virtual environment:
   - `python3 -m venv .venv`
   - `source .venv/bin/activate`

2. Install dependencies:
   - `pip install -r requirements.txt`

3. Launch Jupyter:
   - `jupyter notebook`

4. Run notebooks from their folder locations.

## Notes

- Dataset paths in some notebooks may reference `../datasets/` — adjust relative paths if needed after reorganization.
- Notebook content and outputs were preserved; only naming/organization changes were applied.
