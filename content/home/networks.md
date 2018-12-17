+++
#title = "Introdution"
#date = {{ .Date }}
draft = false
weight = 3

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





##  Networks Visualization

orem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Fermentum leo vel orci porta. Eget sit amet tellus cras adipiscing enim eu. Risus nec feugiat in fermentum posuere urna nec. Non blandit massa enim nec dui nunc mattis enim ut. Quis blandit turpis cursus in hac habitasse platea. Sed adipiscing diam donec adipiscing tristique risus nec feugiat. Quam vulputate dignissim suspendisse in est ante in. Laoreet suspendisse interdum consectetur libero id faucibus. Turpis egestas maecenas pharetra convallis posuere morbi leo urna. Amet commodo nulla facilisi nullam vehicula ipsum a arcu cursus. Mauris commodo quis imperdiet massa tincidunt. Eget dolor morbi non arcu risus quis varius quam. Imperdiet nulla malesuada pellentesque elit eget. Aliquet bibendum enim facilisis gravida neque convallis a cras semper.

***
<center> <h3> <i> Global View </i> </h3> </center>
<iframe src="http://diogenes.ucsd.edu/network" height="900" width="1250" align="middle" frameBorder="0">  </iframe>





## Local Networks

In this site, you can access the Diogenet Network from different perspectives or views.  While the *Global View* of the network is important to gain a perspective of the overall extension of the structure, the *Local View* allows to focus on one specific node (currenly only human actors) and their neighbors.  The variable *Order* of the *Local View* determines the distance between *Ego* and its neighbors. Setting *Order* to 1 will return only the node choosen in the pop-up menu *Node*; setting it to 2 will return *Ego* and its neighbors at 2 steps from *Ego*.

***
### Local View
***
<iframe src="http://diogenes.ucsd.edu/egograph" height="875" width="1250" align="middle" frameBorder="0" scrolling="no"> </iframe>

## Communities

With the help of different algorithms and the use of the library igraph, it is possible to identify **communities** in Diogenet. A community is a cohesive group of social actors. We offer here three different algorithms you can choose from. Some of them, for example, the **Cluster Louvain** algorithm not only identifies communities but the bridges that establish a path of communication between them.  In social network analysis,  a **bridge** is a tie that connects two components or communities. In the present visualization of communities bridges are highlighted with red ties.

At the end of each bridge, there are nodes that control the flow of ideas and information in general between communities. Those nodes are brokers of special importance for understanding the structure of the network. A broker can act as a facilitator between two or more communities of intellectuals but can also capitalize such a position by restricting the flow of communication between communities and thus claiming a special social status as a consequence of his/her mediation.  Brokers can act then both as mediators and bottlenecks, and because they are connected to different sources of knowledge they  can synthesize divergent intellectual positions and capitalize their syntheses as innovations. 

<iframe src="http://diogenes.ucsd.edu/community" height="950" width="1250" align="middle" frameBorder="0" scrolling="no"></iframe>

