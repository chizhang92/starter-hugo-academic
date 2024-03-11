---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: PhD Student
    company: University of Gothenburg
    company_url: 'https://www.gu.se/en'
    company_logo: gu
    location: Gothenburg, Sweden
    date_start: '2020-02-17'
    date_end: ''
    description: |2-
        Project: the European project SHAPE-IT (Supporting the Interaction of Humans and Automated Vehicles: Preparing for the Environment of Tomorrow), funded by Marie Skłodowska-Curie Actions (MSCA) program.

        Affiliated Ph.D. student of Wallenberg AI, Autonomous Systems and Software Program (WASP-AI) program.

        Studies include:
        
        * Predicting pedestrian trajectories
        * Predicting pedestrian intentions 
        * Predicting and analyzing pedestrian-vehicle interactions
        
  - title: Senior Software R&D Engineer 
    company: Baidu
    company_url: 'https://apollo.auto/'
    company_logo: baidu
    location: Beijing, China
    date_start: '2017-04-01'
    date_end: '2020-02-01'
    description: |2-
        Worked at Technology Department of Autonomous Driving (SAE Level 4), Intelligent Driving Group.
        Mainly dealt with the perception (detection and classification) of LiDAR point clouds data.

        Projects include:
        * Multi-classification of objects from LiDAR data (3D point clouds) using deep learning algorithms.
        * Improvement of segmentation and data-driven detection from LiDAR data.
        * Research and development of filtering the false positive objects using machine learning methods.

  - title: Intern Software R&D Engineer
    company: Alibaba Group
    company_url: 'https://www.alibabagroup.com/en/global/home'
    company_logo: alibabagroup
    location: Hangzhou, China
    date_start: '2016-06-20'
    date_end: '2016-09-01'
    description: |2-
        Worked at Technology Department of Cainiao Logistics and Supply Chain.

        Project: Dealt with warehouse sales forecasting and replenishment optimization algorithm Forecasted sales for daily replenishment by time series method and machine learning methods. 
design:
  columns: '2'
---
