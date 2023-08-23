## Generating name-like numbers

**Paper available at:** https://ieeexplore.ieee.org/document/9585113

**Project description:** Entity resolution (ER), the problem of identifying and matching records that belong to the same real-world entities in structured and unstructured data, is a primary task in data integration. Accurate and efficient entity resolution has a huge practical impact on a range of applications across commercial, security and scientific domains. Recently, scalable ER techniques have received enormous attention with the increasing need to combine large-scale datasets. Developing and testing ER algorithms suffer from the shortage of training and ground truth data. Good public datasets, especially those containing personal information, are restricted in this area and usually small in size. Due to privacy and confidential issues, testing algorithms or techniques with real datasets is challenging in ER research. Simulation is one technique for generating synthetic datasets that follow similar characteristics as real data for testing algorithms. 

Many existing simulation tools in ER lack support for generating large-scale data and have problems in complexity, scalability, and limitations of resampling. In our work, we propose a simple, inexpensive, and fast synthetic data generation tool. In the first stage, our tool only generates entity names that are commonly used as identification keys in ER algorithms. We avoid the detail-level simulation of entity names using a simple vector representation that delivers simplicity and efficiency. In this paper, we will discuss how to simulate simple vectors that approximate the properties of entity names. We describe the overall construction of the tool based on data analysis of a namespace that contains entity names collected from the actual environment. 

### Techniques/ Algorithms / Metrics

The following are the techniques/analyses I mainly used in this project.

1. Multidimensional Scaling
2. Dimension Reduction
3. Multivariate Normal Analysis
4. Gaussian and Zip distribution
5. Embedding Strings as Vectors
