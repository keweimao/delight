---
title: Search & Retrieval
summary: Decentralized search and retrieval on the web scale. Efficiency, effectiveness, and scalability. 
tags:
- Information Retrieval
- Distributed Systems
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: Photo by Expect Best on Pixels
  focal_point: Smart
---

A thread of my research is on big data (due to its volume and variety) and how distributed systems with machine learning (ML) can adapt and scale. With the objective to develop a large-scale decentralized search engine, we draw on inspirations from research in complex networks and multi-agent systems. We showed that efficient decentralized searches are possible in a distributed network of agents only when the network structure is optimized. According to a phenomenon we refer to as the \textit{Clustering Paradox}, there is a specific level of network clustering, i.e. grouping of neighbor agents with an ideal proportion of similar vs. dissimilar contents, where searches can be most efficient. Either over-clustering or under-clustering will lead to degraded search performances. Finding the ideal level is key to the success of agent collaboration for decentralized information seeking. 

Fortunately such an ideal network structure can be achieved without a global knowledge or hard engineering in a top-down manner. Rather, agents can interconnect locally and organically to construct this global structure from bottom up. Using a connectivity probability function that favors neighbors with similar contents but allows small chances to connect with those that are different, the network of these agent communities will emerge with the following two types of links (or ties): 1) strong ties that define local communities and serve as anchors (labels) to direct searches toward their relevant target, and 2) weak ties that connect different communities together and serve as ``hubs'' for searches to jump from one community to another. 
