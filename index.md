---
layout: page
title: About me
cover: false
---

**Thank you Tony Stark... I mean, Iron Man**

**自来也真是个很好的老师。坚持到底，勇往直前**

I am working on NLP problems now. Feel free to contact me via wechat: 547160794. I am open to make friends with you. :D

Natural Language Processing(e.g. Dialogue system, question answering, LLM-based things(like agent) etc.) & its applications in Education and Marketing(Advertising).

Things about **Education**, **Healthcare**, **Economy** and **Marketing** are also interesting to me:). 

I'd like to live a vigorous life even ending with dying poorly.

## Vision
Enable Humanity

## Mission
The only thing that I want to do is to help **me** and **people around me** become better

## Principle
~~Honesty~~ 
Nature

## Attention
Who moved my cheese

## Recent news
I am currently exploring new applications of NLP, especially those related to LLMs, with a particular focus on the areas of psychology, education, economics, marketing, as well as agents and collaboration. I'm also open to ideas in other areas, so feel free to reach out if you have any thoughts

## Professional Service
- Conference reviewer
	- ACL
  - AACL
  - EMNLP
- Shared task holder 
	- NLPCC [2020](http://tcci.ccf.org.cn/conference/2020/cfpt.php)
  - NLPCC [2021](http://tcci.ccf.org.cn/conference/2021/cfpt.php)

## Current Highlights
[Google Scholar](https://scholar.google.com/citations?user=JNXKtlgAAAAJ&hl=en)

<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<script>
  (adsbygoogle = window.adsbygoogle || []).push({
    google_ad_client: "ca-pub-7419738440913608",
    enable_page_level_ads: true
  });
</script>

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

