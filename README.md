# Rice-Leaf-Disease-Detection

Dataset: https://www.kaggle.com/datasets/tedisetiady/leaf-rice-disease-indonesia

Includes:
Preprocessing of the images
architectures
multi and single prediction

Classes/types of Rice Leaf Diseases:
- Blast
- Blight
- Tungro

Machine Learning project that detects if any of the Rice leaf images
are infested with one of the three types of diseases available in the dataset.

What this study lacks is the presence of normal rice leaf without any of the diseases.

Notebooks:
* CNN-BILSTM-ATTENTION++.ipynb - initial ntbk we ended up with.
* CNN-BILSTM-ATTENTION-V2++(WITH AND WITHOUT ATTENTION) - the main ntbk.
* Prediction - separate ntbk for running existing models that has been outputted 
* by "CNN-BILSTM-ATTENTION-V2++(WITH AND WITHOUT ATTENTION)" for single image predictions.
* DATA_PREPARATION - Notebook for processing images before using it in the 
* "CNN-BILSTM-ATTENTION-V2++(WITH AND WITHOUT ATTENTION)" notebooks.

PDFs are just the best outputs of our models, the models are not in the model_checkpoint folders
anymore due to size limitations implemented by Github


