# Dialect-identification
Model for discriminating between the Moldavian (MD) and the Romanian (RO) dialects.

Participants have to train a model on tweets. Therefore, participants have to build a model for a in-genre binary classification by dialect task, in which a classification model is required to discriminate between the Moldavian (label 0) and the Romanian (label 1) dialects.

The training data is composed of 7757 samples. The validation set is composed of 2656 samples. All samples are preprocessed in order to replace named entities with a special tag: $NE$.
