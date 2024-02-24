---
title: "SuperAnimal pretrained pose estimation models for behavioral analysis"
authors:
- Shaokai Ye
- admin
- Maxime Vidal
- Steffen Schneider
- Jessy Lauer
- Tian Qiu
- Alexander Mathis
- Mackenzie Weygandt Mathis
date: "2023-19-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

# (publication_types: ["0"])

# Publication name and optional abbreviated publication name.
publication: "Nature Communication"
publication_short: ""
abstract: Quantification of behavior is critical in applications ranging from neuroscience, veterinary medicine and animal con- servation efforts. A common key step for behavioral analysis is first extracting relevant keypoints on animals, known as pose estimation. However, reliable inference of poses currently requires domain knowledge and manual labeling effort to build supervised models. We present a series of technical innovations that enable a new method, collectively called Su- perAnimal, to develop unified foundation models that can be used on over 45 species, without additional human labels. Concretely, we introduce a method to unify the keypoint space across differently labeled datasets (via our generalized data converter) and for training these diverse datasets in a manner such that they don’t catastrophically forget keypoints given the unbalanced inputs (via our keypoint gradient masking and memory replay approaches). These models show excellent performance across six pose benchmarks. Then, to ensure maximal usability for end-users, we demonstrate how to fine-tune the models on differently labeled data and provide tooling for unsupervised video adaptation to boost performance and decrease jitter across frames. If the models are fine-tuned, we show SuperAnimal models are 10-100× more data efficient than prior transfer-learning-based approaches. We illustrate the utility of our models in behavioral classification in mice and gait analysis in horses. Collectively, this presents a data-efficient solution for animal pose estimation.
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
links:
- name: Custom Link
  url: https://arxiv.org/abs/2203.07436

url_pdf: https://arxiv.org/abs/2203.07436

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
