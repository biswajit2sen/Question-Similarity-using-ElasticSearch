# Overview
In this project I am trying to score the similarity between Questions based on the text in the Question and Answer asked by the users in stackoverflow. <br />
We have used StackSample: 10% of Stack Overflow Q&A from kaggle. <br />
The similarity between questions are calculated using cosineSimilarity inbuilt in ElasticSearch. <br />
Elasticsearch is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. <br />
Refer their website for more information https://www.elastic.co/what-is/elasticsearch <br /> 
We have used pretrained Universal-sentence-encorder-large model from tfhub to convert our text data to vector/numerical forms. <br />
 
# Data Collection
We get our data from https://www.kaggle.com/stackoverflow/stacksample?select=Questions.csv
# Technology used
![image](https://user-images.githubusercontent.com/63191193/117545654-54172600-b044-11eb-8464-9ebf463bcde2.png)
![image](https://user-images.githubusercontent.com/63191193/117545712-8fb1f000-b044-11eb-8648-e48fe4a9e8bc.png)

![image](https://user-images.githubusercontent.com/63191193/117545698-7ad55c80-b044-11eb-954b-f61dff52a1f9.png)
