---
title: Projects
layout: page
tags: ['page']
pageOrder: 1
---

We have worked on various projects towards a <em>concrete, grounded, semantic</em> understanding of 3D environments.  What does it mean to understand 3D environments?  Our key insight is to look at real environments as spaces in which human actions take place.  Indoor spaces in particular are canvases that are designed by people to facilitate everyday human actions.  As people spend most of their time indoors, the focus of visual computing research on interiors will become more and more important.

We seek to answer a number of research questions:
- How do people interact with real environments?  What actions can they take?
- What names do people give to objects in scenes?  How are these names dependent on the appearance, functionality, and context?
- What are good representations for 3D scenes?  What features of 3D scene representations of real environments are most salient to people?
- How do environments evolve and change over time?

#### Scene understanding and representation

Underlying any attempt at understanding environments, we must consider how environments are to be represented.  Structured representations that allow for manipulation and changes.  We ask whether common knowledge about environments can be learned from data.  What representation do we need that will allow us to generate and synthesis new environments, to allow users to easily manipulate and interact with an virtual environment? 

## Human centric understanding of environments

One important key to understanding environment is to examine how people interact with their surroundings and how the environment is structured and designed to support human activities.  This is especially true of indoor environments, where architects, builders, and designer has specifically created spaces for us to live and work in.  We can view environments as <em>spaces for action</em>.  
- <b>SceneGrok</b> ([webpage](http://graphics.stanford.edu/projects/scenegrok/))
  Where can a person do X?
- <b>Activity based scene synthesis</b> ([webpage](http://graphics.stanford.edu/projects/actsynth/))
  How can knowledge of human activities be used to help arrange objects?
- <b>PiGraphs</b> ([webpage](http://graphics.stanford.edu/projects/pigraphs/)) 
- What does an static snapshot of a interaction such as 'watching TV' look like?  How is the person posed, what other objects are required for this interaction, and how are the object arranged with respect to the person.

## Scene synthesis
We believe that true understanding goes beyond passive recognition.  That it is important to be able to create new environments.  To that end, we have a series of projects that aims to synthesize new scenes.
- <b>Example based scene synthesis</b> ([webpage](http://graphics.stanford.edu/projects/scenesynth/))  Content creation is a time-consuming and challenging task.  In this project, we use object statistics and arrangement priors learned from a dataset of synthetic scenes to generate new novel scenes given examples. 
- <b>Activity based scene synthesis</b> ([webpage](http://graphics.stanford.edu/projects/actsynth/)) As indoor environments are spaces for action, how objects are arranged is often a consequence of what actitivies the environment is designed to support.  In this project, we use knowledge of human actions to inform and improve arrangement objects in generated scene.
- <b>Text to 3D scene generation</b> ([webpage](https://nlp.stanford.edu/data/text2scene.shtml), [demo](https://dovahkiin.stanford.edu/fuzzybox/text2scene.html)) A natural way for people to communicate what they want is via natural language.  In this project, we synthesize noval scenes based on natural language description such as 'a living room with a red couch'.
- <b>Scene editing</b> ([demo](https://dovahkiin.stanford.edu/fuzzybox/scene-suggest.html))  Creating and designing 3D scene can be challenging.  In this project, we seek to facilitate scene editing by allowing users to select a area where they would like to position an object, and then using priors of what objects typically occur at the location, to suggest and automatically place objects (with correct orientation and scale).

## Learning from synthetic data and simulation
Whether we can utilize synthesic scenes to generate training data for learning in a virtual world.
- <b>SSCNet</b> ([webpage](http://vision.princeton.edu/projects/2016/SSCNet/))
- <b>Characterizing Structural Relationships in Scenes using Graph Kernels</b> ([webpage](http://msavva.github.io/files/graphkernel.pdf))
- <b>Physically based rendering</b> ([webpage](http://robots.princeton.edu/projects/2016/PBRS/)])
- <b>Learning where to look</b> ([pdf](https://arxiv.org/abs/1704.02393))




