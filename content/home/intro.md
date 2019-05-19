+++
#title = "Introduction"
#date = {{ .Date }}
draft = false
weight = 1

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
## Introduction
Diogenet is a dataset and tool for the investigation of the impact of
social ties on the construction and diffusion of knowledge in ancient
Greece. The main theoretical approach at the foundations of Diogenet is
formal social network analysis, a branch of anthropology and sociology.
Accordingly, we use the concepts of network, nodes and ties, to study
the relations that linked a large number of intellectuals of the ancient
world. Contrary to most intellectual histories of the ancient Greece, we
do not only focus on philosophers but also on their family members,
friends outside the field of philosophy and science, and benefactors.
Another important aspect of this project is our interest in the effect
of traveling on the discovery of ideas. We think that moving away from
the conception that fields of knowledge are closed systems allows a
better undestanding of the social processes that lie under the
dissemination of knowledge in the ancient world.

The main source of our current dataset is the *Lives and Opinions of
Eminent Philosophers* that [Diogenes
Laertius](http://diogenet.ucsd.edu/sources/) wrote in the third century
CE, about seven hundred years after the appearance of first philosophers
in Asia Minor. In this work, the Greek doxographer and biographer
reports the main theories and life anecdotes of the philosophers of the
archaic, classical, and Hellenistic periods. Despite his meticulous
accounts, however, Diogenes Laertius has been much distrusted by modern
historians of philosophy. One of the main arguments raised against his
work is based on the apparently excessive attention that he paid to
matters perceived as irrelevant for the history of ideas. These
digressions are in fact stories about the family, friends, romantic
relations, benefactors, and travels of ancient philosophers. It is
precisely this perceived weakness that makes his work a great starting
point for the reconstruction of the social networks of the intellectual
of ancient Greece.

Currently we offer four interactive visualizations of the social network
that Diogenes described in the *Lives*. To make sense of these
visualizations some background both in social network theory and the
history of ancient Greek philosophy is necessary. For this reason, we
recommend using the visualization tools in the
[Dashboard](http://diogenet.ucsd.edu/dashboard/) and the
[Map](http://diogenet.ucsd.edu/map/map.html) in conjunction with
Diogenes' text which is available in various editions in [Greek and
translation](http://diogenet.ucsd.edu/sources/) and an introduction to
social network analysis.



##  Network Visualizations
Diogenet's dataset can be accessed through the Dashboard. With the help
of the interactive applications that you will find there, you can
visualize a global and local view of the networks. Each network is built
by specific type of relation or tie. A family network, for instance, is
different from a network of friends or peer philosophers. The
expectations, themes of conversation and even patterns of behavior in
each network are influenced by the type of relation in which the actors
are involved.

### Global View
In the visualization that you see right below, the actors in the network are
represented as nodes and the relations between them as arrows or
vertices. We call it a global view because in it you can see the entire nextwork of teachers and pupils. This simplified version of the Dashboard is interactive, this means that the nodes can be moved with the mouse, and
clicking on the nodes will highlight their most immediate ties. You can
also scroll with the mouse to zoom in and out the network.

***
<iframe src="global_vnw.html" height="600" width="1100" align="middle" frameBorder="0">  </iframe>

***


### Local Networks

As we just mentioned, you can access Diogenet's dataset from different perspectives.  While the *Global View* of the network is important to gain a panoramic view of the overall structure, the *Local View* allows to focus on one specific node  and their neighbors.You can further explore the local view in the Dashboard where you will find several variables that can be modified.

#### Local View

***
<iframe src="egonet_vnw.html" height="600" width="1100" align="middle" frameBorder="0" scrolling="no"> </iframe>

***
 In network theory, a node that is the focus of a local analysis is called the *ego*, while its neighbors are *alters*. The distance between *ego* and *alter* is called *order*. Higher order will return more neighbors if the node is not socially isolated. The ego in the present visualization is Plato and the order set to 2, this means, it includes those individuals who are 1 to 2 steps away from Plato.  

###  Communities

With the help of different algorithms, it is possible to identify *communities*  of philosohers, friends, and family. A community is a cohesive group of social actors. In the diagram below, each community is highlighted with different colors. Most interestingly, algorithms find communities that do not overlap with current designations of philosophical schools. This is understadable because algorithms do not identify communties in terms of self-designations such as "followers of Plato". Instead they consider the actual ties that link the nodes.  



#### Communal View

***

<iframe src="comnty_vnw.html" height="600" width="1100" align="middle" frameBorder="0" scrolling="no"></iframe>


***

In the Dashboard, we offer here seven different algorithms you can choose from. Some of them, for example, the *Cluster Louvain* algorithm not only identifies communities but also the bridges that establish a path of communication between them.  In social network analysis,  a *bridge* is a tie that connects two components or communities. In the Dashboard, you can see the bridges highlighted in red when you chose Igraph as the visualization library. The library Visnetwork do not offer this option but it allows the nodes to be moved around for their closer inspection. 


