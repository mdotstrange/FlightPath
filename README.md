# FlightPath
A poor mans flight "pathfinding" task for Behavior Designer- it moves to the target using the Rigidbody- casts to find
obstacles and tries to move around them- if it gets stuck it gets the nearest Navmesh SURFACE underneath it and moves to that point
then it tries to go to the target on the navmesh for a few seconds then it flies again. Make sure your NavMeshAgent offset is high enough so that when it switches to navmesh move it still appears to be off the ground.

//REQUIRES Dotween(free), More Effective Coroutines(free) and the NavMeshSurface components though it would be easy to switch it to using the old NavMesh system.

![Example gif](/Liced1.gif)

Requires a Rigidbody with these settings recommended
![Rb settings](/rb.png)

Example tree of useage in this gif- where it seeks the target then stops and looks at it
![Example tree](/extree.png)

Task Ui
![Task Ui](/ui.png)
