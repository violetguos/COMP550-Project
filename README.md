# COMP550-Project

## Intro
For better or for worse, social media has had a significant impact on content and information distribution. 
Since anyone has the ability to post anything at anytime, there comes the cost of an increase in the spread of fake news articles and claims. 
Detecting whether an article is promoting fake news or not is difficult since the claim's goal is often to mislead readers to some false conclusion. 
Therefore, being able to fact check claims by analyzing relevant articles can be beneficial as it would allow systems to promote true and relevant news. 
Ideally, this would reduce public exposure to fake news and deter its spread. 
In this project, we examine this challenge and evaluate how natural language processing (NLP) models can be used for the task of fake news classification.
Our goal is to train a variety of linear, ensemble, and neural network models and use pre-processing techniques that we've seen in class to achieve high classification accuracy.
By training and evaluating models on a news dataset provided by the 2019 online competition `Leaders Prize: Fact or Fake News', we demonstrate several NLP models' effectiveness at classifying false, partly true, and true news. 
We show that our methods can successfully detect fake news but would require more work in true news identification. 

## Results
We train a variety of linear, ensemble, and neural network models to perform multi-class classification on the unbalanced dataset from 2019 Leader's Prize Data Cup. The best performing models in terms of class weighted F1 score is Bi-LSTM, and the best in rarest class F1 score is MLP, achieving 60\% and 17\% respectively. The competition's BERT baseline has 0.511 F1 score.
