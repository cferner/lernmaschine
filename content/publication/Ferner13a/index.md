---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "ODrM* optimal multirobot path planning in low dimensional search spaces"
authors: ["C. Ferner", "G. Wagner", "H. Choset"]
date: 2013-06-01
doi: "10.1109/ICRA.2013.6631119"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-20T19:13:27+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA"

abstract: "We believe the core of handling the complexity of coordinated multiagent search lies in identifying which subsets of robots can be safely decoupled, and hence planned for in a lower dimensional space. Our work, as well as those of others take that perspective. In our prior work, we introduced an approach called subdimensional expansion for constructing low-dimensional but sufficient search spaces for multirobot path planning, and an implementation for graph search called M*. Subdimensional expansion dynamically increases the dimensionality of the search space in regions featuring significant robot-robot interactions. In this paper, we integrate M* with Meta-Agent Constraint-Based Search (MA-CBS), a planning framework that seeks to couple repeatedly colliding robots allowing for other robots to be planned in low-dimensional search space. M* is also integrated with operator decomposition (OD), an A*-variant performing lazy search of the outneighbors of a given vertex. We show that the combined algorithm demonstrates state of the art performance."

# Summary. An optional shortened abstract.
summary: ""

tags: ["multi-agent systems"]
categories: ["research"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
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
