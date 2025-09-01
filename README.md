Graphs and Networks
===================
This repository contains notebooks about graphs algorithms in Python and C.

# Introduction
A graph is represented as a list of nodes, or vertices, and a list of pairs of such nodes called edges. An edge can be directed or undirected, a graph can be cyclic or acyclic. They can be used to represent several real world or abstract objects such as a road or transport network, a social network, the financial network, a supply chain, the world wide web. We can be interested in studying the shortest path between two nodes in terms of the number of edges separating them, or the distribution of connections in the graph, and some statistical moment such as the average number of connections for each node. Graphs can be provided, as in the case of a social or road network, or they can be learnt in probabilistic terms (random graphs), for example by calculating the correlations between variables in a system such as the correlation between the stock prices of firms in a financial market. A network can be static or dynamic. Neural networks can be used to learn a graph, that is computing the probabilities for any two nodes to be connected, from data. A particular type of graphs is a knowledge graph where vertices belong to a hierarchy of classes and are connected by links that may have a logical property that allow to deduct inferences. A subset of a knowledge graph can be used for network analysis. A network can be used to analyze the spreading of an epidemic and many other dynamical processes. For example, an infection can be represented using the [SIR model](https://en.wikipedia.org/wiki/Compartmental_models_(epidemiology)#The_SIR_model) with a set differential equations. Each node will update its state depending on the state of adjacent nodes. The procedure is similar to that used in spatial grids or regular lattices, the difference being that the adjacent nodes are not necesserely spatially contiguous but they might be connected through a transport network, i.e. road, railways of air.   

## Python packages
* [NetworkX - Network Analysis in Python](https://networkx.org/documentation/stable/index.html)

## References
* Trudeau - Introduction to Graph Theory
* [Newman - The Structure and Function of Complex Networks∗](https://arxiv.org/abs/cond-mat/0303516)
* [Pastor-Satorras et al. - Epidemic processes in complex networks](https://arxiv.org/abs/1408.2701)
* [Dorogovtsev - Evolution of networks](https://arxiv.org/abs/cond-mat/0106144)
* Bollobas - Random Graphs, 2nd Edition
* Sedgewick - Algorithms in C - Part 5 - Graph  Algorithms, 3rd Edition
