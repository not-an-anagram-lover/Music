# Music
Music mood detector:- Using labeled playlists data from spotify. Music mood detector detects happy or sad mood of a song combining both audio and lyrical features.
This project was a result of collaborative effort of not-an-anagram-lover and pratimanisha


Creating a dataset of 1765 songs labeled with relevant song features, and lyrics, as extracted from Genius.com.Firstly ensemble voting technique was used to combine three model for lyric based mood prediction. Later, Naïve Bayes model was opted since Naïve Bayes classifiers are known to perform well given small sample sizes and are successfully being used for similar binary text classification tasks such as e-mail spam detection. Also in comparison to other models applied Multinomial Naïve Bayes performs better with respect to our requirements. Applying Support Vector Machine with linear kernel on audio features we get mood predictions with respect to audio.Integrating these two predictions was done using probability of predicted classes from these models and taking geometric mean. A threshold was set using try and error method to predict final mood which yielded greater increase in accuracy of the model.
