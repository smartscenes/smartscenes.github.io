---
title: Projects
layout: page
tags: ['page']
pageOrder: 1
---

We have worked on various projects towards a <em>concrete, grounded, semantic</em> understanding of 3D environments.  What does it mean to understand 3D environments?  Our key insight is to look at real environments as spaces in which human actions take place.  Indoor spaces in particular are canvases that are designed by people to facilitate everyday human actions.  As people spend most of their time indoors, the focus of visual computing research on interiors will become more and more important.

We seek to answer a number of research questions:
- How do people interact with real environments?  What actions can they take?  Where can they perform certain actions?  How should objects be arranged in the environment to enable these actions?
- What names do people give to objects in scenes?  How are these names dependent on the appearance, functionality, and context?
- What are good representations for 3D scenes?  What features of 3D scene representations of real environments are most salient to people?
- How do environments evolve and change over time?  How does human actions change the environment?
- Can we learn a unified model of scenes from data?  Can we encode common knowledge about environments in this model?  

#### Scene understanding and representation

Underlying any attempt at understanding environments, we must consider how environments are to be represented.  What representation do we need that will allow us to generate and synthesis new environments, to allow users to easily manipulate and interact with an virtual environment?  

We believe that a structured representation will be helpful for easy manipulation of objects and changes to scenes.  Thus, in many of our projects, we represent scenes as graphs that encode objects and their semantic relationships.  In <b>Characterizing Structural Relationships in Scenes using Graph Kernels</b> ([pdf](http://msavva.github.io/files/graphkernel.pdf)), we use graphs to represent scenes and define a similarity function between the graphs to enable retrieval of similar scenes.  The representation of a scene as semantic graph is used in many of the projects described below.

## Human centric understanding of environments

One important key to understanding environment is to examine how people interact with their surroundings and how the environment is structured and designed to support human activities.  This is especially true of indoor environments, where architects, builders, and designer has specifically created spaces for us to live and work in.  We view environments as <em>spaces for action</em>.  
- <b>SceneGrok</b> ([webpage](http://graphics.stanford.edu/projects/scenegrok/))
  Where can a person do X?
- <b>Activity based scene synthesis</b> ([webpage](http://graphics.stanford.edu/projects/actsynth/))
  How can knowledge of human activities be used to help arrange objects?
- <b>PiGraphs</b> ([webpage](http://graphics.stanford.edu/projects/pigraphs/)) 
 What does an static snapshot of a interaction such as 'watching TV' look like?  How is the person posed, what other objects are required for this interaction, and how are the object arranged with respect to the person.

## Data based scene synthesis
An important way that understanding can be demostrated is by building a model from which examples can be generated.  For us, that means that means building a generative model of environments that we can use to create new environments.  As it can be difficult to specify by hand the different rules that give rise to indoor environments, we believe it is important to learn these models from data.  To that end, we have a series of projects that aims learn common sense priors on the arrange of objects and use those priors to synthesize new scenes or to make changes to existing scenes.
- <b>Example based scene synthesis</b> ([webpage](http://graphics.stanford.edu/projects/scenesynth/))  Content creation is a time-consuming and challenging task.  In this project, we use object statistics and arrangement priors learned from a dataset of synthetic scenes to generate new novel scenes given examples. 
- <b>Activity based scene synthesis</b> ([webpage](http://graphics.stanford.edu/projects/actsynth/)) As indoor environments are spaces for action, how objects are arranged is often a consequence of what actitivies the environment is designed to support.  In this project, we use knowledge of human actions to inform and improve arrangement objects in generated scene.
- <b>Text to 3D scene generation</b> ([webpage](https://nlp.stanford.edu/data/text2scene.shtml), [demo](https://dovahkiin.stanford.edu/fuzzybox/text2scene.html)) A natural way for people to communicate what they want is via natural language.  In this project, we synthesize noval scenes based on natural language description such as 'a living room with a red couch'.
- <b>Scene editing</b> ([demo](https://dovahkiin.stanford.edu/fuzzybox/scene-suggest.html))  Creating and designing 3D scene can be challenging.  In this project, we seek to facilitate scene editing by allowing users to select a area where they would like to position an object, and then using priors of what objects typically occur at the location, to suggest and automatically place objects (with correct orientation and scale).

## Learning from 3D environments
As a big focus of our research use 3D data for learning, we have helped to create several large 3D datasets (see [datasets](datasets.html) for more details).  We want to leverage virtualizations of real 3D environments to create improved synthetic environments, and use existing 3D data to improve virtualizations of real environments.

We are also interested in exploring whether synthetic data can be used to generate training data for scene understanding.
- <b>SSCNet</b> ([webpage](http://vision.princeton.edu/projects/2016/SSCNet/))  From a single depth image, can we leverage synthetic data to produce a 3D voxelization of the space with predicted semantic labels?
- <b>Physically based rendering</b> ([webpage](http://robots.princeton.edu/projects/2016/PBRS/)) Can we utilize pysically based renderings of synthetic scenes as training data for improving performance on common vision tasks such as normal detection and object segmentation?
- <b>Learning where to look</b> ([pdf](https://arxiv.org/abs/1704.02393)) 
For vision tasks that rely on renderings from a single viewpoint, there are questions of what kind of viewpoints are appropriate.  In this project, we  generate camera viewpoints for a 3D space that semantically match those found in a reference set of images.

## Simulation
We believe that true understanding goes beyond passive recognition, that an agent must be able to interact with objects in the environment and to observe changes.  To enable understanding of environments via interaction, we have developed a indoor simulator:
- <b>MINOS: Multimodal Indoor Simulator</b> ([webpage](https://minosworld.github.io/)) 

We hope that the indoor simulation environment can be used by researchers from vision, robotics, natural language, and machine learning disciplines to investigate a variety of open research questions.




