---
layout: page
title: Projects
permalink: /projects/
---

In this section you can find information about projects I have been working on. It is divided in two subsections, [Professional Projects](#professional) and [Personal Projects](#personal).

---

## <a name="professional"></a>Professional Projects ##

### Using Big Data technologies to perform Genomics Alignment ###

In this project we use the well known alignment software [BWA](https://github.com/lh3/bwa){:target="_blank"} to perform genomics alignment within a Hadoop cluster. The resulting software is [BigBWA](https://github.com/citiususc/BigBWA){:target="_blank"}.

Results probe that, using **BigBWA** in a Hadoop cluster in [AWS](https://aws.amazon.com/){:target="_blank"} with 32 cores, the user can have a speed up of **26.7x**.

### High Performance Computing for Natural Language Processing ###

In this project we used Big Data technologies (Hadoop) and cloud computing to carry out Natural Language processing (NLP) tasks. My main tasks are:

* Development of Java, Python and Perl programs within the MapReduce programming model.
* Performance analysis of different Natural Language Processing  tools for its use with Big Data technologies

From this project we obtain the software [Perldoop](https://github.com/citiususc/perldoop){:target="_blank"}. This software allow us to translate Perl code into Java to run it into a Hadoop cluster, but with some restrictions. You can find more information and help in the [project page](https://proxectos.citius.usc.es/hpcpln/){:target="_blank"}.

### GANESO (Gas Networks Simulator and Optimizator) ###

[GANESO](http://www.reganosa.com/es/software-ganeso){:target="_blank"} is a software to simulate and optimize the gas transport in gas pipelines by solving numeric equations asociated to this kind of problems.

This software is developed by using Fortran language and Pyhton for the graphic interface. In this graphic interface, the open source Quantum Gis has been used, because it allows to add Pyhton plugins.

My main tasks in this project are:

* Development of the graphic interface using Python
* Development of some program modules using Fortran
* Implementation of the program in cloud as SaaS (Software as a Service)

### Improving locality and affinity of the sparse matrix-vector product by using Morton representation ###

The optimization of the sparse matrix-vector product is nowadays a challenge, specially in multicore systems, because of its irregular accesses to memory. There are several studies in which various representations and techniques are analyzed. One of such representations is the Morton representation, that prooved to have advantages in situations where locality and affinity are main aspects.

In this project, results between classic representations and Morton are compared in terms of execution time and cache access. The implemented program is developed in C and using the [PAPI](http://icl.cs.utk.edu/papi/){:target="_blank"} library to measure counters.

### Recognition of people from different points of view within a multiple cameras environment ###

Final project for my engineering degree in Computer Science
This project belongs to a bigger project named “Multi-agent system for fast development of a guide robot in unknown environments” carried out by [Adrián Canedo](https://acanedorodriguez.wordpress.com/){:target="_blank"}, Víctor Álvarez and [Xosé Manuel Pardo López](https://persoal.citius.usc.es/xose.pardo/){:target="_blank"}, members of the CiTIUS. My part in this project consists in know how cameras are located within an indoor environment. For doing this I used people recognition features from [OpenCV](http://opencv.org/){:target="_blank"} libraries, an agent detects people in the camera images and, by detecting the same people in another cameras, I can know if these cameras are neighbors or not.

With this information about cameras being neighbors or not, robots from the other project can be guide due to situations detection within this indoor environment by knowing the cameras positions.

---

## <a name="personal"></a>Personal Projects ##

### CPM (Cluster Processes Monitor) ###

[CPM](https://github.com/jmabuin/CPM){:target="_blank"}, or Cluster Processes Monitor, is a tool to measure the performance of job processes inside a supercomputing cluster.

Typically, in a computing cluster, the task of monitorize a parallel job and get statictics, such as CPU consumption, used memory or other kind of data, is a tedious job that implies visualize large logs or modify the application source code. There are some solutions that monitorize all the cluster, such as [Nagios](https://www.nagios.org/){:target="_blank"} or [Zabbix](http://www.zabbix.com/){:target="_blank"}, but they monitorize the nodes total resources, and not per process of a launched job. **CPM** allows the user to monitorize data from individual processes in real time and get plots and statictics from them in a very easy way. It is composed by three programs that communicate among each other and work togheter across the network.

[CPM](https://github.com/jmabuin/CPM){:target="_blank"} is developed in [C++](https://en.wikipedia.org/wiki/C%2B%2B){:target="_blank"} using the [Qt](https://en.wikipedia.org/wiki/Qt_%28software%29){:target="_blank"} libraries.

### Matrix Market Suite ###

[Matrix Market Suite](https://github.com/jmabuin/matrix-market-suite){:target="_blank"} is a tool that creates and operates over matrices with the [Matrix Market](math.nist.gov/MatrixMarket/){:target="_blank"}  format.

This tool is created only for educational propossal. It is developed in [C](https://en.wikipedia.org/wiki/C_%28programming_language%29){:target="_blank"} language using the [CBLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms){:target="_blank"} library.

Functionalities:

- Create dense symmetric matrices.
- Create dense vectors.
- Dense matrix-vector multiplication.
- Solve linear systems using the [Conjugate Gradient](https://en.wikipedia.org/wiki/Conjugate_gradient_method){:target="_blank"} method.
- Parallelization of the Conjugate Gradient method and the dense matrix-vector multiplication by using [MPI](https://en.wikipedia.org/wiki/Message_Passing_Interface){:target="_blank"}.

To do functionalities:

- Parallelization of the Conjugate Gradient method and the dense matrix-vector multiplication by using [CUDA](https://en.wikipedia.org/wiki/CUDA){:target="_blank"}.
- Implementation of new linear systems solvers (Jacobi, etc,...).
- Implementation of operations for sparse matrices.
