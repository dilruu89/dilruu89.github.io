

## High Performance Out-of-sample Embedding Techniques for Multidimensional Scaling


**Paper available at:**<a href="https://arxiv.org/abs/2111.04067" target="_blank">Out-of-sample Embedding</a>

**Project description:** The exponential growth in dataset dimensions has spurred considerable interest in dimension reduction (DR) techniques. Efficient and high-performance DR algorithms are crucial for handling vast and rapidly evolving datasets. However, the efficacy of many traditional DR methods is challenged by the immense scale of contemporary data. Notably, multidimensional scaling (MDS), a widely used group of DR techniques, encounters scalability issues. Despite its popularity, MDS struggles to scale effectively, making it less practical for large datasets.

In response, we propose an innovative solution termed "out-of-sample embedding" (OSE) to enhance the MDS algorithm's scalability for large-scale data. The core idea involves extending MDS by embedding only a subset of the provided data. We introduce two distinct OSE techniques:
Optimization-Based Approach: The first technique leverages an optimization approach. By embedding a subset of data, it strikes a balance between approximation and accuracy, enabling the processing of large datasets with manageable computation and memory demands.

1. Neural Network Model: The second technique builds upon a neural network model. This approach also relies on the OSE concept and demonstrates superior efficiency compared to the
2. Optimization-based method, with only a marginal compromise on approximation quality.

Notably, OSE offers a dual advantage. It facilitates rapid DR on both streaming datasets and static databases. This flexibility makes OSE an appealing solution for scenarios where timely analysis of dynamic data streams or large static databases is critical.

### Techniques/ Algorithms / Metrics

The following are the techniques/analyses we mainly used in this project.

1. Multidimensional Scaling
2. Dimension Reduction
3. Spatial Mapping
4. Kd-Tree and Nearest Neighbor Search
5. out-of-sample embedding
6. Neural Networks
