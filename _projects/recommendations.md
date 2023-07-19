---
layout: page
title: Recommendations For Streaming Data
description: abstract, paper, poster and some slides
img: 
importance: 1
category: work
giscus_comments: true
---
# Abstract
> Recommender systems have become increasingly popular in recent years because of the broader popularity of many webenabled electronic commerce applications. However, most recommender systems today are designed in the context of an offline setting. The online setting is, however, much more challenging because the existing methods do not work very effectively for very large-scale systems. In many applications, it is desirable to provide real-time recommendations in large-scale scenarios. The main problem in applying streaming algorithms for recommendations is that the in-core storage space for memory-resident operations is quite limited. In this paper, we present a probabilistic neighborhood-based algorithm for performing recommendations in real-time. We present experimental results, which show the effectiveness of our approach in comparison to state-of-the-art methods.

# Intuition
> - Many recommendation systems need to compute user-user and item-item similarities to make recommendations
> - This can be time-consuming; so, a way to compute them (similarities) *quickly* is proposed
> - This allows the model to perform computations "on the fly" since it does not have to go offline to make new calculations
> - Performance is still great while using fewer resources

# Poster
Download [here](/assets/pdf/cikm_2016_poster.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/cikm_2016_poster.pdf" width="100%" height="800" type='application/pdf'></object>

# Slides
Download [here](/assets/pdf/cikm_2016_slides.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/cikm_2016_slides.pdf" width="100%" height="500" type='application/pdf'></object>

# Paper
Download [here](/assets/pdf/cikm_2016_paper.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/cikm_2016_paper.pdf" width="100%" height="800" type='application/pdf'></object>
