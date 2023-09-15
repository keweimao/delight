---
title: Information Theory
summary: The definition and measurement of information is fundamental to methods for information retrieval, text mining, and machine learning. 
tags:
- Information Theory
- Information Retrieval
- Machine Learning
- Data and Information
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

What is information? How can we quantify the amount of information? These are fundamental and challenging questions. They are fundamental because a broad spectrum of problems we face are centered on the notion of \textbf{information} and how it can be measured in practical applications. Yet there is hardly any agreement on what it is and how it should be treated. From \textit{Shannon Entropy} to \textit{Landauer's principle} and Wheeler's ``It from Bit,'' there are perspectives in which information can be viewed and measured. 

A better understanding of these questions through the lenses of related theories and discoveries will provide insight into new models for improved information representation, dissemination, and analytics. Rooted in Shannon's entropic framework of information, my research on the Least Information Theory (LIT) and the Discounted LIT of Entropy (DLITE or pronounced \textit{delight}) attempts to address very practical problems in information processing by creating a new theory with several desirable properties. It was a risky research project I initiated as a junior faculty member which, fortunately, has yielded extraordinary fruit on both the theoretical and practical levels. 

Information theory provides the foundation and guiding principles for research in search and analytics. In the formulation of LIT and DLITE as potential quantities of information, we discovered multiple principle properties desirable in information retrieval and text mining tasks. 

For example, classic Inverse Document Frequency (IDF) scoring computes the amount of Kullback-Leibler (KL) divergence in a term (word) as its term weight. It is often assumed that these weights can be added up as a distance metric and can be compared on the same scale when their theoretical characteristics suggest otherwise. The development of DLITE addresses these issues because of its distinctive properties: 


+ DLITE is a \textit{volumetric} and its cube root a \textit{distance metric} that satisfies properties such as triangular inequality. It is fitting to use it in classic scoring functions where the sum of such values (scores) are meaningful. 
+ DLITE is normalized and bounded. As such, it mitigates issues of dominant terms in the scoring/ranking function, e.g. a rare term that renders other query terms useless. 
+ As the DLITE of an ensemble (the entire system) can be computed as the weighted sum of its sub-systems, it offers researchers the capacity to dissect and reconstruct a system in different ways without altering the final scoring.

These properties have enabled the creation of a new IR ranking system with superior performances, which I will elaborate in the next section. 
