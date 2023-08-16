## Topics Extraction from Conference Speeches  (Unsupervised Learning):

### About this project:

The abundance of conferences and the vast amount of information generated during these events have createx a significant challenge: the information overloadleading to difficulties in extracting the key topics and insights. So, the objective of this project is to propose a way to extract key insights and topics efficiently from a group of conference speeches. I implemented a unsupervised learning model using the algorithm K-means, created wordcloud visualizations to represent the most frequent and relevant words in each cluster and finally, I utilized a topic modeling algorithm called Latent Dirichlet Allocation (LDA) to discover the underlying topics within the clusters. 

### Dataset


The dataset was sourced from Mendeley Data Repository comprising speech transcripts delivered by prominent individuals such as Barack Obama, Bernie Sanders, Bill Gates, Boris Johnson, Donald Trump, Joe Biden, Martin Luther King, and Nelson Mandela. In total, the transcripts collected span approximately 30 hours of recorded talks, originally obtained from various websites. The dataset comprises a total of 40 text files, each person contributed with five speeches.

Retrieved on July 20th 2023 from [Mendeley Data Repository](https://data.mendeley.com/datasets/s4dtmfmzxw/1)


### Tech:

- Python 3
- scikit-learn:
  - K-Means 
  - sklearn.metrics
- pandas
- matplotlib
- seaborn
- nltk (Natural Language Toolkit)
- gensim
- TextBlob
- PorterStemmer
- pyLDAvis


### Author
[Wendy Navarrete](http://wendynavarrete.com)
