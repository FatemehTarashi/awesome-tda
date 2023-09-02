# Awesome TDA  [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of [Topological Data Analysis (TDA)](https://en.wikipedia.org/wiki/Topological_data_analysis) tools and resources. 

If you know of any other tools or resources, read [Contribution Guidelines](https://github.com/FatemehTarashi/awesome-tda/blob/master/contributing.md) and feel free to fork/PR or open a new issue. 

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms) 
  - [Books](#books)
  - [Articles](#articles)
  - [Courses](#courses)
- [Tools](#tools)
- [Frameworks and Libs](#frameworks-and-libs)
  - [C++](#c)
  - [Go](#go)
  - [Haskell](#haskell)
  - [Java](#java)
  - [Julia](#julia)
  - [Matlab](#matlab)
  - [Python](#python)
  - [R](#r)
  - [Spark](#spark)
- [Useful Links](#useful-links)
  - [Bioinformatics](#bioinformatics)
  - [Brain Network Analysis](#brain-network-analysis)
  - [Computing Homology](#computing-homology)
  - [Computer Vision](#computer-vision)
  - [Data Professionals](#data-professionals)
  - [Deep Learning](#deep-learning)
  - [Machine Learning](#machine-learning)
  - [Persistent Homology](#persistent-homology)
  - [Use Python](#use-python)
  - [Use R](#use-r)
  - [Theory and applications of TDA](#theory-and-applications-of-tda)
- [Event](#event)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

## Theory

### Algorithms

<!-- * Morse-Smale complex -->
<!-- * Persistent homology computation -->
<!-- * Persistent cohomology computation -->
<!-- * Reeb graph -->
<!-- * Topological Domains in Mammalian Genomes Identified by Analysis of Chromatin Interactions -->
- [Chunk](https://www.researchgate.net/publication/235766026_Clear_and_Compress_Computing_Persistent_Homology_in_Chunks)
- [Mapper](http://diglib.eg.org/handle/10.2312/SPBG.SPBG07.091-100)
 ([brief summary](https://github.com/ognis1205/spark-tda/wiki/Mapper))
- [PHrow](https://arxiv.org/pdf/1107.5665.pdf)
- [Twist](https://www.researchgate.net/publication/228605960_Persistent_homology_computation_with_a_twist)
- [Vineyards](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.114.5942&rep=rep1&type=pdf)
- [Zigzag persistent homology](https://www.mrzv.org/publications/zigzags/socg09/) 
- [Zigzag Persistent Cohomology](https://arxiv.org/pdf/1608.06039.pdf)
  
### Books
   
- [A Short Course in Computational Geometry and Topology](https://www.springer.com/gp/book/9783319059563) - Edelsbrunner, Herbert.

- [Computational Homology (Applied Mathematical Sciences)](https://www.amazon.com/dp/1441923543/) - Kaczynski, Mischaikow, Mrozek.

- :open_book: [Computational Topology: An Introduction](https://www.maths.ed.ac.uk/~v1ranick/papers/edelcomp.pdf) - Herbert Edelsbrunner, John L Harer.

- :open_book: [Computational Topology for Data Analysis](https://www.cs.purdue.edu/homes/tamaldey/book/CTDAbook/CTDAbook.pdf) - Tamal Krishna Dey, Yusu Wang.

- :open_book: [Elementary Applied Topology](https://www.math.upenn.edu/~ghrist/notes.html) - Robert Ghrist.

- [Fundamentals of Brain Network Analysis](https://www.amazon.com/Fundamentals-Brain-Network-Analysis-Fornito-ebook/dp/B01CRIU886) - Fundamentals of Brain Network Analysis.

- [Geometric and Topological Inference](https://www.researchgate.net/publication/320412992_Geometric_and_Topological_Inference) - Boissonnat, Chazal, Yvinec.

- :open_book: [Persistence Theory: From Quiver Representations to Data Analysis](https://geometrica.saclay.inria.fr/team/Steve.Oudot/books/o-pt-fqrtda-15/surv-209.pdf) - Steve Y Oudot.

- [Topological and Statistical Methods for Complex Data: Tackling Large-Scale, High-Dimensional, and Multivariate Data Spaces](https://www.springer.com/gp/book/9783662448991) -  Bennett, Janine, Vivodtzev, Fabien, Pascucci, Valerio.

- [Topological Based Machine Learning Methods](https://escholarship.org/uc/item/4vr8963d) - Alex Georges.

- [Topological Data Analysis for Genomics and Evolution: Topology in Biology](https://www.cambridge.org/core/books/topological-data-analysis-for-genomics-and-evolution/FCC8429FAD2B5D1525AEA47A8366D6EB) - Raul Rabadan, Andrew J Blumberg.

- [Topological Data Analysis for Scientific Visualization](https://www.springer.com/gp/book/9783319715063) - Tierny, Julien.

-  :open_book: [Topological Methods for 3D Point Cloud Processing](https://www-users.cse.umn.edu/~beksi001/publications/topological_methods_for_3d_point_cloud_processing.pdf) - William Joseph Beksi.

- :open_book: [Topology for Computing](http://directory.umm.ac.id/Networking%20Manual/Topology%20for%20Computing.pdf) - AFRA J ZOMORODIAN.

- [Topological Methods in Data Analysis and Visualization: Theory, Algorithms, and Applications](https://www.springer.com/gp/book/9783642150135)
- [Topological Methods in Data Analysis and Visualization: Theory, Algorithms, and Applications II](https://www.springer.com/gp/book/9783642231742)
- [Topological Methods in Data Analysis and Visualization: Theory, Algorithms, and Applications III](https://www.springer.com/gp/book/9783319040981)
- [Topological Methods in Data Analysis and Visualization: Theory, Algorithms, and Applications IV](https://www.springer.com/gp/book/9783319446820)
  
- [Topology-based Methods in Visualization](https://www.springer.com/gp/book/9783540708223) -  Hauser, Helwig, Hagen, Hans, Theisel, Holger (Eds.)
  
### Articles

- [A Fuzzy Clustering Algorithm for the Mode Seeking Framework](https://arxiv.org/abs/1406.7130) - Bonis, Oudot.

- [A topological data analysis based classification method for multiple measurements](https://arxiv.org/abs/1904.02971) - Riihimäki, Chachólski, Theorell, Hillert, Ramanujam.

- [A User's Guide to Topological Data Analysis](https://learning-analytics.info/journals/index.php/JLA/article/view/5196/6089) - Elizabeth Munch.
  
- [An introduction to Topological Data Analysis:  fundamental and practical aspects for data scientists](https://arxiv.org/abs/1710.04019) - Chazal, Michel.

- [Barcodes: The Persistent Topology of Data](https://www.math.upenn.edu/~ghrist/preprints/barcodes.pdf) - Robert Ghrist.

- [Computing Persistent Homology (Discrete and Computational Geometry)](https://geometry.stanford.edu/papers/zc-cph-05/zc-cph-05.pdf) - Zomorodian, Carlsson.

- [Deep Learning with Topological Signatures](https://papers.nips.cc/paper/6761-deep-learning-with-topological-signatures.pdf) - Hofer, Kwitt, Niethammer, Uhl.

- [Designing machine learning workflows with an application to topological data analysis](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0225577) - Cawi, La Rosa, Nehorai.

- [Introduction to the R package TDA](https://cran.r-project.org/web/packages/TDA/vignettes/article.pdf) - Fasy, Jisu Kim, Lecci, Clément Maria, Millman, Rouvreau.
  
- [Homological Algebra and Data](https://www.math.upenn.edu/~ghrist/preprints/HAD.pdf) - Robert Ghrist.
  
- [Large Scale computation of Means and Clusters for Persistence Diagrams using Optimal Transport](https://arxiv.org/abs/1805.08331) -  Lacombe, Cuturi, OUDOT.
  
- [Sampling real algebraic varieties for topological data analysis](https://arxiv.org/abs/1802.07716) - Dufresne, Edwards, Harrington, Hauenstein.

- [Stratifying Multiparmeter Persistent Homology](https://arxiv.org/pdf/1708.07390.pdf) - Harriington, Otter, Schenck, Tillmann.
  
- [Text Mining using Topological Data Analysis. An introduction](https://www.researchgate.net/publication/323705256_Text_Mining_using_Topological_Data_Analysis_An_introduction) - Carrazana, Chong.

- [Topology and Data](https://www.ams.org/journals/bull/2009-46-02/S0273-0979-09-01249-X/S0273-0979-09-01249-X.pdf) - Gunnar Carlsson.

- [Topological Data Analysis](https://arxiv.org/abs/1609.08227) - Larry Wasserman.

- [Topological Data Analysis and Its Application to Time-Series Data Analysis](https://www.fujitsu.com/global/documents/about/resources/publications/fstj/archives/vol55-2/paper15.pdf) - Umeda, Kaneko, Kikuchi.

- [Topological Data Analysis and Machine Learning Theory](https://www.birs.ca/workshops/2012/12w5081/report12w5081.pdf) - Carlsson , Jardine, Feichtner-Kozlov, Morozov.

- [Topological Data Analysis for Object Data](https://arxiv.org/abs/1804.10255) - Patrangenaru, Bubenik, Paige, Osborne .

- [Two-Tier Mapper: a user-independent clustering method for global gene expression analysis based on topology](https://arxiv.org/abs/1801.01841) - Jeitziner, Carrière, Rougemont, Oudot, Hess, Brisken.

- [Why Topology for Machine Learning and Knowledge Extraction?](https://res.mdpi.com/d_attachment/make/make-01-00006/article_deploy/make-01-00006.pdf) - Massimo Ferri.

### Courses
- [Applied Algebraic Topology Seminars](https://topology.ima.umn.edu/seminars)

- [Computational Topology and Data Analysis](http://web.cse.ohio-state.edu/~dey.8/course/CTDA/CTDA.html) - Course is not active, but the course notes are useful.

- [Topological Data Analysis](http://www.enseignement.polytechnique.fr/informatique/INF556/#Synopsis) - Course is not active, but the course notes are useful.

- [Topics in topology: Scientific and engineering applications of algebraic topology](http://homepage.math.uiowa.edu/~idarcy/AT/prelectures.html) - 2013 lecture series. 
<!--([videos here](https://www.youtube.com/channel/UCThuKLGcSXhBJ5GlwzHobJw/videos?view=0&sort=da&flow=grid)) on TDA.--->

## Tools
- [Ctl](https://github.com/appliedtopology/ctl) - (C++11 library) A set of generic tools for Building Neighborhood Graphs and Cellular Complexes, Computing (persistent) homology over finite fields, Parallel algorithms for homology. an be used with c++, Python, MATLAB and R.

- [Knotter](https://github.com/rosinality/knotter) - Implementation of Mapper algorithm for TDA.

- [RIVET](https://github.com/rivetTDA/rivet) - For the visualization and analysis of two-parameter persistent homology with [Python API](https://github.com/rivetTDA/rivet-python/).

- [TdaToolbox](https://github.com/Coricos/TdaToolbox) - Some tools that may be applied to data science in general.

- [TTk](https://topology-tool-kit.github.io/index.html) - Topological data analysis in scientific visualization. Can be used with C++, python.

## Frameworks and Libs

### C++  
- [Dionysus](http://mrzv.org/software/dionysus/) - Computing persistent (co)homology, Implementation of the Persistent (co)homology computation, Vineyards, Zigzag persistent homology algorithms.

- [GUDHI](http://gudhi.gforge.inria.fr/) - Geometry Understanding in Higher Dimensional with a Python interface.

- [PHAT](https://bitbucket.org/phat-code/phat) - Persistent Homology Algorithm Toolbox.
    
### Go
- [TDA](https://github.com/kshedden/tda) - Some methods are provided for gridded data (images).

### Haskell 
- [Persistence](https://hackage.haskell.org/package/Persistence) 

### Java
- [JavaPlex](https://github.com/appliedtopology/javaplex) - The JavaPlex library implements persistent homology and related techniques. It designed for ease of use from Matlab and java-based systems.

### Julia 
- [Eirene.jl](https://github.com/Eetion/Eirene.jl) -  For homological persistence.
- [TDA.jl](https://github.com/wildart/TDA.jl) - This package provides Persistence Diagram & Barcode, Nerve, Mapper tools for topological data analysis.

### Matlab
- [Clique Top](https://github.com/nebneuron/clique-top) - Doing topological analysis of symmetric matrices.

### Python
- [GDA Public](https://geomdata.github.io/gda-public/) - Several fundamental tools by Geometric Data Analytics Inc. [geomdata](http://www.geomdata.com)

- [KeplerMapper](https://github.com/MLWave/kepler-mapper) - TDA Mapper algorithm for visualization of high-dimensional data. it can make use of Scikit-Learn API compatible cluster and scaling algorithms.

- [Kohonen](https://github.com/lmjohns3/kohonen) - Kohonen-style vector quantizers: Self-Organizing Map (SOM), Neural Gas, and Growing Neural Gas.

- [Mapper Implementation](https://github.com/ksanjeevan/mapper-tda) - Topological Data Analysis for high dimensional dataset exploration.

- [MoguTDA](https://github.com/stephenhky/MoguTDA) - Numerical calculation of algebraic topology in an application to topological data analysis: implicial complex, and the estimation of homology and Betti numbers.

- [OpenTDA](https://github.com/outlace/OpenTDA)

- [Python Mapper](http://danifold.net/mapper/introduction.html) - Mapper algorithm implementation + graphical user interface.

- [Qsv](https://github.com/RottenFruits/qsv) - Data structure visualizer.

- [Scikit-TDA](https://scikit-tda.org/) - For non-topologists.

- [Giotto-TDA](https://giotto-ai.github.io/gtda-docs/) - A ``scikit-learn`` - compatible library for end-to-end topological machine learning including Mapper, persistent homology, vectorization methods for persistence diagrams, and preprocessing components for time series, graphs, images, and point clouds ([paper](https://openreview.net/forum?id=fjQtZJOCTXf)).

- [ScTDA](https://github.com/CamaraLab/scTDA) - It includes tools for the preprocessing, analysis, and exploration of single-cell RNA-seq data based on topological representations.

- [TMAP](https://tmap.readthedocs.org) - Population-scale microbiome data analysis.

### R
- [TDA](https://cran.r-project.org/web/packages/TDA/) - Tools for the statistical analysis of persistent homology and for density clustering.

- [TDAmapper](https://github.com/paultpearson/TDAmapper/) - An R package for using discrete Morse theory to analyze a data set using the Mapper algorithm described in G. Singh, F. Memoli, G. Carlsson (2007).

- [TDAstats](https://github.com/rrrlw/TDAstats) - Computing persistent homology.

### Spark
- [Spark Mapper](https://github.com/log0ymxm/spark-mapper) - Estimating a lower dimensional simplicial complex from a dataset.

- [Spark TDA](https://github.com/ognis1205/spark-tda) - Scalable topological data analysis package.
  
## Useful Links

### Bioinformatics
- [List of Resources for Topological Data Analysis in Bioinformatics](https://github.com/biobai/BioTDA/blob/52715e03fe8cfe1ee11eced06896f74e1e5b4f1a/README.md)

### Brain Network Analysis
- [An algebraic topological method for multimodal brain networks comparisons](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.00904/full)

- [Complex Brain Network Analysis and Its Applications to Brain Disorders: A Survey](https://new.hindawi.com/journals/complexity/2017/8362741/)

- [Functional Brain Network Topology Discriminates between Patients with Minimally Conscious State and Unresponsive Wakefulness Syndrome](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6463121/)

- [Graph theory methods: applications in brain networks](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6136126/)

- [Topological Methods in Brain Network Analysis](https://braintopology.wordpress.com/tda/)

### Computing Homology
- [Computing Homology](https://jeremykun.com/2013/04/10/computing-homology/)

### Computer Vision
- [Topological Data Analysis in Computer Vision](https://www.researchgate.net/publication/338956906_Topological_data_analysis_in_computer_vision)

### Data Professionals
- [Topological Data Analysis for Data Professionals](https://www.kdnuggets.com/2018/01/topological-data-analysis.html)

### Deep Learning
- [Applied Topological Data Analysis to Deep Learning? Hands-on Arrhythmia Classification!](https://towardsdatascience.com/applied-topological-data-analysis-to-deep-learning-hands-on-arrhythmia-classification-48993d78f9e6)

- [From Topological Data Analysis to Deep Learning: No Pain No Gain](https://towardsdatascience.com/from-tda-to-dl-d06f234f51d)

- [On Characterizing the Capacity of Neural Networks Using Algebraic Topology](https://openreview.net/forum?id=H11lAfbCW)

- [Using Topological Data Analysis to Understand the Behavior of Convolutional Neural Networks](https://www.ayasdi.com/blog/artificial-intelligence/using-topological-data-analysis-understand-behavior-convolutional-neural-networks/)

### Machine Learning
- [How TDA and Machine Learning Enhance Each Other](https://www.ayasdi.com/blog/bigdata/how-tda-and-machine-learning-enhance-each-other/)

- [Machine Learning Explanations with Topological Data Analysis](https://sauln.github.io/blog/tda_explanations/)

- [Topological Methods for Machine Learning](http://topology.cs.wisc.edu/)

- [Topological Machine Learning](https://www.sthu.org/research/topmachinelearning/)

### Persistent Homology
- [A roadmap for the computation of persistent homology](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-017-0109-5#Sec34)

- [Practical Guide to Persistent Homology](http://www.mrzv.org/software/dionysus2/tutorial/index.html)

### Use Python
- [Topological Data Analysis - A Python tutorial](https://www.thekerneltrip.com/statistics/topological-data-analysis-tutorial/)

### Use R
- [A Mathematician's Perspective on Topological Data Analysis and R](https://rviews.rstudio.com/2018/11/14/a-mathematician-s-perspective-on-topological-data-analysis-and-r/)

### Theory and applications of TDA
- [A concrete application of Topological Data Analysis](https://towardsdatascience.com/a-concrete-application-of-topological-data-analysis-86b89aa27586)

- [A Guide to Data Science from mathematics](https://github.com/Hulalazz/A-_Guide_-to_Data_Sciecne_from_mathematics/blob/f42b92bb6a34f32d8c4e7afe98c9bdc889413688/TDA.md)

- [An Algebraic Geometry Perspective on Topological Data Analysis](https://sinews.siam.org/Details-Page/an-algebraic-geometry-perspective-on-topological-data-analysis)

- [Topological Data Analysis - A Very Short Introduction](https://medium.com/@varad.deshmukh/topological-data-analysis-a-very-short-introduction-611d3238a0bd)

- [Topological Data Analysis](https://people.clas.ufl.edu/peterbubenik/intro-to-tda/) - UFL.

- [Topological Data Analysis](https://researcher.watson.ibm.com/researcher/view_group.php?id=6585) - IBM.

- [Theory and applications of topological data analysis](https://datawarrior.wordpress.com/category/tda/)

## Event
- [Conferences and workshops](https://people.clas.ufl.edu/peterbubenik/conferences/)

- [International Conference on Computational Topology and Topological Data Analysis](https://waset.org/computational-topology-and-topological-data-analysis-conference)
