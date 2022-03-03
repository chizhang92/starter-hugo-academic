---
title: "Social-IWSTCNN: A Social Interaction-Weighted Spatio- Temporal Convolutional Neural Network for Pedestrian Trajectory Prediction in Urban Traffic Scenarios"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chi Zhang
- Christian Berger
- Marco Dozza

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-07-11T00:00:00Z"
doi: "10.1109/IV48863.2021.9575958"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In proceedings of the 2021 IEEE Intelligent Vehicles Symposium (IV)
publication_short: In IEEE IV 2021

abstract: Pedestrian trajectory prediction in urban scenarios is essential for automated driving. This task is challenging because the behavior of pedestrians is influenced by both their own history paths and the interactions with others. Previous research modeled these interactions with pooling mechanisms or aggregating with hand-crafted attention weights. In this paper, we present the Social Interaction-Weighted Spatio- Temporal Convolutional Neural Network (Social-IWSTCNN), which includes both the spatial and the temporal features. We propose a novel design, namely the Social Interaction Extractor, to learn the spatial and social interaction features of pedestrians. Most previous works used ETH and UCY datasets which include five scenes but do not cover urban traffic scenarios extensively for training and evaluation. In this paper, we use the recently released large-scale Waymo Open Dataset in urban traffic scenarios, which includes 374 urban training scenes and 76 urban testing scenes to analyze the performance of our proposed algorithm in comparison to the state-of-the-art (SOTA) models. The results show that our algorithm outperforms SOTA algorithms such as Social-LSTM, Social-GAN, and Social-STGCNN on both Average Displacement Error (ADE) and Final Displacement Error (FDE). Furthermore, our Social- IWSTCNN is 54.8 times faster in data pre-processing speed, and 4.7 times faster in total test speed than the current best SOTA algorithm Social-STGCNN.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2105.12436.pdf'
url_code: ''
url_dataset: 'https://waymo.com/intl/en_us/open/'
url_poster: 'https://www.shape-it.eu/wp-content/uploads/2021/09/ESR3_Chi_Zhang_AUTOUI_Poster-1.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
