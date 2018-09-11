# awesome-TDA

A curated list of [topological data analysis (TDA)](https://en.wikipedia.org/wiki/Topological_data_analysis) resources and links.

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms)
    - [Morse-Smale complex](#Morse-Smale-complex)
    - [Persistent homology computation](#Persistent-homology-computation)
    - [Persistent cohomology computation](#Persistent-cohomology-computation)
    - [Reeb graph](#Reeb-graph)
    - [Vineyards](#Vineyards)
    - [Zigzag persistent homology ](#Zigzag-persistent-homology )

    
  - [Articles](#articles)
  - [Books](#books)
  - [Courses](#courses)
  - [Other lists](#other-lists)
- [Tools](#tools)
- [Frameworks and Libs](#frameworks-and-libs)
  - [GUDHI](#GUDHI)
  - [Python](#python)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Mailing lists](#mailing-lists)
  - [Web-tools](#web-tools)
  - [Web-sites](#web-sites)
- [Contributing](#contributing)
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Morse-Smale complex

### Articles

### Books

### Courses
- [Computational Topology and Data Analysis](http://web.cse.ohio-state.edu/~dey.8/course/CTDA/CTDA.html)

### Other lists

## Tools
- [TdaToolbox](https://github.com/Coricos/TdaToolbox)
  - [3DShape] - This notebook gives a simple example of how to handle three-dimensional shapes. The whole example is based on the height as filtration function, so not invariant in space. However, it gives a pretty good idea of what the output of a topological analysis may give.
  - [ToMaTo Clustering] - This notebook rather focus on a specific strength of TDA: its robustness to detect centroids in dataset, along with its ability to record the relationships between each point, enabling us to retrace the whole structure of the centroids. Examples are provided in the notebook.


- [TTk](https://topology-tool-kit.github.io/index.html) - The Topology ToolKit is an open-source library and software collection for topological data analysis in scientific visualization. TTK can handle scalar data defined either on regular grids or triangulations, either in 2D or in 3D. It provides a substantial collection of generic, efficient and robust implementations of key algorithms in topological data analysis.

## Frameworks and Libs

### C++
- [Ctl](https://github.com/appliedtopology/ctl) - This C++11 library provides a set of generic tools for:
  - Building Neighborhood Graphs
  - Building Cellular Complexes
  - Computing [persistent] homology over finite fields
  - Parallel algorithm(s) for homology

- [Dionysus](http://mrzv.org/software/dionysus/) - Dionysus is a C++ library for computing persistent homology. It provides implementations of the following algorithms:
  - Persistent homology computation 
  - Vineyards (C++ only)
  - Persistent cohomology computation 
  - Zigzag persistent homology 

- [GUDHI](http://gudhi.gforge.inria.fr/) - The GUDHI library is a generic open source C++ library, with a Python interface, for Topological Data Analysis (TDA) and Higher Dimensional Geometry Understanding. The library offers state-of-the-art data structures and algorithms to construct simplicial complexes and compute persistent homology.

- [TDA](https://cran.r-project.org/web/packages/TDA/) - tools for the statistical analysis of persistent homology and for density clustering. For that, this package provides an R interface for the efficient algorithms of the C++ libraries [GUDHI](http://gudhi.gforge.inria.fr/), [Dionysus](http://www.mrzv.org/software/dionysus/), and [PHAT](https://bitbucket.org/phat-code/phat/). This package also implements the methods in Fasy et al. [(2014)](doi:10.1214/14-AOS1252) and Chazal et al. [(2014)](doi:10.1145/2582112.2582128) for analyzing the statistical significance of persistent homology features.

### Java
- [JavaPlex](https://github.com/appliedtopology/javaplex) - Persistent Homology and Topological Data Analysis Library - The JavaPlex library implements persistent homology and related techniques from computational and applied topology, in a library designed for ease of use, ease of access from Matlab and java-based systems, and ease of extensions for further research projects and approaches. JavaPlex is mainly developed by the Computational Topology workgroup at Stanford University, and is based on previous similar packages from the same group.

### Python
- [KeplerMapper](https://github.com/MLWave/kepler-mapper) - This is a Python implementation of the TDA Mapper algorithm for visualization of high-dimensional data. For complete documentation, see https://kepler-mapper.scikit-tda.org.
KeplerMapper employs approaches based on the Mapper algorithm (Singh et al.) as first described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition".
KeplerMapper can make use of Scikit-Learn API compatible cluster and scaling algorithms.

- [kohonen](https://github.com/lmjohns3/kohonen) - This module contains some basic implementations of Kohonen-style vector quantizers: Self-Organizing Map (SOM), Neural Gas, and Growing Neural Gas. Kohonen-style vector quantizers use some sort of explicitly specified topology to encourage good separation among prototype "neurons".

- [mogutda](https://github.com/stephenhky/MoguTDA) - mogutda contains Python codes that demonstrate the numerical calculation of algebraic topology in an application to topological data analysis (TDA). Its core code is the numerical methods concerning implicial complex, and the estimation of homology and Betti numbers. mogutda runs in Python 2.7, 3.5, and 3.6.

- [openTDA](https://github.com/outlace/OpenTDA) - Open source Python library for topological data analysis (TDA)

- [Python Mapper](http://danifold.net/mapper/introduction.html)Python Mapper is a realization of this toolchain, written by Daniel Müllner and Aravindakshan Babu. It is open source software and is released under the GNU GPLv3 license. 
There is also a company, Ayasdi, which was founded by Gurjeet Singh, Gunnar Carlsson and Harlan Sexton and whose main product, the [Ayasdi Iris software](https://www.ayasdi.com/solutions/clinical-variation-management/), has the Mapper algorithm at its core. Ayasdi also issues academic trial licenses.

- [Scikit-TDA](https://scikit-tda.org/) - Scikit-TDA is a home for compatible TDA Python libraries intended for non-topologists. This project aims to provide a curated library of TDA Python tools that are widely usable and easily approachable.
It is structured so that each package can stand alone or be used as part of the scikit-tda bundle.
Current packages available:
  - [Ripser] - Data to diagrams in one line
  - [Persim] - Easy Persistence Images
  - [UMAP] - Mathematically justified dimensionality reduction
  - [Kepler Mapper] - Mapper framework integrated into sklearn
  - [TaDAsets] - Constructors for common data sets for demonstrating TDa.

- [scTDA](https://github.com/CamaraLab/scTDA) - scTDA is an object oriented python library for topological data analysis of high-throughput single-cell RNA-seq data. It includes tools for the preprocessing, analysis, and exploration of single-cell RNA-seq data based on topological representations.

### R
- [TDAmapper](https://github.com/paultpearson/TDAmapper/) - Topological Data Analysis using Mapper - An R package for using discrete Morse theory to analyze a data set using the Mapper algorithm described in G. Singh, F. Memoli, G. Carlsson (2007)

### Spark

- [Spark Mapper](https://github.com/log0ymxm/spark-mapper) - Mapper is a topological data anlysis technique for estimating a lower dimensional simplicial complex from a dataset. It was initially described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition."

- [spark-tda](https://github.com/ognis1205/spark-tda) - The scalable topological data analysis package for Apache Spark. This project aims to implement the following features:
  - [ Scalable Mapper Implemented as Reeb Diagrams, i.e., Reeb Cosheaves]
  - [Scalable Mapper Implementation]
  - [Scalable Multiscale Mapper Implementation]
  - [Scalable Tower Computation for Multiscale Mapper]
  - [Scalable Persistent Homology Computation on Top of Apache Spark]
  
  
  
## License

`awesome-TDA by [@FatemehTarashi](https://github.com/FatemehTarashi)
