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
- [kohonen](https://github.com/lmjohns3/kohonen) - This module contains some basic implementations of Kohonen-style vector quantizers: Self-Organizing Map (SOM), Neural Gas, and Growing Neural Gas. Kohonen-style vector quantizers use some sort of explicitly specified topology to encourage good separation among prototype "neurons".

- [Python Mapper](http://danifold.net/mapper/introduction.html)Python Mapper is a realization of this toolchain, written by Daniel Müllner and Aravindakshan Babu. It is open source software and is released under the GNU GPLv3 license. 
There is also a company, Ayasdi, which was founded by Gurjeet Singh, Gunnar Carlsson and Harlan Sexton and whose main product, the [Ayasdi Iris software](https://www.ayasdi.com/solutions/clinical-variation-management/), has the Mapper algorithm at its core. Ayasdi also issues academic trial licenses.

### R
- [TDAmapper](https://github.com/paultpearson/TDAmapper/) - Topological Data Analysis using Mapper - An R package for using discrete Morse theory to analyze a data set using the Mapper algorithm described in G. Singh, F. Memoli, G. Carlsson (2007)

## License

`awesome-TDA by [@FatemehTarashi](https://github.com/FatemehTarashi)
