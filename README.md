## Recent Projects

### [Multi-label Emotion Classification using Movie Subtitles](https://github.com/ziwei-z/w266-project)

- Focus: natural language processing - CNN, LSTM, transformers (BERT & RoBERTa), Tensorflow, Keras
- Teammate: Prathyusha Charagondla

Using the XED data set, which 17,530 movie subtitles labeled one or more of Plutchik's eight emotions, we designed CNN, LSTM, and BERT models for multi-label classification. In our experiments, we explored using BERT without the CLS token, instead averaging the vectors from the 'last_hidden_state'. Our RoBERTa model achieves the best micro f1-score of 0.548, surpassing the original paper's 0.536. We explored the differences between the model predictions and the true labels and discuss potential future steps for improving multi-label emotion classification.

### [Does clickbait really lead to more clicks?](https://github.com/ziwei-z/w241-final-project)

- Focus: experiments, causal inference, survey design, a/b testing
- Teammates: Hsuanyi Cheng, Patrick Kim, Kayla Wopschall

We collected data and used regression analysis to study the effect of "clickbait" imagery and headline on news article clickthrough rates. We compared the impacts of changing headlines and images in both on Facebook and by designing a survey to directly measure the effects of these “clickbait features”. We tested articles related to travel during Covid and the drought in the West, which show evidence of increased clickthrough rates on Facebook when both text and image are altered. The survey tests a travel article and an article about streaming video and movie theater success, and results suggest a strong correlation between altering image and text individually, and altering both, in respondents interest in the article. We also tested for hetereogenous treatment effects, which showed people over 45 to be more likely to click through to a clickbait article in the Facebook experiment. 
    
### [Facial keypoints detection](https://github.com/ziwei-z/facial_detection)

- Focus: machine learning - Tensorflow, CNN
- Teammates: Ram Ben-David, Thomas Lurquin, Joe Mirza

We designed and trained convolutional neural networks models that predict label locations ( (x,y) coordinates) of 15 facial features, given an image of a face represented in a 96 x 96 array of pixel values. Augmented training data by warping, rotating, and adjusting the contrast level of images using tools like openCV.
