---
title: "Distance-based Consensus Modeling for Complex Annotations"
collection: publications
permalink: /publication/2019-11-complex-annotations
excerpt: '__Alexander Braylan and Matthew Lease__. Modeling annotators and their labels is useful for ensuring data quality. Though many models exist for binary or categorical labels, prior methods do not generalize to complex annotation tasks (e.g., open-ended text, multivariate, structured responses) without devising new models for each specific task. To obviate the need for task-specific modeling, we propose to model distances between labels, rather than the labels themselves. Our method, a Bayesian hierarchical extension of multidimensional scaling, is agnostic as to the distance function; we leave it to the annotation task requester to specify an appropriate distance function for their task. Evaluation shows the generality and effectiveness of the model across two complex annotation tasks: multiple sequence labeling and syntactic parsing.
'
venue: 'AnnoNLP @ EMNLP-IJCNLP 2019'
paperurl: 'https://praznat.github.io/label_distance_aggregation__annoNLP.pdf'
---
Modeling annotators and their labels is useful for ensuring data quality. Though many models exist for binary or categorical labels, prior methods do not generalize to complex annotation tasks (e.g., open-ended text, multivariate, structured responses) without devising new models for each specific task. To obviate the need for task-specific modeling, we propose to model distances between labels, rather than the labels themselves. Our method, a Bayesian hierarchical extension of multidimensional scaling, is agnostic as to the distance function; we leave it to the annotation task requester to specify an appropriate distance function for their task. Evaluation shows the generality and effectiveness of the model across two complex annotation tasks: multiple sequence labeling and syntactic parsing.

[Download paper here](https://praznat.github.io/label_distance_aggregation__annoNLP.pdf)

BibTeX

@conference{Braylan-annonlp19,
  author = {Alexander Braylan and Matthew Lease},
  title = {Distance-based Consensus Modeling for Complex Annotations},
  booktitle = {{Workshop on Aggregating and Analysing Crowdsourced Annotations for NLP (AnnoNLP) at the EMNLP-IJCNLP Conference}},
  year = {2019},
  confurl = {http://dali.eecs.qmul.ac.uk/annonlp},
  url = {../papers/braylan-annonlp19.pdf},
  slides = {../papers/alexbraylan_AnnoNLP.pptx},
  source = {https://github.com/Praznat/annotationmodeling}
}