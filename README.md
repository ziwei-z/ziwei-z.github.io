## Ziwei Zhao Projects

### [Multi-label Emotion Classification using Movie Subtitles](https://github.com/ziwei-z/w266-project)
#### (Work in Progress)

- Focus: natural language processing - CNN, LSTM, transformers (BERT), Tensorflow
- Teammate: Prathyusha Charagondla

    Multi-label, multi-class emotion classification is an underdeveloped area of NLP. We take the XED data set, which contains 17,530 movie subtitles labeled one or more of Plutchik's eight emotions, and use CNN, LSTM, and BERT models for multi-label classification. In our experiments, we explored the BERT without the CLS token, averaging the vectors from the 'last_hidden_state', and the RoBERTa model. Our RoBERTa model achieves the best micro f1-score of 0.548, slightly surpassing the original paper's 0.536. We explore the differences between the model predictions and the true labels and discuss potential future steps for improving multi-label emotion classification.

### [Does clickbait really lead to more clicks?](https://github.com/ziwei-z/w241-final-project)

- Focus: causal inference, survey design, a/b testing
- Teammates: Hsuanyi Cheng, Patrick Kim, Kayla Wopschall

    We study the effect on click-through rates of applying textual and stylistic image often related to clickbait to headlines of newspaper articles, which can be bought in a digital environment. Here we compare the impacts of changing headlines and images in both a social media platform and survey format to directly measure whether these “clickbait features” do what they're intended to do: entice readers to click on them. When testing articles related to travel during Covid and the drought in the West, our research shows evidence of increased clickthrough rates on the social media platform Facebook when both text and image are altered. The follow up with a survey style approach where we test a travel article and an article about streaming video and movie theater success, suggests there is strong correlation between altering image and text individually, and altering both, in respondents interest in the article (with no apparent effect of article content). However, further work is needed to ensure a sample size large enough to test for a significant treatment effect. 
    
### [Facial keypoints detection](https://github.com/ziwei-z/facial_detection)

- Focus: machine learning - Tensorflow, CNN
- Teammates: Ram Ben-David, Thomas Lurquin, Joe Mirza

Designed and trained convolutional neural networks models that predict label locations ( (x,y) coordinates) of 15 facial features given an image of a face represented in a 96 x 96 array of pixel values. Augmented training data by warping, rotating, and adjusting the contrast level of images using tools like openCV. 
