# Bach_Chorales_Style_Music_generator
The training dataset is from Bach’s chorales. This project will try to make models to generate midi songs from the same Bach’s style.    

This project is supervised learning. It will organize the data into sequences that the model can learn from. Each sequence could represent a segment of a chorale and the model will calculate the probabilities of all the possibility notes and select the highest probability note and generate the next segment. So, it is a classification problem.   

The data is in lisp extension which give some challenge to read the data. And it also needs to preproduce the data to sequences pairs. Time-series characteristics also give me challenge. About the final midi generate, because the training data has only single-line melodies, the output midi has only single-line.  (The data set only has the highest note if it’s a chord.) There is no bass chord section, so the effect is limited.  
