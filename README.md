# Integrating Ginkgo with M++ for High-Performance PDE Solving

This repository contains the code and documentation for a thesis project aimed at integrating the high-performance sparse linear system solver Ginkgo with the parallel finite element software M++ to accelerate the solution of linear elliptic PDEs on GPUs.

## Project Overview

This project aims to develop a practical interface between M++ and Ginkgo, enabling efficient GPU utilization for solving large-scale linear systems arising from finite element discretizations. The goal is to contribute to the development of powerful tools for scientific and engineering applications.

## Key Features

* **Interface Development:** A well-defined interface handling data transfer, format conversions, and solver selection.
* **Performance Evaluation:** Benchmarking the integrated system with simplified test cases, comparing execution time, memory usage, and scalability.
* **Technical Documentation:** Documentation detailing design choices, implementation details, performance analysis, and limitations.
* **Optional Goal:** Explore a distributed memory implementation to efficiently solve large-scale problems on distributed memory systems with multiple GPUs.

## Project Progress

**[          ]** 0% Complete

**Tasks:**
- [ ] Collect research papers
- [ ] Summarize numerical algorithms
- [ ] Implement simple test case 
- [ ] Benchmarking
- [ ] Improve results
- [ ] Finalize thesis

## Project Timeline

| Month | Tasks                                                    |
|-------|---------------------------------------------------------|
| Oct   | - Collect relevant research papers and resources.       |
|       | - Summarize existing numerical linear algebra algorithms. |
| Nov   | - Continue collecting and reviewing research papers.    |
|       | - Refine project scope and goals.                       |
| Dec   | - Implement a simple test case using the integrated system. |
|       | - Begin basic performance benchmarking.                  |
| Jan   | - Conduct thorough benchmarking of the interface.         |
|       | - Analyze initial performance results.                   |
| Feb   | - Optimize interface based on performance analysis.     |
|       | - Improve the accuracy and scalability of the interface.   |
| March | - Finalize thesis writing and documentation.             |
|       | - Prepare for thesis defense.                            |

### Phases

- **Phase 1 (Oct - Dec):** Focus on gathering information, setting up the project environment, and developing a basic prototype.
- **Phase 2 (Jan - March):**  Concentrate on performance analysis, optimization, and final thesis writing.


## Acknowledgements

Special thanks to Dr. Niklas Baumgarten for his guidance and support. 
