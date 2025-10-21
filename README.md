Implementing novel KNN-models from ["Effective k‑nearest neighbor models for data
classification enhancement"](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-025-01137-2).

This repository contains a PRKNNClassifier python class, which implements a sci-kit learn API complient implentation of the proximal ratio (PR) KNN models described in the paper above. The PRKNNClassifier can be found in test_class.py.

In review.ipynb, I discuss the motivation for implementing this class, describe how the models work, and try to replicate some of the results the creators of this model obtained from experiment 1 of their paper. I also discuss some critiques I have for how the paper details the implementation of the PRKNN model.

Implementing the model presented some technical challenges, also discussed in review.ipynb

demo.ipynb contains a demonstration of the PRKNNClassifier.

This was an interesting project, and my first attempt to implement a machine learning model. With KNN models, optimization is key; I would love to further explore this topic in the feature, maybe by implementing a KNN in C.