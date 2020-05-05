Intent Recognition using BERT
==============================

Chatbots have become an integral part of businesses to improve customer experience, as they can provide 24/7 support to customers in an (almost) automated manner. However, to accurately respond to customers enquiries and provide them with the relevant resources or next steps, accurate intent recognition is necessary. Intent recognition involves classifying a short text (sentence or two) and have to classify it into one (or multiple) categories. 

In this project, I'll walk you through how I fine-tune the BERT model for text classification.

This dataset has 14484 observations. Each observation consists of user's query (i.e `text` e.g. play the song little robin redbreast) has the `intent` of PlayMusic. There are 7 different intents: 
- SearchCreativeWork (e.g. Find me the I, Robot television show),
- GetWeather (e.g. Is it windy in Boston, MA right now?),
- BookRestaurant (e.g. I want to book a highly rated restaurant for me and my boyfriend tomorrow night),
- PlayMusic (e.g. Play the last track from Beyoncé off Spotify),
- AddToPlaylist (e.g. Add Diamonds to my roadtrip playlist)
- RateBook (e.g. Give 6 stars to Of Mice and Men)
- SearchScreeningEvent (e.g. Check the showtimes for Wonder Woman in Paris)

It is hosted on [GitHub] (https://github.com/snipsco/nlu-benchmark/tree/master/2017-06-custom-intent-engines) and is first presented in [this paper] (https://arxiv.org/abs/1805.10190).

#### Results 
[work-in progress]
Using DistilBERT to embed text and modeling using Log reg gives us higher accuracy than using count vectoriser to generate a document-term matrix and modeling using Log reg. 


Feel free to connect with me (https://www.linkedin.com/in/valerie-lim-yan-hui/) to find out more. I'd love to hear your suggestions or inputs too. Take carea and stay safe! :) ]
