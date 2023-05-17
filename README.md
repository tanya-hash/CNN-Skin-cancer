# CNN-Skin-cancer

This is a CNN project for detecting Skin Cancer of 9 types: actinic keratosis', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus', 'pigmented benign keratosis', 'seborrheic keratosis', 'squamous cell carcinoma', 'vascular lesion'

Before data augmentation model was clearly overfitting

Used two techniques: One is horizontal flip and the other is central cropping

Trained the model but ran out of GPU on google colab. I believe validation accuracy would have improved at the end of 30 epochs but data may still be over-fitting.
Different augmentation technique might help
