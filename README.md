# CSE 570 : Introduction to Parallel and Distributed Processing

## Requirements
- A CCR node from the GPGPU-capable partition with CUDA 8.0 will be used for testing.
- Your code will be tested for efficiency.

##  Assignment 1: 
- Implement an efficient **NVIDIA CUDA** program for Gaussian kernel density estimate. 
- **Assumptions**
  - The input vector ```X``` and output vector ```Y``` are single precision.
  - The size ```n``` of vectors ```X``` and ```Y``` exceeds capacity of a single CUDA thread block, but is small enough to be processed by a single kernel invocation. 

## Assignment 2:
- Implement efficient end-to-end **Apache Spark** program for finding connected components in an undirected graph 
- **Assumptions**
  - The undirected graph ```G``` is too large to fit into a single compute node.
  - The graph ```G``` is represented by a list of edges in the form of ```source target ``` where ```source``` is the source vertex id and ```target``` is the target vertex id. The vertices are represented as integers. Assume the graph has no self loops. The list of edges are provided as a text file. 
