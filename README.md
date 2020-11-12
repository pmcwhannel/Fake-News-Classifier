# Fake-News-Classifier
Fake news classification for a Kaggle data competition.

The link to the competition can be found here: https://www.kaggle.com/c/datachallenge2

Test Accuracy: 99.988%

**Description of Model:**

I used a transfer learning technique, in which I took the "bert_base_cased" and fine tuned it through the CLS output layer (768 dim) with dropout followed by a linear transformation and then a cross entropy loss. I tried adding more complexity though it didn't lead to increased performance therefore I stuck with the aforementioned additions.
