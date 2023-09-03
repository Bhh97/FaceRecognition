# Face Recognition using InceptionResNetV1 and PyTorch

This project utilizes the power of the InceptionResNetV1 model for the task of face recognition. Data from the LFW (Labelled Faces in the Wild) and AFD (Asian Face Dataset) have been used for training purposes. The key highlight of this project is its evaluation – where the trained model is tested against classes it hasn't seen during training.

## Datasets
## LFW (Labelled Faces in the Wild): A database of face photographs designed for studying the problem of unconstrained face recognition.
## AFD (Asian Face Dataset): A dataset primarily consisting of faces from Asian demographics.

## Model
InceptionResNetV1: An advanced CNN model renowned for its accuracy in large scale image recognition tasks. For this project, it was fine-tuned to specialize in face recognition.

## Training
The model was trained using a combination of the LFW and AFD datasets to ensure a diverse representation of facial features.

## Testing
Post-training, the model was evaluated using a set of classes it hasn't been trained on. This was done to understand its generalization capabilities and how well it can adapt to unseen data.
