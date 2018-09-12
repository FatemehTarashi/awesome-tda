# awesome-TDA

A curated list of [topological data analysis (TDA)](https://en.wikipedia.org/wiki/Topological_data_analysis) resources and links.
awesome-TDA is under development!
## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms)
    - [Morse-Smale complex](#morse-smale-complex)
    - [Persistent homology computation](#persistent-homology-computation)
    - [Persistent cohomology computation](#persistent-cohomology-computation)
    - [Reeb graph](#reeb-graph)
    - [Vineyards](#vineyards)
    - [Zigzag persistent homology ](#zigzag-persistent-homology )
  - [Articles](#articles)
    - [Homological Algebra and Data - Robert Ghrist](homological-algebra-and-data-robert-ghrist)
    - [Topological Data Analysis - Larry Wasserman](topological-data-analysis-larry-wasserman)
    - [Topological Data Analysis for Object Data - Patrangenaru,Bubenik,Paige,Osborne](#topological-data-analysis-for-object-data)
  
  - [Books](#books)
    - [A Short Course in Computational Geometry and Topology](a-short-course-in-computational-geometry-and-topology)
    - [Topological and Statistical Methods for Complex Data](#topological-and-statistical-methods-for-complex-data)
    - [Topological Data Analysis for Scientific Visualization](#topological-data-analysis-for-scientific-visualization )
    - [Topological Methods in Data Analysis and Visualization](#topological-methods-in-data-analysis-and-visualization)
    - [Topological Methods in Data Analysis and Visualization-II](#topological-methods-in-data-analysis-and-visualization-II )
    - [Topological Methods in Data Analysis and Visualization-III](#topological-methods-in-data-analysis-and-visualization-III)
    - [Topological Methods in Data Analysis and Visualization-IV](#topological-methods-in-data-analysis-and-visualization-IV )
    - [Topology-based Methods in Visualization](#topology-based-methods-in-visualization)
  - [Courses](#courses)
  - [Other lists](#other-lists)
- [Tools](#tools)
  - [TdaToolbox](#tdatoolbox)
  - [TTk](#ttk)
- [Frameworks and Libs](#frameworks-and-libs)
  - [C++](#c++)
    - [Ctl](#ctl)
    - [Dionysus](#dionysus)
    - [GUDHI](#gudhi)
    - [PHAT](#phat)
    - [TDA](#tda)
  - [Java](#java)
    - [JavaPlex](#javaplex)
  - [Python](#python)
    - [KeplerMapper](#keplermapper)
    - [kohonen](#kohonen)
    - [openTDA](#opentda)
    - [Python Mapper](#python-mapper)
    - [Scikit-TDA](#scikit-tda)
    - [scTDA](#sctda)
  - [R](#r)
    - [TDAmapper](#tdamapper)
  - [Spark](#spark)
    - [Spark Mapper](#spark-mapper)
    - [Spark-tda](#spark-tda)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Mailing lists](#mailing-lists)
  - [Web-tools](#web-tools)
  - [Web-sites](#web-sites)
- [Contributing](#contributing)-->
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms
#### Morse-Smale complex
#### Persistent homology computation
#### Persistent cohomology computation
#### Reeb graph
#### Vineyards
#### Zigzag persistent homology
#### Topological Domains in Mammalian Genomes Identified by Analysis of Chromatin Interactions

### Articles
#### An introduction to Topological Data Analysis:  fundamental and practical aspects for data scientists
  [Pdf](https://arxiv.org/pdf/1710.04019.pdf) - Abstract: Topological Data Analysis (tda) is a recent and fast growing field providing a set of new topological and geometric tools to infer relevant features for possibly complex data. This paper is a brief introduction, through a few selected topics, to basic fundamental and practical aspects of tda for non experts.

#### Homological Algebra and Data - Robert Ghrist
  [Pdf](https://www.math.upenn.edu/~ghrist/preprints/HAD.pdf) - Abstract: These  lectures  are  a  quick  primer  on  the  basics  of  applied  algebraic topology with emphasis on applications to data. In particular, the perspectives of (elementary) homological algebra, in the form of complexes and co/homological invariants are sketched. Beginning with simplicial and cell complexes as a means of enriching graphs to higher-order structures, we define simple algebraic topological invariants, such as Euler characteristic.  By lifting from complexes of simplices to algebraic complexes of vector spaces, we pass to homology as a topological compression scheme.  Iterating this process of expanding to sequences and compressing via homological algebra, we define persistent homology and related theories, ending with a simple approach to cellular sheaves and their cohomology. Throughout, an emphasis is placed on expressing homological-algebraic tools as
the natural evolution of linear algebra. Category-theoretic language (though morenatural and expressive) is deemphasized, for the sake of access.  Along the way, sample applications of these techniques are sketched,  in domains ranging from neuroscience to sensing, image analysis, robotics, and computation.

#### Topological Data Analysis - Larry Wasserman 
  [Pdf](https://arxiv.org/pdf/1609.08227.pdf) - Abstract: Topological Data Analysis (TDA) can broadly be described as a collection of data analysis methods that find structure in data.  This includes: clustering, manifold estimation, nonlinear dimension reduction, mode estimation, ridge estimation and persistent homology.  This paper reviews some of these methods. 

#### Topological Data Analysis for Object Data - Patrangenaru,Bubenik,Paige,Osborne
  [Pdf](https://arxiv.org/pdf/1804.10255.pdf) - Abstract: Statistical analysis on object data presents many challenges.  Basic summaries such as means and variances are difficult to compute.  We apply ideas from topology to study object data.  We present a framework for using persistence landscapes to vectorize object data and perform statistical analysis. We apply to this pipeline to some biological images that were previously shown to be challenging to study using shape theory. Surprisingly, the most persistent features are shown to be “topological noise” and the statistical analysis depends on the less persistent features which we refer to as the “geometric signal”. We also describe the first steps to a new approach to using topology for object data analysis,  which applies topology to distributions on object spaces
  
  
### Books
#### A Short Course in Computational Geometry and Topology
   Authors: Edelsbrunner, Herbert [springer link](https://www.springer.com/gp/book/9783319059563)
   - This monograph presents a short course in computational geometry and topology. In the first part the book covers Voronoi diagrams and Delaunay triangulations, then it presents the theory of alpha complexes which play a crucial role in biology. The central part of the book is the homology theory and their computation, including the theory of persistence which is indispensable for applications, e.g. shape reconstruction. The target audience comprises researchers and practitioners in mathematics, biology, neuroscience and computer science, but the book may also be beneficial to graduate students of these fields.

#### Topological and Statistical Methods for Complex Data
  Tackling Large-Scale, High-Dimensional, and Multivariate Data Spaces -  Editors: Bennett, Janine, Vivodtzev, Fabien, Pascucci, Valerio (Eds.) [springer link](https://www.springer.com/gp/book/9783662448991)  
  
  - This book contains papers presented at the Workshop on the Analysis of Large-scale, High-Dimensional, and Multi-Variate Data Using Topology and Statistics, held in Le Barp, France, June 2013. It features the work of some of the most prominent and recognized leaders in the field who examine challenges as well as detail solutions to the analysis of extreme scale data.
  
    The book presents new methods that leverage the mutual strengths of both topological and statistical techniques to support the management, analysis, and visualization of complex data. It covers both theory and application and provides readers with an overview of important key concepts and the latest research trends.

    Coverage in the book includes multi-variate and/or high-dimensional analysis techniques, feature-based statistical methods, combinatorial algorithms, scalable statistics algorithms, scalar and vector field topology, and multi-scale representations. In addition, the book details algorithms that are broadly applicable and can be used by application scientists to glean insight from a wide range of complex data sets.
    
#### Topological Data Analysis for Scientific Visualization
  Authors: Tierny, Julien [springer link](https://www.springer.com/gp/book/9783319715063) 
   - Combining theoretical and practical aspects of topology, this book provides a comprehensive and self-contained introduction to topological methods for the analysis and visualization of scientific data.

     Theoretical concepts are presented in a painstaking but intuitive manner, with numerous high-quality color illustrations. Key algorithms for the computation and simplification of topological data representations are described in detail, and their application is carefully demonstrated in a chapter dedicated to concrete use cases.

     With its fine balance between theory and practice, "Topological Data Analysis for Scientific Visualization" constitutes an appealing introduction to the increasingly important topic of topological data analysis for lecturers, students and researchers.

#### Topological Methods in Data Analysis and Visualization
  Theory, Algorithms, and Applications - Editors: Pascucci, V., Tricoche, X., Hagen, H., Tierny, J. (Eds.) [springer link](https://www.springer.com/gp/book/9783642150135)
   - Topology-based methods are of increasing importance in the analysis and visualization of datasets from a wide variety of scientific domains such as biology, physics, engineering, and medicine. Current challenges of topology-based techniques include the management of time-dependent data, the representation large and complex datasets, the characterization of noise and uncertainty, the effective integration of numerical methods with robust combinatorial algorithms, etc. While there is an increasing number of high-quality publications in this field, many fundamental questions remain unsolved. New focused efforts are needed in a variety of techniques ranging from the theoretical foundations of topological models, algorithmic issues related to the representation power of computer-based implementations as well as their computational efficiency, user interfaces for presentation of quantitative topological information, and the development of new techniques for systematic mapping of science problems in topological constructs that can be solved computationally. The editors have brought together the most prominent and best recognized researchers in the field of topology-based data analysis and visualization for a joint discussion and scientific exchange of the latest results in the field. The 2009 "TopoInVis" workshop in Snowbird, Utah, follows the two successful workshops in 2005 (Budmerice, Slovakia) and 2007 (Leipzig, Germany).
   
#### Topological Methods in Data Analysis and Visualization-II
  Theory, Algorithms, and Applications - Editors: Peikert, R., Hauser, H., Carr, H., Fuchs, R. (Eds.) [springer link](https://www.springer.com/gp/book/9783642231742) 
   - When scientists analyze datasets in a search for underlying phenomena, patterns or causal factors, their first step is often an automatic or semi-automatic search for structures in the data. Of these feature-extraction methods, topological ones stand out due to their solid mathematical foundation. Topologically defined structures—as found in scalar, vector and tensor fields—have proven their merit in a wide range of scientific domains, and scientists have found them to be revealing in subjects such as physics, engineering, and medicine.
  
     Full of state-of-the-art research and contemporary hot topics in the subject, this volume is a selection of peer-reviewed papers originally presented at the fourth Workshop on Topology-Based Methods in Data Analysis and Visualization, TopoInVis 2011, held in Zurich, Switzerland. The workshop brought together many of the leading lights in the field for a mixture of formal presentations and discussion. One topic currently generating a great deal of interest, and explored in several chapters here, is the search for topological structures in time-dependent flows, and their relationship with Lagrangian coherent structures. Contributors also focus on discrete topologies of scalar and vector fields, and on persistence-based simplification, among other issues of note. The new research results included in this volume relate to all three key areas in data analysis—theory, algorithms and applications.

#### Topological Methods in Data Analysis and Visualization-III
  Theory, Algorithms, and Applications - Editors: Bremer, P.-T., Hotz, I., Pascucci, V., Peikert, R. (Eds.) [springer link](https://www.springer.com/gp/book/9783319040981) 
   - his collection of peer-reviewed conference papers provides comprehensive coverage of cutting-edge research in topological approaches to data analysis and visualization. It encompasses the full range of new algorithms and insights, including fast homology computation, comparative analysis of simplification techniques, and key applications in materials and medical science. The volume also features material on core research challenges such as the representation of large and complex datasets and integrating numerical methods with robust combinatorial algorithms.

     Reflecting the focus of the TopoInVis 2013 conference, the contributions evince the progress currently being made on finding experimental solutions to open problems in the sector. They provide an inclusive snapshot of state-of-the-art research that enables researchers to keep abreast of the latest developments and provides a foundation for future progress. With papers by some of the world’s leading experts in topological techniques, this volume is a major contribution to the literature in a field of growing importance with applications in disciplines that range from engineering to medicine.
 #### Topological Methods in Data Analysis and Visualization-IV
  Theory, Algorithms, and Applications -  Editors: Carr, Hamish, Garth, Christoph, Weinkauf, Tino (Eds.) [springer link](https://www.springer.com/gp/book/9783319446820)
   - This book presents contributions on topics ranging from novel applications of topological analysis for particular problems, through studies of the effectiveness of modern topological methods, algorithmic improvements on existing methods, and parallel computation of topological structures, all the way to mathematical topologies not previously applied to data analysis.

     Topological methods are broadly recognized as valuable tools for analyzing the ever-increasing flood of data generated by simulation or acquisition. This is particularly the case in scientific visualization, where the data sets have long since surpassed the ability of the human mind to absorb every single byte of data.

     The biannual TopoInVis workshop has supported researchers in this area for a decade, and continues to serve as a vital forum for the presentation and discussion of novel results in applications in the area, creating a platform to disseminate knowledge about such implementations throughout and beyond the community.

     The present volume, resulting from the 2015 TopoInVis workshop held in Annweiler, Germany, will appeal to researchers in the fields of scientific visualization and mathematics, domain scientists with an interest in advanced visualization methods, and developers of visualization software systems.

#### Topology-based Methods in Visualization
  Editors: Hauser, Helwig, Hagen, Hans, Theisel, Holger (Eds.) [springer link](https://www.springer.com/gp/book/9783540708223)
   - Enabling insight into large and complex datasets is a prevalent theme in visualization research for which different approaches are pursued.
     Topology-based methods are built on the idea of abstracting characteristic structures such as the topological skeleton from the data and to construct the visualizations accordingly. There are currently new demands for and renewed interest in topology-based visualization solutions. This book presents 13 peer-reviewed papers as written results from the 2005 workshop “Topology-Based Methods in Visualization” that was initiated to enable additional stimulation in this field. It contains a longer chapter dedicated to a survey of the state-of-the-art, as well as a great deal of original work by leading experts that has not been published before, spanning both theory and applications. It captures key concepts and novel ideas and serves as an overview of current trends in topology-based visualization research.

### Courses
- [Computational Topology and Data Analysis](http://web.cse.ohio-state.edu/~dey.8/course/CTDA/CTDA.html) A course is not active, but the course notes are useful

- [Topological Data Analysis](hhttp://www.enseignement.polytechnique.fr/informatique/INF556/#Synopsis) A course is not active, but the course notes are useful
### Other lists

## Tools
### TdaToolbox
[TdaToolbox](https://github.com/Coricos/TdaToolbox)
  - [3DShape] - This notebook gives a simple example of how to handle three-dimensional shapes. The whole example is based on the height as filtration function, so not invariant in space. However, it gives a pretty good idea of what the output of a topological analysis may give.
  - [ToMaTo Clustering] - This notebook rather focus on a specific strength of TDA: its robustness to detect centroids in dataset, along with its ability to record the relationships between each point, enabling us to retrace the whole structure of the centroids. Examples are provided in the notebook.

### TTK
[TTk](https://topology-tool-kit.github.io/index.html) - The Topology ToolKit is an open-source library and software collection for topological data analysis in scientific visualization. TTK can handle scalar data defined either on regular grids or triangulations, either in 2D or in 3D. It provides a substantial collection of generic, efficient and robust implementations of key algorithms in topological data analysis.

For more information you can read ["Topological Data Analysis Made Easy with the Topology ToolKit"](https://arxiv.org/pdf/1806.08126.pdf) article.

## Frameworks and Libs

### C++
#### ctl
[Ctl](https://github.com/appliedtopology/ctl) - This C++11 library provides a set of generic tools for:
  - Building Neighborhood Graphs
  - Building Cellular Complexes
  - Computing [persistent] homology over finite fields
  - Parallel algorithm(s) for homology
  
#### Dionysus
[Dionysus](http://mrzv.org/software/dionysus/) - Dionysus is a C++ library for computing persistent homology. It provides implementations of the following algorithms:
  - Persistent homology computation 
  - Vineyards (C++ only)
  - Persistent cohomology computation 
  - Zigzag persistent homology 

#### GUDHI
[GUDHI](http://gudhi.gforge.inria.fr/) - The GUDHI library is a generic open source C++ library, with a Python interface, for Topological Data Analysis (TDA) and Higher Dimensional Geometry Understanding. The library offers state-of-the-art data structures and algorithms to construct simplicial complexes and compute persistent homology.

####  PHAT
[phat](https://bitbucket.org/phat-code/phat) - This software library contains methods for computing the persistence pairs of a filtered cell complex represented by an ordered boundary matrix with Z<sub>2</sub> coefficients. For an introduction to persistent homology, see the textbook. This software package contains code for several algorithmic variants:
  - The "standard" algorithm 
  - The "row" algorithm 
  - The "twist" algorithm
  - The "chunk" algorithm 
  - The "spectral sequence" algorithm 
  
#### TDA
[TDA](https://cran.r-project.org/web/packages/TDA/) - tools for the statistical analysis of persistent homology and for density clustering. For that, this package provides an R interface for the efficient algorithms of the C++ libraries [GUDHI](http://gudhi.gforge.inria.fr/), [Dionysus](http://www.mrzv.org/software/dionysus/), and [PHAT](https://bitbucket.org/phat-code/phat/). This package also implements the methods in Fasy et al. [(2014)](doi:10.1214/14-AOS1252) and Chazal et al. [(2014)](doi:10.1145/2582112.2582128) for analyzing the statistical significance of persistent homology features.

### Java
#### JavaPlex
[JavaPlex](https://github.com/appliedtopology/javaplex) - Persistent Homology and Topological Data Analysis Library - The JavaPlex library implements persistent homology and related techniques from computational and applied topology, in a library designed for ease of use, ease of access from Matlab and java-based systems, and ease of extensions for further research projects and approaches. JavaPlex is mainly developed by the Computational Topology workgroup at Stanford University, and is based on previous similar packages from the same group.

### Python
#### KeplerMapper
[KeplerMapper](https://github.com/MLWave/kepler-mapper) - This is a Python implementation of the TDA Mapper algorithm for visualization of high-dimensional data. For complete documentation, see https://kepler-mapper.scikit-tda.org.
KeplerMapper employs approaches based on the Mapper algorithm (Singh et al.) as first described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition".
KeplerMapper can make use of Scikit-Learn API compatible cluster and scaling algorithms.

#### kohonen
[kohonen](https://github.com/lmjohns3/kohonen) - This module contains some basic implementations of Kohonen-style vector quantizers: Self-Organizing Map (SOM), Neural Gas, and Growing Neural Gas. Kohonen-style vector quantizers use some sort of explicitly specified topology to encourage good separation among prototype "neurons".

#### mogutda
[mogutda](https://github.com/stephenhky/MoguTDA) - mogutda contains Python codes that demonstrate the numerical calculation of algebraic topology in an application to topological data analysis (TDA). Its core code is the numerical methods concerning implicial complex, and the estimation of homology and Betti numbers. mogutda runs in Python 2.7, 3.5, and 3.6.

#### openTDA
[openTDA](https://github.com/outlace/OpenTDA) - Open source Python library for topological data analysis (TDA)

#### Python Mapper
[Python Mapper](http://danifold.net/mapper/introduction.html)Python Mapper is a realization of this toolchain, written by Daniel Müllner and Aravindakshan Babu. It is open source software and is released under the GNU GPLv3 license. 
There is also a company, Ayasdi, which was founded by Gurjeet Singh, Gunnar Carlsson and Harlan Sexton and whose main product, the [Ayasdi Iris software](https://www.ayasdi.com/solutions/clinical-variation-management/), has the Mapper algorithm at its core. Ayasdi also issues academic trial licenses.

#### Scikit-TDA
[Scikit-TDA](https://scikit-tda.org/) - Scikit-TDA is a home for compatible TDA Python libraries intended for non-topologists. This project aims to provide a curated library of TDA Python tools that are widely usable and easily approachable.
It is structured so that each package can stand alone or be used as part of the scikit-tda bundle.
Current packages available:
  - [Ripser] - Data to diagrams in one line
  - [Persim] - Easy Persistence Images
  - [UMAP] - Mathematically justified dimensionality reduction
  - [Kepler Mapper] - Mapper framework integrated into sklearn
  - [TaDAsets] - Constructors for common data sets for demonstrating TDa.

#### scTDA
[scTDA](https://github.com/CamaraLab/scTDA) - scTDA is an object oriented python library for topological data analysis of high-throughput single-cell RNA-seq data. It includes tools for the preprocessing, analysis, and exploration of single-cell RNA-seq data based on topological representations.

### R
#### TDAmapper
[TDAmapper](https://github.com/paultpearson/TDAmapper/) - Topological Data Analysis using Mapper - An R package for using discrete Morse theory to analyze a data set using the Mapper algorithm described in G. Singh, F. Memoli, G. Carlsson (2007)

### Spark
#### Spark Mapper
[Spark Mapper](https://github.com/log0ymxm/spark-mapper) - Mapper is a topological data anlysis technique for estimating a lower dimensional simplicial complex from a dataset. It was initially described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition."

#### spark-tda
[spark-tda](https://github.com/ognis1205/spark-tda) - The scalable topological data analysis package for Apache Spark. This project aims to implement the following features:
  - [ Scalable Mapper Implemented as Reeb Diagrams, i.e., Reeb Cosheaves]
  - [Scalable Mapper Implementation]
  - [Scalable Multiscale Mapper Implementation]
  - [Scalable Tower Computation for Multiscale Mapper]
  - [Scalable Persistent Homology Computation on Top of Apache Spark]
  
 For more information you can read ["Sparse-TDA: Sparse Realization of Topological Data Analysis for Multi-Way Classification"](https://arxiv.org/pdf/1701.03212.pdf) article.
  
## Resources  
- [From Topological Data Analysis to Deep Learning: No Pain No Gain](https://towardsdatascience.com/from-tda-to-dl-d06f234f51d)

## License

`awesome-TDA by [@FatemehTarashi](https://github.com/FatemehTarashi) is licensed under the
GNU General Public License v3.0
