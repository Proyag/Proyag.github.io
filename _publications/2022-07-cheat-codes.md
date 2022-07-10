---
title: "Cheat Codes to Quantify Missing Source Information in Neural Machine Translation"
collection: publications
permalink: /publications/cheat-codes
authors:
  - Proyag Pal
  - Kenneth Heafield
date: 2022-07-11
venue: "<a href ='https://2022.naacl.org'>NAACL</a>"
paperurl: '/files/papers/cheat-codes.pdf'
poster: '/files/posters/cheat_codes_poster.pdf'
aclanthology: '2022.naacl-main.177'
bibtex: '2022.naacl-main.177.bib'
abstract: This paper describes a method to quantify the amount of information <i>H(t|s)</i> added by the target sentence <i>t</i> that is not present in the source <i>s</i> in a neural machine translation system. We do this by providing the model the target sentence in a highly compressed form (a "cheat code"), and exploring the effect of the size of the cheat code. We find that the model is able to capture extra information from just a single float representation of the target and nearly reproduces the target with two 32-bit floats per target token.
---
