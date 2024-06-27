# Babyemotionrecognition
Machine learning project to detect baby emotion through speech


Dataset link:https://www.kaggle.com/datasets/dejolilandry/asvpesdspeech-nonspeech-emotional-utterances

# Evaluation of network


<img width="417" alt="image" src="https://github.com/Noorjahan0905/babyemotionrecognition/assets/105159578/38fd2a7e-e4e2-497e-b9ed-69aa5f353b2d">


The bar graph shows the count of emotions used in a baby emotion recognition project: "happy" (160) is the most frequent, followed by "sad" (130), "angry" (120), "disgust" (70), and "calm" (30), indicating varied representation across emotions.

<img width="887" alt="image" src="https://github.com/Noorjahan0905/babyemotionrecognition/assets/105159578/b6790148-2567-4c70-821d-ee8ba37d541b">


The left graph shows the training loss decreasing steadily while the testing loss fluctuates before decreasing, indicating overfitting initially but improvement later. The right graph shows training accuracy reaching near 100% quickly, while testing accuracy improves gradually, stabilizing around 90% by 50 epochs.

# Working 
<img width="488" alt="image" src="https://github.com/Noorjahan0905/babyemotionrecognition/assets/105159578/b652f602-e807-458d-99b8-e6b509c84eff">

The CNN architecture in the model extracts hierarchical features from the audio data through multiple convolutional and pooling layers, normalizes and regularizes these features, and then classifies them into emotion categories using dense layers.

