---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Research Overview

My research focuses on the intersection of **computer architecture**, **hardware acceleration**, and **emerging computational challenges** in bioinformatics and machine learning. I am particularly interested in designing efficient hardware solutions that can handle the computational demands of modern data-intensive applications.

---

## Core Research Areas

### 1. Processing-in-Memory (PIM) & Emerging Memory Technologies

The traditional von Neumann architecture separates memory from computation, leading to significant energy consumption and latency in data-intensive applications. My research explores:

- **3D DRAM Architectures**: Leveraging vertically-stacked DRAM for improved bandwidth and energy efficiency
- **FeRAM (Ferroelectric RAM)**: Exploring ferroelectric memory for near-data processing
- **FeNAND**: Emerging memory technologies that combine benefits for specialized workloads
- **In-Memory Computing**: Moving computation closer to data to reduce data movement overhead

### 2. Bioinformatics & Multi-omics Hardware Acceleration

Genomic and proteomic analysis generates exponentially growing datasets. Effective hardware acceleration requires understanding the unique computational patterns:

- **Genomics Acceleration**: Sequence alignment, assembly, and de Bruijn graph construction
- **Proteomics Processing**: Mass spectrometry data analysis and protein identification
- **Metabolomics Integration**: Combining multiple omics streams for systems biology
- **Real-time Analytics**: Enabling on-the-fly processing of streaming genomic data

### 3. Hardware Accelerator Design for Bioinformatics

Specialized hardware can dramatically improve performance and energy efficiency:

- **FPGA-based Acceleration**: Rapid prototyping and validation of accelerator designs
- **ASIC Design Methodology**: Long-term efficient implementations for deployment
- **Hardware-Software Co-design**: Jointly optimizing algorithms and hardware implementations
- **Performance Characterization**: Understanding accelerator performance across diverse workloads

### 4. Machine Learning Systems & Hardware Efficiency

Modern ML systems introduce new architectural challenges and opportunities:

- **Mixture-of-Experts (MoE) Models**: Hardware implications of expert selection and routing
- **Sparse Gating Mechanisms**: Efficient hardware implementation of conditional computation
- **Router Algorithms**: Hardware-friendly implementations of expert selection
- **Memory Bandwidth Optimization**: Addressing memory bottlenecks in large model inference

### 5. Graph Processing Acceleration

Graph algorithms have diverse applications from social networks to biological networks:

- **3D DRAM for Graphs**: Leveraging emerging memory for graph traversal
- **Graph Neural Networks (GNNs)**: Hardware acceleration for neural computation on graphs
- **Sequence-to-Graph Architectures**: Optimized processing for genomic graph algorithms like SeGraM
- **Scalable Graph Analytics**: Supporting billion-scale graphs with limited resources

---

## Current Projects

### General-Purpose In-Memory Accelerator for Bioinformatics
Developing a unified hardware accelerator platform for diverse bioinformatics workloads using 3D DRAM-based PIM architecture, in collaboration with Prof. Rob Knight's lab.

### Intel Hardware Acceleration for Bioinformatics
Characterizing bioinformatics workloads and optimizing them for Intel's Advanced Matrix Extensions (AMX) and In-Memory Analytics Accelerator (IAA), resulting in a comprehensive Bioinformatics Application Note.

### 3D DRAM Architecture for Graph Processing
TCAD-based research on optimizing 3D DRAM for efficient graph processing, with applications to genomic networks and knowledge graphs.

### Sequence-to-Graph Hardware Accelerators
Designing specialized accelerators for genomic sequence-to-graph transformation, enabling faster genome assembly and analysis pipelines.

---

## Methodology

My research approach combines:

- **Workload Characterization**: Profiling real applications to understand computational patterns
- **Simulation & Modeling**: TCAD and performance simulation tools to validate designs
- **Prototyping**: FPGA and software implementations for feasibility validation  
- **Benchmark Development**: Creating comprehensive benchmarks representing diverse applications
- **Collaboration**: Working with domain experts in biology and computer science

---

## Impact & Vision

My goal is to advance the state-of-the-art in hardware acceleration by:

1. **Bridging Disciplines**: Connecting computer architecture with computational biology
2. **Enabling Innovation**: Making advanced computational analysis accessible to researchers
3. **Improving Efficiency**: Reducing power consumption and latency in data-intensive workloads
4. **Supporting Biology**: Accelerating discovery in genomics, proteomics, and other life sciences

I believe that thoughtful hardware-software co-design can unlock new possibilities in understanding biological systems and training more efficient machine learning models.
