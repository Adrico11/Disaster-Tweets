## Disaster Tweets Classification (Kaggle competition)

### Goal of the project
Build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t
The scores mentioned below are thos obtained on a submission test sample and correspond to the f1-scores of my predictions

Here is the link to the competition : https://www.kaggle.com/c/nlp-getting-started/overview

### Contents of the files in this repo
The three jupyter notebooks in this repo each contain a different approach to solving this problem, with increasing complexity :
- Kaggle ML.ipynb : machine learning models (Logistic regression, Naive Bayes, K-Nearest Neighbours, Random forest, Gradient Boosting...) benchmarked (Best : 0.79313 with a Naive Bayes model) 
- Kaggle DL.ipynb : implementation of deep neural networks for NLP tasks with LSTMs and RNNs (Best : 0.79987 with a Bidirectionnal RNN model)
- Kaggle BERT.ipynb : use of a pre-trained transformer for classification with BERT (Best : 0.83450 => **top 10% of submissions !!**)

#### Following are screenshots of training and validation metrics (F1 score and loss) for 2 epochs of training (x-axis : batch number) made with Tensorboard :
<img width="352" alt="image" src="https://user-images.githubusercontent.com/59745916/153378716-3d12dfe1-2d60-4daf-9d20-6cc445c518fb.png">
<img width="355" alt="image" src="https://user-images.githubusercontent.com/59745916/153378876-3cae6b52-a24e-41fa-b100-37a244a0b442.png">
<img width="350" alt="image" src="https://user-images.githubusercontent.com/59745916/153378998-6192333d-1a66-42c5-b313-0ef9675f1f27.png">
<img width="349" alt="image" src="https://user-images.githubusercontent.com/59745916/153379101-1c0c5736-fbcd-4f48-8216-8e1196c1ba30.png">
