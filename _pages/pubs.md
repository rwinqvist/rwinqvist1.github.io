---
layout: single
title: "Recent publications"
permalink: /publications/
author_profile: true
classes: wide


instruMentor:
  - image_path: instruMentor/instrumentor.png
    alt: "instruMentor"
    title: "instruMentor: An Interactive Robot for Musical Instrument Tutoring"
    text: "Musical instrument education has typically faced challenges in providing students with a cost-efficient and long-term solution for personalised tutoring. To address these challenges, we propose a musical instrument tutor robot for students learning the recorder, called instruMentor. Equipped with robotic hands and a multimodal interface, the robot interacts with users by playing the recorder and demonstrating in real-time the proper handling of the instrument. A pilot study was conducted to investigate the effectiveness of a robot tutor for instrument learning. Experimental results suggest that instruMentor is successful at teaching the recorder and is positively appreciated by users, showing promise for the future coupling of music tutoring and social robots."
    url: "https://link.springer.com/chapter/10.1007/978-3-030-23807-0_25"
    btn_label: "PDF"
    btn_class: "btn--primary"
    tags:
        - Robotics
        - HRI

feature_row5:
  - image_path: assets/images/portfolio/deep_learning-thumb-800.jpg
    portfolio_caption: Photo Credit [Ardon Dertat](https://towardsdatascience.com/applied-deep-learning-part-1-artificial-neural-networks-d7834f67a4f6)
    alt: "deep learning network"
    title: "Deep Learning"
    text: "In this project, I have first developed code for an image classifier built with PyTorch in Jupyter Notebook, then converted it into a command line application. The application allows you to choose one of the pretrained architectures, specify different hyperparameters (learning rate, hidden layers, epochs) and use either GPU or CPU for training. I also implemented saving the checkpoints so that you can continue training if stopped. Image Classifier predicts 102 flower categories. "
    url: "https://github.com/k-bosko/image_classifier"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
        - deep-learning
        - transfer-learning
        - PyTorch


---

{% if site.author.googlescholar %}
  <p style="font-size: 18px;"> You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</p>
{% endif %}

&nbsp;
&nbsp;
&nbsp;

{% include feature_row id="instruMentor" type="left" %}
<a name="instruMentor paper"></a>


&nbsp;
{% include feature_row id="feature_row5" type="left" %}
<a name="Deep-Learning">
