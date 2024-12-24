---
layout: category
permalink: /categories/AIself/
taxonomy: AIself
title: Deep Learning's Generalization, Especially on structured discrete data
entries_layout: grid
classes: wide
desc: 'a suite of deep learning tools with weak supervisions that we have developed for structured data'
---


<div>
    This front adapts from our legacy website <a href="http://deeplearning4discrete.net/">deeplearning4discrete.net</a>  and introduces a suite of
    deep learning tools we have developed for improve deep learning generalization, especially when on discrete structured 
    data types like text, graph, or sets.  Please feel free to email me when you find my typos. 

</div>

<hr>

## Background on why Generalization topics of Deep Learning are interesting? 
Generalization refers to how a machine model adapts properly to new, previously unseen data. We focus on OOD (out of distribution) generalization. 


![timeline]({{ site.baseurl }}pic/OOD-generalization.png){:class="img-responsive"}



## Why structured discrete Data is Interesting? 

Deep learning constructs networks of parameterized functional modules and is trained  from reference examples using gradient-based optimization [Lecun19]. 

Since it is hard to estimate gradients through functions of discrete random variables, researching on how to make deep learning 
behave well on discrete structured data and structured representation interests us. 
Developing such techniques are an active research area. We focus on investigating interpretable and scalable techniques for doing so.


## Relevant Papers we published 

+ We can use a component-view to categorize the research topics in OOD generalization: 
  - (1) sample level 
  - (2) feature level 
  - (3) representation/encoding level
  - (4) loss level
  - (5) task level (e.g., meta learning, few shot generalization)
  - Please check out each item in our side-bar


![timeline]({{ site.baseurl }}pic/weaksupervised.png){:class="img-responsive"}


## Contacts:
Have questions or suggestions? Feel free to [ask me on Twitter](https://twitter.com/Qdatalab) or [email me](https://qiyanjun.github.io/Homepage/).

Thanks for reading!


<!--
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
