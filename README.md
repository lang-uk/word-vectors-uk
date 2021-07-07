Our main purpose is to train some good word vectors for our product, called [UberText](https://lang.org.ua/uk/corpora/#anchor4). We did that for UberText v1.0, which was collected back in 2006 for the [lexvec, glove and word2vec](https://lang.org.ua/uk/models/#anchor4) on full corpus (tokenized, lowercased, lemmatized, lemmatized lowercased) and its parts (fiction, news).

Later that vectors was evaluated using intrinsic evaluation, described [here](https://github.com/lang-uk/vecs).

Now we are updating the ubertext to the version 2.0. It'll be roughly twice the size of version 1.0, cover more sources and has more perks.

We'd like to update the vectors as well:
- choose models and params
- determine requirements to the texts and preprocessing
- evaluate the results
- include vector generation to our pipeline
- and publish resulting artifacts

For sure it mush include fastText, but we are generally open to any ideas.
