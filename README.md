# CSCI5611-HW1
<h2>MouseFollow</h2>
<img height=400 width=800 src="/images/mousefollowgif.gif">
<p>No extra credit involved in MouseFollow</p>
<div\>
<h2>Particle System</h2>
<img height=400 width=800 src="/images/particlegif.gif">
<p>No extra credit involved in Particle System</p>
<div\>
<h2>TTCForces</h2>
<img height=400 width=800 src="/images/ttcforcesgif.gif">
<p>No extra credit involved in TTForces</p>
<div\>
<h2>DFS vs BFS searching</h2>
<p>The purpose of the visited and parent lists are to check against cycles as well as keep track what path the search is on. Keeping this path allows the program to print out the solution path when it reaches the solution node.</p>
<p>After converting the graph to the new one, the graph is no longer a tree because certain nodes have more than one parent node. This could potentially lead to cycles and infinite loops. However, the new graph is searchable with BFS and DFS.</p>
<img height=500 width="auto" src="/images/BFS.JPG">
<p>BFS gets the optimal path answer but takes more steps than DFS. There is no cycle in the graph which allows it to still find the optimal path.</p>
<img height=500 width="auto" src="/images/DFS.JPG">
<p>DFS gets the optimal path answer in less steps than BFS. There is no cycle in the graph which allows DFS to find any answer at all. If there was a cycle, it would not be able to find a solution path.</p>
<p>No extra credit involved in BFS and DFS</p>