# CSCI544 project

## Adversarial Attack Against Fake News Detection NLP Model

#### Jianing Chen, Ruoyu Li, Connie Liang, Mengsha Wen, Di Wu
Here is the report: [LINK](https://github.com/CarolWen39/544project/blob/main/Report.pdf)

Here is our presentation on youtube: [LINK](https://youtu.be/2Vs-euPTrc0)

<br/>We use pre-trained model Bertweet and Flair to classify the news, and analyze the attacking success rate and running time of 5 methods to generate adversarial examples.

### Code
 TextAttack.ipynb is the code we ran to get experiment results. In this project, since we put our concentration on analysis, we used the following articles' codes as reference:
 <br/>[Flair Framework](https://github.com/flairNLP/flair)
 <br/>[TextAttack](https://github.com/QData/TextAttack)
 <br/>[FakeNewsDetection](https://github.com/nicolaischneider/FakeNewsDetectionVulnerability)

### Raw Data
 True.csv, False.csv and fake_or_real_news.csv are the raw data we use for classification. References are in our report.

### Data
 dataforattacking.csv is the data prepared for attacking.
 
### Data Preparation
 We do data preprocessing such as removing stop words, combining two source datasets, etc. 

### Result
 Results and summarys of our experiment results for those five attacking methods.


