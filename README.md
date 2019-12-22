# **Hmk5-ADM**
> Last hmk for Adm course
> Group 23
This repository is composed of:
>> 0) this README and a file gitignore.
>> 1) **main.ipynb** where you find all the procedures to solve the hmk.
>> 2) **main.py** that is the same as above but in a python fomrat, easy ot open from an editor and run it.

> 1) for **functionality1** we just performed a bfs that return the graph with the minimum distances from the root.
> 2) for **functionality2** we understood that *we have to find a graph, smartest possible that can connect the nodes that are given(so can meet other nodes)*, and we used a variation, through dijsktra of the Prim's algorithm of mst.
> 3) for **functionality3** we used dijsktra in order to every cople of nodes in the path
> 4) for **functionality4** we controlled all permutations of paths and choosed the minimum, and when the nodes were more than 7 we used a randomization to find samples and provide a local minimum, for sure it will give a good path.

All those functionalities are in the Graph Class and use **oop programming and functional programming**, and are done in relation to the kind of distances selected by the user. <br>
Calling G.GraphandPlot() the user will be able to perform any task requested in the homework.
