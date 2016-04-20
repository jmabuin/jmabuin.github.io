---
layout: page
title: Projects
permalink: /projects/
---

In this section you can find information about projects I have been working on. It is divided in two subsections, [Professional Projects](#professional) and [Personal Projects](#personal).

## <a name="professional"></a>Professional Projects ##

### Using Big Data technologies to perform Genomics Alignment ###

In this project we use the well known alignment software BWA to perform genomics alignment within a Hadoop cluster. The resulting software, BigBWA, can be found at https://github.com/citiususc/BigBWA.

Results probe that, using BigBWA in a Hadoop cluster in AWS with 32 cores, the user can have a speed up of 26.7.

### High Performance Computing for Natural Language Processing ###

In this project we used Big Data technologies (Hadoop) and cloud computing to carry out Natural Language processing (NLP) tasks. My main tasks are:

* Development of Java, Python and Perl programs within the MapReduce programming model.
* Performance analysis of different Natural Language Processing  tools for its use with Big Data technologies

From this project we obtain the software Perldoop (https://github.com/citiususc/perldoop). This software allow us to translate Perl code into Java to run it into a Hadoop cluster, but with some restrictions. You can find more information and help in the GitHub project page.

### GANESO (Gas Networks Simulator and Optimizator) ###

GANESO is a software to simulate and optimize the gas transport in gas pipelines by solving numeric equations asociated to this kind of problems.

This software is developed by using Fortran language and Pyhton for the graphic interface. In this graphic interface, the open source Quantum Gis has been used, because it allows to add Pyhton plugins.

My main tasks in this project are:

* Development of the graphic interface using Python
* Development of some program modules using Fortran
* Implementation of the program in cloud as SaaS (Software as a Service)

### Improving locality and affinity of the sparse matrix – vector product by using Morton representation ###

The optimization of the sparse matrix – product is nowadays a challenge, specially in multicore systems, because of its irregular accesses to memory. There are several studies in which various representations and techniques are analyzed. One of such representations is the Morton representation, that prooved to have advantages in situations where locality and affinity are main aspects.

In this project, results between classic representations and Morton are compared in terms of execution time and cache access. The implemented program is developed in C and using the PAPI library to measure counters.

### Recognition of people from different points of view within a multiple cameras environment ###

Final project for my engineering degree in Computer Science
This project belongs to a bigger project named “Multi-agent system for fast development of a guide robot in unknown environments” carried out by Adrián Canedo, Víctor Álvarez and Xosé Manuel Pardo López, members of the CiTIUS. My part in this project consists in know how cameras are located within an indoor environment. For doing this I used people recognition features from OpenCV libraries, an agent detects people in the camera images and, by detecting the same people in another cameras, I can know if these cameras are neighbors or not.

With this information about cameras being neighbors or not, robots from the other project can be guide due to situations detection within this indoor environment by knowing the cameras positions.

## <a name="personal"></a>Personal Projects ##
