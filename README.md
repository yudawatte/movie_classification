# movie_classification
IMPD movie classification with transfer learning

Dataset was obtained from tensorflow_datasets.

Here I am using tensorflow_hub pre-trained model "gnews-swivel-20dim" for IMPD movie review classification.
It is a Google trained network on GNEWS data and which able to convert raw text into vectors.

Model tend to get overfit arround 30 epochs. Used early stopping to avoid overfitting. 
Final validation accuracy 87%.
