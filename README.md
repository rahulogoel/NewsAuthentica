# NewsAuthentica

>Checks the authenticity of news articles using Machine Learning and Natural Language Processing (NLP).

This project is the implementation of a research paper by [Jumana Jouhar et al.](https://www.sciencedirect.com/science/article/pii/S1877050924006252) with a little tweaking.

## Dataset

It is trained on data of around 45,000 news articles with a mix of real and fake news articles. The dataset is provided by the [University of Victoria](https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/).

## Result

Tested various machine learning models like :
- Decision Tree
- Random Forest
- Gradient Boosting
- Passive Aggressive Classifier
-  XGBoost
-  Logistic Regression
  
Got the best result with `XGBoost` with over 99% accuracy along with different metrics.

In the end, you can also try giving input news articles and checking whether the news is real or fake. You can refer to [politifact.com](https://www.politifact.com/) which will give you real and fake news articles.
