---
layout: default
title: Home
desc: 'a suite of deep learning tools we have developed on discrete data'
---

<div>
  The website <a href="http://deeplearning4discrete.net/">deeplearning4discrete.net</a> introduces a suite of
    deep learning tools we have developed for learning patterns and making predictions on discrete 
    data, like text, graph, or sets.  Feel free to submit <a href="https://github.com/QData/deeplearning4discrete-web">pull requests</a> when you find my typos.

</div>

<hr>


## Background of Representation Learning and Deep Learning

The performance of machine learning algorithms is largely dependent on the
 data representation (or features) on which they are
applied. Deep learning aims at discovering learning algorithms that can
find multiple levels of representations directly from data, with higher
levels representing more abstract concepts. In recent years,
the field of deep learning has lead to groundbreaking performance in many applications such as computer vision, speech understanding, natural language processing, and computational biology.


## Why Discrete Data is Interesting? 

Deep learning constructs networks of parameterized functional modules and is trained  from reference examples using gradient-based optimization [Lecun19]. 

Since it is hard to estimate gradients through functions of discrete random variables, researching on how to make deep learning 
behave well on discrete data and discrete representation interests us. 
Developing such techniques are an active research area. We focus on investigating interpretable and scalable techniques for doing so.


## Relevant Papers we published 

+ Please check out each item in our side-bar


## We have focused on weak supervision in multiple of our papers along this line of research. 

![timeline]({{ site.baseurl }}pic/weaksupervised.png){:class="img-responsive"}


## Contacts:
Have questions or suggestions? Feel free to [ask me on Twitter](https://twitter.com/Qdatalab) or [email me](http://www.cs.virginia.edu/yanjun/).

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
