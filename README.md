Author: Huygens Ravelomanana
# Description
We perform text classification using the name data from [pytorch.org](https://download.pytorch.org/tutorial/data.zip).
The goal is to classify names according to their origins.
+ We load the data and do some text preprocessing first.
+ We use character tokenization and vectorization then build and LSTM model for the classification.
+ We then evaluate the result on (unseen) test data.
+ We also build some utility functions at the end.

