---
layout: single
title: "Publications"
permalink: /pubs/
author_profile: true
classes: wide

instruMentor:
  - image_path: assets/gif/gifify.gif
    alt: "instruMentor"
    title: "instruMentor: An Interactive Robot for Musical Instrument Tutoring"
    text: "I developed a Gifify app where a user can upload a video and get it processed into a gif. This is a Flask app deployed to AWS EC2 instance. The user login data is saved into DynamoDB, while the users' uploaded videos and resulting gifs are stored on S3 buckets. The video processing is implemented through a Lambda function (deployed via Docker to ECS)."
    url: "https://link.springer.com/chapter/10.1007/978-3-030-23807-0_25"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags:
        - AWS
        - Lambda
        - S3
        - EC2
        - DynamoDB
        - Flask
        - ECS
        - Docker

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

## Projects in Computer Science

{% include feature_row id="instruMentor" type="left" %}
<a name="Gifify AWS app"></a>
{% include feature_row id="feature_row0-2" type="left" %}
<a name="HWT game"></a>
{% include feature_row id="feature_row0-3" type="left" %}
<a name="GhostKitchen Node.js app"></a>
{% include feature_row id="feature_row0-4" type="left" %}
<a name="Python app"></a>
<a name="NLP Flask app"></a>
{% include feature_row id="feature_row2" type="left" %}
<a name="KD Tree algorithm"></a>
{% include feature_row id="feature_row0-5" type="left" %}

## Projects in Data Science

&nbsp;
<a name="Signal-Processing">
{% include feature_row id="feature_row1-0" type="left" %}
{% include feature_row id="feature_row5" type="left" %}
<a name="Deep-Learning">
{% include feature_row id="feature_row1-1" type="left" %}
<a name="Marketing-Analytics"></a>
{% include feature_row id="feature_row1-2" type="left" %}
<a name="Purchase-Analytics"></a>
{% include feature_row id="feature_row1-3" type="left" %}
<a name="Tableau-Dashboard"></a>
{% include feature_row id="feature_row1-4" type="left" %}
<!-- <a name="Digital-Marketing"></a>
{% include feature_row id="feature_row4" type="left" %} -->
<a name="Recommender-System"></a>
{% include feature_row id="feature_row3" type="left" %}