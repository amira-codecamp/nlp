Scientific documents classification (ETDs & articles) using naive bayes - languages including english, french, arabic

# FoS classification system
https://en.wikipedia.org/wiki/Fields_of_Science_and_Technology

# Model architecture
![Model architecture](architecture.png)

# 
import joblib
model = joblib.load("FoS_classifier.pkl") # load 
label = model.predict([text]) # predict 
