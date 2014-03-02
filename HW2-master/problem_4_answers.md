<p>
Here I briefly describe my Problem 4 implementation:
</p>

<p
First off, you'll note that I used some of the example template in simple_graph, along with my Problem 2 implementation. The few other tricks I learned have urls where I got them from. Now, onto the visualization.
</p>

<p>
My idea, discussed with my group, was to have nodes represent unique users instead of (unique) commits. In this regard, this is a people oriented visualization, not a code one, made to see collaboration and/or productivity. This would be useful for someone who is generally in charge of a project's outcome but who does not run it day to day.
</p>

</p>
Each unique user is a node. Hover over node, and you get the user name with the number of commits. (I tried to display the number permanently in the center of the node but was unable to do so, due to some sort of conceptual glitch I had with not being able to grab the x&y positions even though I could locate them in the JavaScript console; they returned undefined.)
</p>

<p>
The next task was going to be showing the relative collaboration between each person. I was going to have the link thickness be in accordance with # of collaborations between the two people (i.e. the nodes), BUT it turned out that since I'm just looking at the master branch, everyone just connects to Mike Bostock (who created d3). So weighting the relative number of connections isn't super useful.
</p>

<p>
What I did instead is show how many more commits Mike has, and Jason (who co-wrote), than other contributors to the master branch, and then have the alternative visual layout be a random graph display, where you just had the size of the node be how many commits.
</p>

 
