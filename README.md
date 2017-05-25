# UNSPSCPrediction

The four primary levels of the code are: Segment, Family, Class and Commodity.
Each level is coded in two decimal digits, with '00' treated specially to give segments, families and classes their own eight-digit code

There are some inconsistencies in the dataset. For example, some data are missing in the fields like Segment, Family, Class and Commodity

So, Only choice is to go with Material description to predict the UNSPSC final code

Bag of words are created based on the material description given in the dataset. 

After creating bag of words, I allow the Random forest model to train with the given dataset. Once the model is trained, it becomes easy to predict the test set using the predict function of scikit-learn's predict function

Word2Vector is also tested in Client's machine.
