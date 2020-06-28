# Introduction
Facial expressions communicate better than words.
In recent years, the technique of facial expression recognition has been vastly explored and this has solved a huge problem in many areas of application. Such as the business places for customer relationship evaluation, on a Police patrol or during investigations, in a psychology session and many more. 
Emotion recognition is very important as facial expressions can easily go unnoticed due to busy schedules or mere neglect. That is why researchers in this area are concerned about building systems that can assist humans to pick on different faces so as to improve good relationships with customers, clients and even colleagues. 

# Approach
- The data was downloaded from one of Kaggle’s FER competitions (https://www.kaggle.com/aspiring1/fer2013-images) as images, and then were converted to csv on the Colab notebook.
- The images were manually cleaned and then reduced to three classes: Happy, Neutral and Sad 
- Transfer learning was used which ran on fast.ai. However, different pretrained models were tried and VGG19_bn turned out best with an accuracy of 76% 
- The model was tested with the Test set along with some real life photos.

