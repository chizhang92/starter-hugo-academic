---
title: "Learning the Pedestrian-Vehicle Interaction for Pedestrian Trajectory Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chi Zhang
- Christian Berger

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-08T00:00:00Z"
doi: "10.1109/ICCAR55106.2022.9782673"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2022 the 8th International Conference on Control, Automation and Robotics (ICCAR)
publication_short: In IEEE ICCAR 2022

abstract: In this paper, we study the interaction between pedestrians and vehicles and propose a novel neural network structure called the Pedestrian-Vehicle Interaction (PVI) extractor for learning the pedestrian-vehicle interaction. We implement the proposed PVI extractor on both sequential approaches (long short-term memory (LSTM) models) and non-sequential approaches (convolutional models). We use the Waymo Open Dataset that contains real-world urban traffic scenes with both pedestrian and vehicle annotations. For the LSTM-based models, our proposed model is compared with Social-LSTM and Social-GAN, and using our proposed PVI extractor reduces the average displacement error (ADE) and the final displacement error (FDE) by 7.46% and 5.24%, respectively. For the convolutional-based models, our proposed model is compared with Social-STGCNN and Social-IWSTCNN, and using our proposed PVI extractor reduces the ADE and FDE by 2.10% and 1.27%, respectively. The results show that the pedestrian-vehicle interaction influences pedestrian behavior, and the models using the proposed PVI extractor can capture the interaction between pedestrians and vehicles, and thereby outperform the compared methods.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/ICCAR55106.2022.9782673'
url_code: ''
url_dataset: 'https://waymo.com/intl/en_us/open/'
url_poster: ''
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
