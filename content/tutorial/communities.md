+++
title = "Communities View"

date = 2018-09-09T00:00:00
# lastmod = 2019-08-19T00:00:00

draft = false  # Is this a draft? true/false
toc = true  # Show table of contents? true/false
type = "docs"  # Do not modify.

# Add menu entry to sidebar.
linktitle = "Communities"
[menu.tutorial]
  parent = "Horus"
  weight = 5
+++

### Communities

In the community page of [Horus](http://diogenet.ucsd.edu/horus/) it is possible to search for communities of philosophers, friends, and family with the help of different algorithms. A community is a cohesive group of social actors. In the image below, each community is highlighted with different colors. Most interestingly, algorithms find communities that do not overlap with current designations of philosophical schools. This is understandable because algorithms do not identify communities in terms of self-designations such as "followers of Plato." Instead, they consider the actual ties that link the nodes.

<center>
{{< figure library="1" src="figure3.png" >}}
</center>

In [Horus](http://diogenet.ucsd.edu/horus/), we offer seven different algorithms to identify communities. Some of them, for example the *Cluster Louvain* algorithm, identify not only communities but also the ties that cross and connect two different groups. In the communities tab of [Horus](http://diogenet.ucsd.edu/horus/), you can choose between two visualization libraries: *Visnetwork* and *igraph.* *Visnetwork* is dynamic and allows the manipulation of the nodes. *igraph* is static but nevertheless indicates the social territories where communities overlap through the coloring of the adjacent areas.