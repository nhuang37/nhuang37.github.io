---
layout: about
title: about
permalink: /
subtitle: Flatiron Research Fellow, Center for Computational Mathematics, Flatiron Institute.

profile:
  align: right
  image: prof_pic.jpeg
  image_circular: true # crops the image to make it circular
  more_info: >


selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Flatiron Research Fellow in the [Center for Computational Mathematics](https://www.simonsfoundation.org/flatiron/center-for-computational-mathematics/) at [Flatiron Institute](https://www.simonsfoundation.org/flatiron/). I am broadly interested in geometric deep learning, theory and algorithms for foundation models, and machine learning for science.

I completed my PhD in 2024 from Johns Hopkins University, where I was fortunate to be co-advised by [Professor Soledad Villar](https://www.ams.jhu.edu/villar/) and [Professor Carey Priebe](https://www.ams.jhu.edu/~priebe/). I was a research intern at [Apple Machine Learning Research](https://machinelearning.apple.com/) in 2023 and 2024.

<h2 style="margin-bottom: 0px;">Selected Publications</h2>

<div class="publications" markdown="1">

### Graph Machine Learning

{% bibliography --group_by none --query @*[topic=graph-learning] %}

### Theory and Algorithms for Foundation Models

{% bibliography --group_by none --query @*[topic=foundations] %}

### Machine Learning for Science

{% bibliography --group_by none --query @*[topic=ml4science] %}

</div>
