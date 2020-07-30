---
title: "Modeling and Aggregation of Complex Annotations via Annotation Distances"
collection: publications
permalink: /publication/2020-04-complex-annotations
excerpt: '__Alexander Braylan and Matthew Lease__. Modeling annotators and their labels is valuable for ensuring collected data quality. Though many models have been proposed for binary or categorical labels, prior methods do not generalize to complex annotations (e.g., open-ended text, multivariate, or structured responses) without devising new models for each specific task. To obviate the need for task-specific modeling, we propose to model distances between labels, rather than the labels themselves. Our models are largely agnostic to the distance function; we leave it to the requesters to specify an appropriate distance function for their given annotation task. We propose three models of annotation quality, including a Bayesian hierarchical extension of multidimensional scaling which can be trained in an unsupervised or semi-supervised manner. Results show the generality and effectiveness of our models across diverse complex annotation tasks: sequence labeling, translation, syntactic parsing, and ranking.
[
[Slides](https://www.slideshare.net/AlexanderBraylan/modeling-and-aggregation-of-complex-annotations)
|
[Presentation]
(https://www.youtube.com/watch?v=Asa_Bswlvfo)
|
[Code]
(https://github.com/Praznat/annotationmodeling)
]'
venue: 'The Web Conference 2020'
paperurl: 'https://www.ischool.utexas.edu/~ml/papers/braylan_web2020.pdf'
---
Modeling annotators and their labels is valuable for ensuring collected data quality. Though many models have been proposed for binary or categorical labels, prior methods do not generalize to complex annotations (e.g., open-ended text, multivariate, or structured responses) without devising new models for each specific task. To obviate the need for task-specific modeling, we propose to model distances between labels, rather than the labels themselves. Our models are largely agnostic to the distance function; we leave it to the requesters to specify an appropriate distance function for their given annotation task. We propose three models of annotation quality, including a Bayesian hierarchical extension of multidimensional scaling which can be trained in an unsupervised or semi-supervised manner. Results show the generality and effectiveness of our models across diverse complex annotation tasks: sequence labeling, translation, syntactic parsing, and ranking.

[Download paper here](https://www.ischool.utexas.edu/~ml/papers/braylan_web2020.pdf)

BibTeX

@inproceedings{braylan2020modeling,
  title={Modeling and Aggregation of Complex Annotations via Annotation Distances},
  author={Braylan, Alexander and Lease, Matthew},
  booktitle={Proceedings of The Web Conference 2020},
  pages={1807--1818},
  year={2020}
}