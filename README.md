# CSCI544 project

## Adversarial Attack Against Fake News Detection NLP Model

#### Jianing Chen, Ruoyu Li, Connie Liang, Mengsha Wen, Di Wu


We use pre-trained model Bertweet and Flair to classify the news, and analyze the attacking success rate and running time of 5 methods for generating adversarial examples.

### Code
 TextAttack.ipynbthe is the code we ran to get experiment results. Since in this project, we put our concentration on analysis, we used the following articles' codes as reference and did minor modificaitons:
 [Flair Framework](https://github.com/flairNLP/flair)
 [TextAttack](https://github.com/QData/TextAttack)

### Raw Data
 True.csv, False.csv and fake_or_real_news.csv are the raw data we use for classification. References are in our report.

### Data
 dataforattacking.csv is the data prepared for attacking.
 
### Data Preparation
 We do data preprocessing such as removing stop words, combining two source datasets, etc. 

### Result
 Results and summarys of our experiment results for those five attacking methods.


