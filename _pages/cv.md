---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Engineering, University of Maryland - College Park, Expected May 2021

Work Experience
======
* **MUKH Technologies: Research Intern (August 2020 - Present)**
  * Leading research on improving facial recognition performance across domain shift with large scale data
  * Building facial recognition pipelines for multi-spectral data streams

* **Carnegie Mellon University: Robotics Institute Research Intern (April 2020 - December 2020)**
  * Leading research on 3D open world detection and tracking for autonomous driving
  
* **University of Maryland: UMIACS Research Intern (May 2018 - Jun 2020)**
  * Conducted research in traffic analytics for unsupervised anomaly detection and discriminative representation learning for vehicle re-identification
  * Led research in defending against clean-label adversarial poisoning attacks

* **Bank of America: Conversational Commerce Technology Intern (May 2019 - Aug 2019)**
  * Developed deep learning pipeline to validate quality of utterance-intent pairs in chatbot conversations using PyTorch, AllenNLP, and NLTK
  * Delivered novel insights to improve customer satisfaction from production data and reduce call center call volume
  * Deployed RESTful Active Learning API to introduce targeted learning feedback loop and improve intent classification model performance

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Programming Languages**: Python, Ruby, Java, MATLAB, C/C++, C#, OCaml
* **Software Frameworks**: PyTorch, OpenCV, AllenNLP, NLTK, Flask


[[Download PDF]](http://neeharperi.com/files/NeeharResume.pdf)