---
title: "Reward Augmented Maximum Likelihood to Improve Neural Machine Translation Training"
collection: publications
permalink: /publications/msc-thesis
authors:
  - Proyag Pal
date: 2017-08
paperurl: '/files/raml_thesis.pdf'
abstract: Neural Machine Translation in its current form suffers from some problems such as loss-evaluation mismatch and exposure bias. Reward Augmented Maximum Likehood is a technique that directly incorporates the task evaluation metrics such as BLEU score into the traditional maximum likelihood training framework. This is done by augmenting the training output targets with outputs that are sampled proportional to their exponentiated scaled rewards, on which cross-entropy is optimised. This is a more computationally efficient method than reinforcement learning-based methods and can be trained effectively from a cold start without bootstrapping with a cross-entropy trained model. This project implements Reward Augmented Maximum Likelihood in the Nematus neural machine translation framework, and observes significant improvements in BLEU score over a model trained to optimise perplexity.
---
