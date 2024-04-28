---
title: "Infusing Pub-Sub Storage with Transactions"
authors:
- Liana V. Rodriguez, John Bent, Tim Shaffer, and Raju Rangaswami
# date: "2022-07-01-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Infusing Pub-Sub Storage with Transactions
publication_short: Pub-Sub Storage

abstract: The need to support new features in existing storage systems is an ongoing concern for storage developers. So is the desire to develop next generation storage systems that can adopt newly developed feature improvements with relative ease. Extending storage systems is challenging because of the inherent complexity of their codebases and the need to ensure that the storage state does not become corrupt or inconsistent when enabling new features. In this work, we examine a new storage architecture, FDMI, that uses the well-established publish-subscribe model for extending the feature set of a host storage system using plugins. A central mechanism in FDMI is transactional coupling. With transactional coupling, the subscribed plugin can either create new transactions that execute asynchronously following the successful completion of the precipitating event or can participate in the pending transaction and control whether the precipitating event itself will or will not be committed. We further create a classification of transactional mechanisms as well as possible desired plugin functionality and explore the matrix of these two classifications to create a new model for faster, safer distributed storage development.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Pub-Sub Storage USENIX HotStorage'22 paper
  url: https://dl.acm.org/doi/10.1145/3538643.3539739
url_pdf: https://users.cs.fiu.edu/~raju/WWW/publications/hotstorage2022/paper.pdf
# url_code: https://github.com/sylab/cacheus
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: https://www.hotstorage.org/2022/slides/hotstorage22-paper4-presentation_slides.pdf
# url_source: '#'
# url_video: https://www.youtube.com/watch?v=tRsCs6sAkvM

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Pub-Sub Storage'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}} Proceedings of the 14th ACM Workshop on Hot Topics in Storage and File Systems HotStorage'22 {{% /alert %}}
