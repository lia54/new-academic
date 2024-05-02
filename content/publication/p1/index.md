---
title: "Learning Cache Replacement with Cacheus"
authors:
- Liana V. Rodriguez, Farzana Yusuf, Steven Lyons, Eysler Paz, Raju Rangaswami, Jason Liu, Ming Zhao and Giri Narasimhan
# date: "2021-07-01-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Learning Cache Replacement with Cacheus
publication_short: Cacheus

abstract: Recent advances in machine learning open up new and attractive approaches for solving classic problems in computing systems. For storage systems, cache replacement is one such problem because of its enormous impact on performance. We classify workloads as a composition of four workload primitive types—LFU-friendly, LRU-friendly, scan, and churn. We then design and evaluate CACHEUS, a new class of fully adaptive, machine-learned caching algorithms that utilize a combination of experts designed to address these workload primitive types. The experts used by CACHEUS include the state-of-the-art ARC, LIRS and LFU, and two new ones – SR-LRU, a scan-resistant version of LRU, and CR-LFU, a churn-resistant version of LFU. We evaluate CACHEUS using 17766 simulation experiments on a collection of 329 workloads run against 6 different cache configurations. Paired t-test analysis demonstrates that CACHEUS using the newly proposed lightweight experts, SR-LRU and CR-LFU, is the most consistently performing caching algorithm across a range of workloads and cache sizes. Furthermore, CACHEUS enables augmenting state-of-the-art algorithms (e.g., LIRS, ARC) by combining it with a complementary cache replacement algorithm (e.g., LFU) to better handle a wider variety of workload primitive types.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Cacheus USENIX FAST'21 paper
  url: https://www.usenix.org/conference/fast21/presentation/rodriguez
url_pdf: https://www.usenix.org/system/files/fast21-rodriguez.pdf
url_code: https://github.com/sylab/cacheus
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: https://www.usenix.org/sites/default/files/conference/protected-files/fast21_slides_yusuf.pdf
# url_source: '#'
url_video: https://www.youtube.com/watch?v=tRsCs6sAkvM

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Cacheus components'
  focal_point: ""
  preview_only: false
  image_position: center
  image_size: cover
  text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]

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

{{% alert note %}} USENIX Conference on File and Storage Technologies FAST'21 {{% /alert %}}
