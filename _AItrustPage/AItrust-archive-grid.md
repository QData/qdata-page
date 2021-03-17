---
layout: category
permalink: /categories/AItrust/
taxonomy: AItrust
entries_layout: grid
classes: wide
desc: 'A suite of tools we designed for making machine learning secure and trustworthy. '
---

<div>
    This front adapts from our legacy website <a href="http://www.securemachinelearning.org/">http://TrustworthyMachineLearning.org/</a>  and introduces updates of  a suite of tools
  we have designed for making machine learning secure and trustworthy. This project involves toolboxes for five main tasks
  (organized as entries in the navigation menu).
  Please feel free to email me when you find my typos. 

</div>
<br>
<hr>


## Scope of problems our tools aim to tackle

Classifiers based on machine learning algorithms have shown promising results for many security tasks including malware classification and network intrusion detection, but classic machine learning algorithms are not designed to operate in the presence of adversaries. Intelligent and adaptive adversaries may actively manipulate the information they present in attempts to evade a trained classifier, leading to a competition between the designers of learning systems and attackers who wish to evade them. This project is developing automated techniques for predicting how well classifiers will resist the evasions of adversaries, along with general methods to automatically harden machine-learning classifiers against adversarial evasion attacks.



## Important tasks


At the junction between machine learning and computer security, this project involves toolboxes for five main task as  shown in the following table. Our system aims to allow a classifier designer to understand how the classification performance of a model degrades under evasion attacks, enabling better-informed and more secure design choices. The framework is general and scalable, and takes advantage of the latest advances in machine learning and computer security.

![timeline]({{ site.baseurl }}pic/trustworthyML.png){:class="img-responsive"}


![timeline]({{ site.baseurl }}pic/trustMLtime.png){:class="img-responsive"}


#### We categorize the topics into a list of subtasks and list our selected works in the following table: 

| No. | Tool Category  |   ~~~~~~~~~Paper~Title~~~~~~ | Venues |  Software |
| :--- | :-------: | :--------:  | :--------------------------: | -------: |
| 1 | Evade NLP Machine Learning |  [TextAttack: A Framework for Adversarial Attacks in Natural Language Processing] | EMNLP2020 | [GitHub](https://github.com/QData/TextAttack) |
| 2 | Evade Machine Learning | [Automatically Evading Classifiers, Case Study on PDF Malware Classifiers] | NDSS16  |[GitHub](https://github.com/uvasrg/EvadeML) |
| 3 | Evade NLP Machine Learning |  [Black-box Generation of Adversarial Text Sequences to Fool Deep Learning Classifiers] | DeepSecureWkp18 | [GitHub](https://github.com/QData/deepWordBug) |
| 4 | Detect Adversarial Attacks | [Feature Squeezing- Detecting Adversarial Examples in Deep Neural Networks]  | NDSS18 |[GitHub](https://github.com/QData/FeatureSqueezing) |
| 5 | Defense against Adversarial Attacks | [DeepCloak- Masking Deep Neural Network Models for Robustness against Adversarial Samples] | ICLRwkp17 | [GitHub](https://github.com/qdata/deepcloak) |
| 6 | Visualize Adversarial Attacks | [Adversarial-Playground- A Visualization Suite for Adversarial Samples]  | VizSec17 | [GitHub](https://github.com/QData/AdversarialDNN-Playground) |
| 7 | Theorems of Adversarial Examples | [A Theoretical Framework for Robustness of (Deep) Classifiers Against Adversarial Samples] | ICLRw17 |  |
| 8 | Trustworthy via Interpretation | [Deep Motif Dashboard] | ICLRw2017 |  |



## Contact
Have questions or suggestions? Feel free to [ask me on Twitter](https://twitter.com/Qdatalab) or [email me](http://www.cs.virginia.edu/yanjun/).

Thanks for reading!


<!--
<h2> Scope of problems our tools aim to tackle: </h2>

<div>Classifiers based on machine learning algorithms have shown promising results for many security tasks including malware classification and network intrusion detection, but classic machine learning algorithms are not designed to operate in the presence of adversaries. Intelligent and adaptive adversaries may actively manipulate the information they present in attempts to evade a trained classifier, leading to a competition between the designers of learning systems and attackers who wish to evade them. This project is developing automated techniques for predicting how well classifiers will resist the evasions of adversaries, along with general methods to automatically harden machine-learning classifiers against adversarial evasion attacks.
</div>

<br>
<div>
At the junction between machine learning and computer security, this project involves toolboxes for five main tasks. We associate
each task with a tag (see the following list of tags).
Our system aims to allow a classifier designer to understand how the classification performance of a model degrades under evasion attacks, enabling better-informed and more secure design choices. The framework is general and scalable, and takes advantage of the latest advances in machine learning and computer security.
</div>

<hr>

<h5>Our blog posts are organized by tags. Each tag represents an important category of secure-machine-learning tasks. </h5>


 <ul class="tags">
{% assign sorted = site.tags | sort %}
{% for tag in sorted %}
  {% assign t = tag | first %}
<a href="{{ site.baseurl }}#{{t | downcase | replace:" ","-" }}">{{ t  }}</a> |
{% endfor %}
</ul>

{% assign sorted = site.tags | sort %}
{% for tag in sorted %}
  {% assign t = tag | first %}
  {% assign posts = tag | last %}

<h4><a name="{{t | downcase | replace:" ","-" }}"></a><a class="internal" href="{{ site.baseurl }}#{{t | downcase | replace:" ","-" }}">
  {{ t }}</a></h4>
<ul>
{% for post in posts %}
  {% if post.tags contains t %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <span class="date">{{ post.date | date: "%B %-d, %Y"  }}</span>
  </li>
  {% endif %}
{% endfor %}
</ul>

{% endfor %}


<hr>

<h1> Blog Posts </h1>

<hr>

<div class="posts">

  {% for post in site.posts  %}

  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>
-->