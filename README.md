# Text-Analysis
Text Analysis of Novel "Great Expectations" by Charles Drawin
# Installing Following Packages
%pip install nltk
%pip install wordcloud
%pip install gensim

# Import 15 Pacakges as follows
import nltk
from nltk import word_tokenize
from nltk.corpus import stopwords
from nltk.sentiment.vader import SentimentIntensityAnalyzer
from nltk .stem import WordNetLemmatizer
from gensim.corpora import Dictionary
from gensim.models import ldamodel
from gensim.models.coherencemodel import CoherenceModel
from wordcloud import WordCloud
import pandas as pd
from PIL import Image
import numpy as np
import random
import re
import matplotlib.pyplot as plt
%matplotlib inline
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('vader_lexicon')
nltk.download('wordnet')
