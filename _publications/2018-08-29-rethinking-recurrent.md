---
title: "Rethinking Recurrent Latent Variable Model for Music Composition"
authors: "Eunjeong Stella Koh, Shlomo Dubnov, <strong>Dustin Wright</strong>"
collection: publications
permalink: /publication/2018-08-29-rethinking-recurrent
excerpt: 'We present promising results with symbolic music generation using a variational autoencoder with CNN encoder.'
date: 2018-08-29
venue: 'IEEE 20th International Workshop on Multimedia Signal Processing (MMSP)'
paperurl: 'https://arxiv.org/pdf/1810.03226.pdf'
---
We present a model for capturing musical features and creating novel sequences of music, called the Convolutional-Variational Recurrent Neural Network. To generate sequential data, the model uses an encoder-decoder architecture with latent probabilistic connections to capture the hidden structure of music. Using the sequence-to-sequence model, our generative model can exploit samples from a prior distribution and generate a longer sequence of music. We compare the performance of our proposed model with other types of Neural Networks using the criteria of Information Rate that is implemented by Variable Markov Oracle, a method that allows statistical characterization of musical information dynamics and detection of motifs in a song. Our results suggest that the proposed model has a better statistical resemblance to the musical structure of the training data, which improves the creation of new sequences of music in the style of the original.

[Download paper here](https://arxiv.org/pdf/1810.03226.pdf)

[View code](https://github.com/dwright37/cnn-vrnn-polyphonic-music-generation)

Recommended bibtex: 

```
@inproceedings{koh2018rethinking,
  title={ {Rethinking Recurrent Latent Variable Model for Music Composition} },
  author={Koh, Eunjeong Stella and Dubnov, Shlomo and Wright, Dustin},
  booktitle={2018 IEEE 20th International Workshop on Multimedia Signal Processing (MMSP)},
  pages={1--6},
  year={2018},
  organization={IEEE}
}
```
