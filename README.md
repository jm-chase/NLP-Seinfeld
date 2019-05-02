# NLP-Seinfeld
Unsupervised Natural Language Processing on Seinfeld Dialogue

# Purpose
To run NLP on Seinfeld dialogue.  I hoped to show if Seinfeld dialogue could be clustered
in some novel way.  Because writers generally give a particular episode a narrative direction, I tried to predict a writer for a particular episode

#Techniques
NLP
  -Doc2Vec
  -Tf-idf
Clustering
  -K-Means
  -Spectral Clustering
  -Affinity Propagation
Supervised Learning
  - Logistic Regression

#Difficulties
In a show 'about nothing', the dialogue was not unique or distinctive enough to produce a good model, either unsupervised or supervised with 
my strategy.  

#Other Strategies
I did not analyze the dialogue by character, mainly because of time, I estimate that predicting who said a certain line would be easier than 
predicting who wrote it given this data.  Firstly, there would be more lines per character than lines per writer, and characters may be more 
distinct from each other in dialogue than writers in dialogue.  I intend this visit this question later. 
