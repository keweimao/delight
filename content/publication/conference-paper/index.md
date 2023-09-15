---
title: "Alternatives to Classic BM25-IDF based on a New Information Theoretical Framework"
authors:
- admin
date: "2022-12-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Big Data 2022*
publication_short: In *Big Data'22*

abstract: The IDF (Inverse Document Frequency) term weighting method is a classic treatment of a term's significance in information retrieval and text analytics. IDF can be derived from the information-theoretic KL Divergence and has given rise to competitive methods such as TF*IDF and Okapi BM25, which is the default scoring function of ElasticSearch. We developed a new information metric called {\dlite} and derived from it an alternative to IDF, namely {\idl}, for term weighting and scoring in ranked information retrieval. In a series of experiments we conducted on multiple benchmark TREC collections, {\idl} methods consistently outperformed BM25, a very competitive baseline, for ad hoc retrieval. We outline the theoretical properties of {\dlite} that support the effectiveness of {\idl}. As a general information measure, we expect {\dlite} to be applicable in many other areas of big-data analytics where further research will be valuable. 

# Summary. An optional shortened abstract.
summary: DLITE theory and its derived methods for term weighting outperformed classic TF*IDF and BM25 for information retrieval. 

tags:
- Big Data
- Osaka, Japan
featured: true

links:
#- name: Custom Link
#  url: http://example.org
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

