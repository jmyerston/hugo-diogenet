+++
title = "Local Network View"

date = 2018-09-09T00:00:00
# lastmod = 2019-08-19T00:00:00

draft = false  # Is this a draft? true/false
toc = true  # Show table of contents? true/false
type = "docs"  # Do not modify.

# Add menu entry to sidebar.
linktitle = "Local Network"
[menu.tutorial]
  parent = "Horus"
  weight = 4
+++

### Local Network View

While the global view is important to gain a panorama of the overall structure of the network , the local view allows you to focus on one specific node and its neighbors.[^1] You can explore the local view in [Horus](http://diogenet.ucsd.edu/horus/) by modifying several variables that appear in the left menu. 

<center>
{{< figure library="1" src="figure2.png">}}
</center>

Among the variables you can modify in the local view is *ego*, the focus node whose network you would like to explore. Another important variable is **order**, the distance between *ego* and *alter.* In social network theory, *ego* is the node at the center of analysis, while its neighbors are *alters*.  Higher values in **order** will return more neighbors if the node is not socially isolated. In the screenshot of the local view that you see above, the *ego* is Plato and the **order** set to 2; this means, only individuals who are 1 and 2 steps away from Plato are shown.

[^1]: This could also be called in social networks analysis' jargon the egocentric perspective
