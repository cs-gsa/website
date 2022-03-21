+++
title = "Fast Estimation of the Earth Mover's Distance Graph Kernel"
date = 2022-03-04

[extra]
speaker = "Camden Sikes"
+++


# Abstract
Many types of data, from social networks to proteins, can be most naturally represented as graphs. It is often useful to measure the similarity between such graph-structured data, but the unordered nature of graphs makes this quite difficult. In lieu of mathematically meaningful metrics, which are computationally intractable, scientists develop and use graph kernels to efficiently compute similarity scores which are practically useful. One such method is the Earth Mover's Distance graph kernel, a measure based on the spectral properties of graphs. This method is very accurate on small graphs, but it is too slow to be run on even moderately large graphs. I introduce an approximation method which greatly increases the speed of the graph kernel computation while sacrificing very little accuracy. This presentation will assume little knowledge and will thus provide a strong background before introducing the proposed method.

# About the speaker
Camden Sikes is a second year PhD student in computer science, advised by Yousef Saad. He is interested in graph theory, computational linear algebra, and high performance computing.