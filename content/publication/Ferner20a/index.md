---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Semi-discriminative Approach for Sub-sentence Level Topic Classification on a Small Dataset"
authors: ["C. Ferner", "S. Wegenkittl"]
date: 2020-02-01
doi: "https://doi.org/10.1007/978-3-030-46147-8_42"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-20T17:31:33+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases"
publication_short: "ECML-PKDD"

abstract: "This paper aims at identifying sequences of words related to specific product components in online product reviews. A reliable baseline performance for this topic classification problem is given by a Max Entropy classifier which assumes independence over subsequent topics. However, the reviews exhibit an inherent structure on the document level allowing to frame the task as sequence classification problem. Since more flexible models from the class of Conditional Random Fields were not competitive because of the limited amount of training data available, we propose using a Hidden Markov Model instead and decouple the training of transition and emission probabilities. The discriminating power of the Max Entropy approach is used for the latter. Besides outperforming both standalone methods as well as more generic models such as linear-chain Conditional Random Fields, the combined classifier is able to assign topics on subsentence level although labeling in the training data is only available on sentence level"

# Summary. An optional shortened abstract.
summary: "We combine a Maximum Entropy classifier with a Hidden Markov Model for exploiting the inherent document structure for topic classification."

tags: ["natural language processing", "small data", "hidden markov model", "topic classification"]
categories: ["natural language processing", "research"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Twitter
#   url: https://doi.org/10.1007/978-3-030-46147-8_42
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ecmlpkdd2019.org/downloads/paper/566.pdf
url_code:
url_dataset:
url_poster: "poster.pdf"
url_project:
url_slides: "presentation.pdf"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
