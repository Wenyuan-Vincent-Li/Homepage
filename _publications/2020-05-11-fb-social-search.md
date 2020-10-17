---
title: "A Social Search Model for Large Scale Social Networks"
collection: publications
permalink: /publication/2020-05-11-fb-social-search
excerpt: 'With the rise of social networks, information on the internet is no
longer solely organized by web pages. Rather, ...'
date: 2020-05-11
venue: 'Arxiv'
citation: 'Yunzhong He, Wenyuan Li, Liang-Wei Chen, Gabriel Forgues, Xunlong Gui, Sui Liang, and Bo Hou (2020). 
&quot; A Social Search Model for Large Scale Social Networks. &quot; 
<i>arXiv preprint arXiv:2005.04356</i>.'
---
### Abstract:
With the rise of social networks, information on the internet is no
longer solely organized by web pages. Rather, content is generated
and shared among users and organized around their social relations
on social networks. This presents new challenges to information
retrieval systems. On a social network search system, the generation
of result sets not only needs to consider keyword matches, like a
traditional web search engine does, but it also needs to take into
account the searcher’s social connections and the content’s visibility
settings. Search ranking should also be able to handle both textual
relevance and the rich social interaction signals from the social
network.

In this paper, we present our solution to these two challenges by
first introducing a social retrieval mechanism, and then investigate
novel deep neural networks for the ranking problem. The retrieval
system treats social connections as indexing terms, and generates
meaningful results sets by biasing towards close social connections
in a constrained optimization fashion. The result set is then ranked
by a deep neural network that handles textual and social relevance
in a two-tower approach, in which personalization and textual
relevance are addressed jointly.

The retrieval mechanism is deployed on Facebook and is helping
billions of users finding postings from their connections efficiently.
Based on the postings being retrieved, we evaluate our two-tower
neutral network, and examine the importance of personalization
and textual signals in the ranking problem.

[Download paper here](https://arxiv.org/pdf/2005.04356.pdf)