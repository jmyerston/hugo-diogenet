



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

# Introduction 

Diogenet is a dataset and a series of web applications for the investigation of the impact of the social networks on the emergence of philosophy in ancient Greece.  In contrast to most approaches to the intellectual history of classical antiquity, we do not only focus on philosophers but also on the social ties that linked them. Moreover, we do not limit ourselves to study relations among intellectuals, but also take into consideration family members, lovers, friends, and benefactors. We think that moving away from the conception that fields of knowledge are closed systems allows a better understanding of the social processes that underlie the construction of knowledge in the ancient world.  

An important aspect of the ancient networks was their geographical location, as well as the spatial mobility of some actors who could connect communities across space.  Since in the ancient Mediterranean traveling was central in the production and exchange of ideas, we have included travel itineraries in our dataset.  In our interactive Map, for instance, you can find that thinkers like Pythagoras, Democritus, and Plato undertook long distance journeys. We are particularly interested in the impact  of traveling and intercultural exchange in the formation of schools of thought and the production of new ideas.

The main ancient source that we use to explore such issues is the *Lives of Philosophers* that Diogenes Laertius wrote in the third century CE, about eight hundred years after the appearance of the first philosophers in Asia Minor. In this work, Diogenes reports not only about the theories of  philosophers but also about their lives. Despite his meticulous accounts, however, Diogenes has been much distrusted by modern historians of philosophy. One of the main arguments raised against his work is based on the apparently excessive attention that he paid to matters perceived as irrelevant for the history of ideas. These digressions are, in fact, stories about the family, friends, romantic relations, benefactors, and travels of ancient philosophers. It is precisely this perceived weakness that makes his work a great starting point for the reconstruction of the social networks of the intellectual of ancient Greece.

Currently we offer two interactive tools for the study of the social networks that Diogenes described in the *Lives*; these are [Horus](http://diogenet.ucsd.edu/horus/), a general network visualization tool that creates network visualizations from both socio-centric and ego-centric perspectives, and the Map, a tool for the exploration of the travels of ancient intellectuals.  

To make sense of the visualizations produced by [Horus](http://diogenet.ucsd.edu/horus/) and the Map, some background both in social network theory and the history of ancient Greek philosophy is necessary. In the [bibliography](http://diogenet.ucsd.edu/bibliography/) you can find  listed some introductory references to the subject.

## Network Visualizations

With the help of [Horus](http://diogenet.ucsd.edu/horus/), you can visualize a **global** and **local** view of the networks, as well as search for intellectual communities. Each network that you can study in [Horus](http://diogenet.ucsd.edu/horus/) is built on a specific type of social tie that you can choose from the menu. Exploring each type of tie separately is important because a family network, for instance, is different from a network of friends or peer philosophers. The expectations, themes of conversation, and even patterns of behavior in each network were  articulated differently depending on  the type of social ties through which the actors were intertwined. What Axiothea of Phlius conversed with her father as a daughter was, most likely, not what she discussed with  Plato in the Academy.  

### Global Network View

In the screenshot that you see below, the actors in the network are represented as nodes and the ties which link them as arrows or as simple lines. We call this the **global network** view because it reflects the entire network of teachers and pupils. You can explore this network with [Horus](http://diogenet.ucsd.edu/horus/), which allows many different adjustments.  For example, you can choose one or many social ties, move the nodes, and highlight the most immediate ties of a node.  You can also use your mouse scroll button to zoom in and out of the network.
<center>
{{< figure library="1" src="figure1.png">}}
</center>

### Local Network View

While the global view is important to gain a panorama of the overall structure of the network , the local view allows you to focus on one specific node and its neighbors.[^1] You can explore the local view in [Horus](http://diogenet.ucsd.edu/horus/) by modifying several variables that appear in the left menu. 

<center>
{{< figure library="1" src="figure2.png">}}
</center>

Among the variables you can modify in the local view is *ego*, the focus node whose network you would like to explore. Another important variable is **order**, the distance between *ego* and *alter.* In social network theory, *ego* is the node at the center of analysis, while its neighbors are *alters*.  Higher values in **order** will return more neighbors if the node is not socially isolated. In the screenshot of the local view that you see above, the *ego* is Plato and the **order** set to 2; this means, only individuals who are 1 and 2 steps away from Plato are shown.

### Communities

In the community page of [Horus](http://diogenet.ucsd.edu/horus/) it is possible to search for communities of philosophers, friends, and family with the help of different algorithms. A community is a cohesive group of social actors. In the image below, each community is highlighted with different colors. Most interestingly, algorithms find communities that do not overlap with current designations of philosophical schools. This is understandable because algorithms do not identify communities in terms of self-designations such as "followers of Plato." Instead, they consider the actual ties that link the nodes.

<center>
{{< figure library="1" src="figure3.png" >}}
</center>

In [Horus](http://diogenet.ucsd.edu/horus/), we offer seven different algorithms to identify communities. Some of them, for example the *Cluster Louvain* algorithm, identify not only communities but also the ties that cross and connect two different groups. In the communities tab of [Horus](http://diogenet.ucsd.edu/horus/), you can choose between two visualization libraries: *Visnetwork* and *igraph.* *Visnetwork* is dynamic and allows the manipulation of the nodes. *igraph* is static but nevertheless indicates the social territories where communities overlap through the coloring of the adjacent areas.

[^1]: This could also be called in social networks analysis' jargon the egocentric perspective
