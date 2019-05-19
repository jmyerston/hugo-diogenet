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



##  Network Visualization
With the help of the interactive application that you find below, you can visualize a global view of the network in different ways. You can choose three different types of ties that connect the nodes in the network. For now, these ties are teacher-disciple, friends, and family. In the future, we will add other types of ties denoting who *send letters to whom*, who *cited* and *read* whom, among others. You can scroll with the mouse to zoom in and out the network view; changing the size of the labels can improve readability.

###  Global Networks
Aliquam consectetur est gravida erat blandit rhoncus. In dolor quam, aliquet ut pellentesque quis, volutpat finibus neque. Phasellus vel quam ac dui commodo mattis. Donec ac sodales lorem. Mauris blandit non elit sed porttitor. Praesent pulvinar vel est sit amet sodales. Fusce laoreet pretium eros a feugiat. Nullam in arcu vitae est dapibus gravida. Vestibulum ultrices magna id sagittis fringilla. Vivamus in diam a ipsum viverra interdum quis nec eros. Aliquam sapien libero, semper a ultricies a, dignissim ac enim. Nunc malesuada massa ligula, sit amet lacinia tellus laoreet quis. In sed nisi augue. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas euismod accumsan dolor, a aliquam justo ultricies sit amet. Aliquam erat volutpat. 

####  Global View 
***
<iframe src="global_vnw.html" height="600" width="1100" align="middle" frameBorder="0">  </iframe>

***


### Local Networks

In this site, you can access the Diogenet Network from different perspectives or views.  While the *Global View* of the network is important to gain a perspective of the overall extension of the structure, the *Local View* allows to focus on one specific node (currenly only human actors) and their neighbors.  The variable *Order* of the *Local View* determines the distance between *Ego* and its neighbors. Setting *Order* to 1 will return only the node choosen in the pop-up menu *Node*; setting it to 2 will return *Ego* and its neighbors at 2 steps from *Ego*.

#### Local View

***
<iframe src="egonet_vnw.html" height="600" width="1100" align="middle" frameBorder="0" scrolling="no"> </iframe>

***

###  Communities

With the help of different algorithms and the use of the library igraph, it is possible to identify **communities** in Diogenet. A community is a cohesive group of social actors. We offer here three different algorithms you can choose from. Some of them, for example, the **Cluster Louvain** algorithm not only identifies communities but the bridges that establish a path of communication between them.  In social network analysis,  a **bridge** is a tie that connects two components or communities. In the present visualization of communities bridges are highlighted with red ties.

At the end of each bridge, there are nodes that control the flow of ideas and information in general between communities. Those nodes are brokers of special importance for understanding the structure of the network. A broker can act as a facilitator between two or more communities of intellectuals but can also capitalize such a position by restricting the flow of communication between communities and thus claiming a special social status as a consequence of his/her mediation.  Brokers can act then both as mediators and bottlenecks, and because they are connected to different sources of knowledge they  can synthesize divergent intellectual positions and capitalize their syntheses as innovations. 

#### Communal View

***

<iframe src="comnty_vnw.html" height="600" width="1100" align="middle" frameBorder="0" scrolling="no"></iframe>


***
