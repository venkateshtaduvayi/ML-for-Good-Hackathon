# ML For Good with Child Mind Institute Data

## Authors:
Anju Jain   
Ali Lotfdar   
Karthika Mylswamy   
Venkatesh Taduvayi   

# Project Overview:

In this project we have done the following usecases  

1. Crislogger: Sentiment analysis and topic modeling with crisis logger data using various methedologies 
2. ProlificAcademy: Finding the Polarity and subjectivity of the positive statements and the correlation between the positive change with the various activites like social media, isolated, video game, outdoor. 

The first use can be found in the notebook: team29_CrisisLogger.ipynb  
The second use case can be found in the notebook: team29_ProlificAcademic.ipynb   

# Usecase 1: Crisis Logger
The crisislogger data had the transcriptions and with that data we have done the sentiment analsysis and topic modeling. 

We have showcased the sentiments like positive, negative and neutral using various NLP model/ algorithm
We also did the world cloud to highligh the most frequesntly used words. 

### Feature used:
transcriptions 

### Methodology:
textblob   
SentiWordNet   
Vader   
Spacy 

# Usecase 2: ProlificAcademy

In this use case we have done the following 

1. showcased the polarity and subjectivity based on the feature specifypositive (free text field)

2. Showcased the postive or negative correlation between the feature positivechange and activities features like social media, isolated, video game, outdoor

3. Analyzed the positive/negative/neutral impact beased on the occupation and worry. 

4. Created a heatmap to show the correlation between the worry and features like 'positivechange','country','infected','sex','education', 'mentalhealth','financedifficulty', 'livingdifficulty', 'foodsecurity'


### Features used:
specifypositive  
positivechange    
priorsocialmedia  
isolated   
priorvideogames   
outdoorsprior  
socialmedia   
isolated  
videogames  
outdoors  
priorvideogames_2  
outdoorsprior_2  

occupation  
priorworry  
worriedyourself  

country   
infected  
sex  
education  
mentalhealth  
financedifficulty  
livingdifficulty   
foodsecurity  

### Methedology:
Data cleaning  
Data Normalization   
Sentiment Analysis  
Correlation Analysis  
Longitudinal analysis  
Linear regression   




# Packages and Models used in both usescases:
sklearn   
nltk   
panda  

wordcloud  
textblob   
spacytextblob   

matplotlib   
seaborn 
plotpy   

Image   
vaderSentiment   
SentiWordNet   
spacy   
en_core_web_sm    
gensim   
pyLDAvis.gensim   
pyLDAvis   

Linear Regression    












