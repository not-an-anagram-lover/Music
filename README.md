# Music
Music mood detector:- Using labeled playlists data from spotify. Music mood detector detects happy or sad mood of a song combining both audio and lyrical features.

Creating a dataset of 1765 songs labeled with relevant song features, and lyrics, as extracted from Genius.com.Firstly ensemble voting technique was used to combine three model for lyric based mood prediction. Later, Naïve Bayes model was opted since Naïve Bayes classifiers are known to perform well given small sample sizes and are successfully being used for similar binary text classification tasks such as e-mail spam detection. Also in comparison to other models applied Multinomial Naïve Bayes performs better with respect to our requirements. Applying Support Vector Machine with linear kernel on audio features we get mood predictions with respect to audio.Integrating these two predictions was done using probability of predicted classes from these models and taking geometric mean. A threshold was set using try and error method to predict final mood which yielded greater increase in accuracy of the model.

### About Collaborators:

#### <Name: Kshitija Saxena>                                  <Name: Pratima Nisha>
#### <Email: saxenakshitija@gmail.com>                        <Email: pratima.nisha8@gmail.com>
#### <LinkedIn: https://github.com/not-an-anagram-lover>      <LinkedIn: https://www.linkedin.com/in/pratima-nisha-9a10ba170>

|   |  |  |
| ------------- | ------------- | ------------- |
| Name  | Kshitija Saxena  | Pratima Nisha |
| Email | saxenakshitija@gmail.com | pratima.nisha8@gmail.com |
| LinkedIn | https://github.com/not-an-anagram-lover | https://www.linkedin.com/in/pratima-nisha-9a10ba170 |
