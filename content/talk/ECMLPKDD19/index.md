---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Sub-sentence Level Topic Classification"
event: European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases
event_url: https://ecmlpkdd2019.org/
location: Würzburg
address:
  street:
  city:
  region:
  postcode:
  country:
summary: Conference Talk for my accepted paper *A Semi-discriminative Approach for Sub-sentence Level Topic Classification on a Small Dataset*.
abstract: "This paper aims at identifying sequences of words related to specific product components in online product reviews. A reliable baseline performance for this topic classification problem is given by a Max Entropy classifier which assumes independence over subsequent topics. However, the reviews exhibit an inherent structure on the document level allowing to frame the task as sequence classification problem. Since more flexible models from the class of Conditional Random Fields were not competitive because of the limited amount of training data available, we propose using a Hidden Markov Model instead and decouple the training of transition and emission probabilities. The discriminating power of the Max Entropy approach is used for the latter. Besides outperforming both standalone methods as well as more generic models such as linear-chain Conditional Random Fields, the combined classifier is able to assign topics on subsentence level although labeling in the training data is only available on sentence level.\n

*paper abstract*
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-09-18
#date_end: 2020-11-23T19:59:42+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-11-23T19:59:42+01:00

authors: []
categories: ["talk"]
tags: ["natural language processing", "research"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: slides.pdf

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
