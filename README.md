# Infant-Cry-Classifier
For In-Depth details talking about each component and technology being used, open the notebook (.ipynb file). 

![Image Alt Text](https://user-images.githubusercontent.com/83641114/275823628-52dc66e5-fbdf-4008-81e7-e389a156792a.png)

[General Overview of the layout]

# Abstract

Infant crying noises analysis is essential for understanding and addressing the needs of babies. This research focuses on comparing the performance of a Convolutional Neural Network (CNN) model and a Transformer model for categorizing infant cries into five reasons: hunger, pain, burping needs, discomfort, and tiredness. The models are evaluated on a labeled dataset comprising 457 cry audio files obtained from the Donate a Cry corpus. Mel-frequency cepstral coefficients (MFCC) are used as features to capture the frequency content of the crying sounds. The Transformer model is developed and compared against the CNN model for classification accuracy. Different augmentation levels are applied to both models for evaluation. The results indicate that the Transformer model exhibits higher accuracy compared to the CNN model across multiple augmentation levels. The highest accuracy is achieved by the Transformer model with 4 augmentations. These findings demonstrate the effectiveness of the Transformer model for accurately categorizing infant cries based on their underlying reasons. This research contributes to the field of infant cry analysis by highlighting the advantages of utilizing the Transformer model over the traditional CNN model.


# Results

Transformer Accuracy : 80.44%

LOSS CURVE :
<img src="https://user-images.githubusercontent.com/83641114/275827896-dc355e91-5637-4795-8acd-55050e50f0af.png" alt="Image Alt Text" width="200" height="200">

![Image Alt Text](https://user-images.githubusercontent.com/83641114/275827896-dc355e91-5637-4795-8acd-55050e50f0af.png)

Confusion Matrix :

![Image Alt Text](https://user-images.githubusercontent.com/83641114/275828389-f10ea9eb-2c71-470f-9dcd-cf7bff783533.png)

Normalised Confusion Matrix :

![Image Alt Text](https://user-images.githubusercontent.com/83641114/275828302-98e04252-20c8-4e67-9cb4-5437b9dadd68.png)

Table comparing the accuracies we reached :

![Image Alt Text](https://user-images.githubusercontent.com/83641114/275829282-28f6a2c8-abd5-47ac-998e-bce84236ecab.png)
