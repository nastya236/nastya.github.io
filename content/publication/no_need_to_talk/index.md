---
title: "No Need to Talk: Asynchronous Mixture of Language Models"

authors:
- admin
- Angelos Katharopoulos
- David Grangier
- Ronan Collobert
date: "2024-09-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

# (publication_types: ["1"])

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We introduce SmallTalk LM, an innovative method for training a mixture of language models in an almost asynchronous manner. Each model of the mixture specializes in distinct parts of the data distribution, without the need of high-bandwidth communication between the nodes training each model. At inference, a lightweight router directs a given sequence to a single expert, according to a short prefix. This inference scheme naturally uses a fraction of the parameters from the overall mixture model. Our experiments on language modeling demonstrate that SmallTalk LM achieves significantly lower perplexity than dense model baselines for the same total training FLOPs and an almost identical inference cost. Finally, in our downstream evaluations we outperform the dense baseline on 75% of the tasks.
# Summary. An optional shortened abstract.

links:
- name: Custom Link
  url: https://arxiv.org/abs/2410.03529

url_pdf: https://arxiv.org/pdf/2410.03529
# url_video: https://youtu.be/7h3jwTTfXUY

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
