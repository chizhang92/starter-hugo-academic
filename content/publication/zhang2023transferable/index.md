---
title: "Spatial-Temporal-Spectral LSTM: A Transferable Model for Pedestrian Trajectory Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chi Zhang
- Zhongjun Ni
- Christian Berger

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-06-13T00:00:00Z"
doi: "10.1109/tiv.2023.3285804"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Intelligent Vehicles
# publication_short:

abstract: Predicting the trajectories of pedestrians is critical for developing safe advanced driver assistance systems and autonomous driving systems. Most existing models for pedestrian trajectory prediction focused on a single dataset without considering the transferability to other previously unseen datasets. This leads to poor performance on new unseen datasets and hinders leveraging off-the-shelf labeled datasets and models. In this paper, we propose a transferable model, namely the “Spatial-Temporal-Spectral (STS) LSTM” model, that represents the motion pattern of pedestrians with spatial, temporal, and spectral domain information. Quantitative results and visualizations indicate that our proposed spatial-temporal-spectral representation enables the model to learn generic motion patterns and improves the performance on both source and target datasets. We reveal the transferability of three commonly used network structures, including long short-term memory networks (LSTMs), convolutional neural networks (CNNs), and Transformers, and employ the LSTM structure with negative log-likelihood loss in our model since it has the best transferability. The proposed STS LSTM model demonstrates good prediction accuracy when transferring to target datasets without any prior knowledge, and has a faster inference speed compared to the state-of-the-art models. Our work addresses the gap in learning knowledge from source datasets and transferring it to target datasets in the field of pedestrian trajectory prediction, and enables the reuse of publicly available off-the-shelf datasets.
# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/tiv.2023.3285804'
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
