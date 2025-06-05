# Amazon-Last-Mile-Route-Optimization

A Reproduction Study of the Amazon Last Mile Routing Challenge: A Traveling Salesman Problem Approach

Department of Quantitative Economics, University of California Los Angeles

Author: Aakanksha Dutta

Faculty Advisor: Denis Chetverikov

4th June 2025

ABSTRACT

Last-mile delivery routing is a critical challenge in logistics, impacting efficiency, cost, and customer satisfaction. Amazon’s Last Mile Routing Research Challenge launched in 2021 provides a real-world dataset of delivery sequences, offering an opportunity to study how human drivers navigate complex urban environments. The challenge invited data scientists from Massachusetts Institute of Technology (MIT) to improve the efficiency of last-mile delivery routes using realworld logistics data.
This paper aims to reproduce and analyze the methodology employed by Chen Wu, Yin Song, Verdi March and Eden Duthie, one of the top-performing team in the challenge. The analysis focuses on three key datasets - actual delivery sequences, route scoring outputs, and package-related metadata - and outlines the preprocessing and analytical framework applied. Initial data integration and visualization steps are used to assess the consistency of the current approach with that of the reference team, serving as a foundation for subsequent optimization and modeling efforts. This paper reproduces the challenge by: (1) Modeling zone transitions using a probabilistic Prediction by Partial Matching (PPM) model, (2)Evaluating sequence prediction accuracy using both exact-match and set-based metrics, and (3) Generating executable routes by integrating zone-level predictions with Traveling Salesman Problem (TSP) optimization. The resulting approach offers a reproducible methodology for last-mile routing research and supports the validity of hierarchical spatial modeling in logistics applications.
Key Terms: Last-Mile Routing, Probabilistic Modeling, Spatial Hierarchies, Traveling Salesman Problem
