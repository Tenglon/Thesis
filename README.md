In this assignment, you are going to implement star topology and mesh topology with UDP/TCP and dynamic routing.  

## 1. Star Topology 

Consider a small network with five nodes 0, 1, 2, 3, and 4, forming a star topology as shown below figure. The node 4 is at the center. Node 0 uses a TCP connection, which transmits FTP packets to node 3 (a TCP sink) through the node 4. Node 1 is another traffic source, and uses UDP as transport layer protocol and sends CBR packets to node 2 through node 4. The duration of the simulation time is 10 seconds. Write a Tcl script to simulate the said scenario. You can assume that the link parameters are: Bandwidht 1Mb, Delay 10ms and Queue type DropTail 

![star](star.png)

## 2. Mesh Topology 

Consider a network with six nodes 0, 1, 2, 3, 4 and 5 forming a mesh topology as shown in the below figure. Node 1 is a TCP source, which transmits FTP packets to node 4 (a TCP sink). Node 0 is another traffic UDP source, and sends CBR packets to node 5. The duration of the simulation time is 10 seconds. Assume that at time 2 seconds the link between node 1 and node 4 fails. Write a Tcl script to simulate the mesh network with the dynamic distance vector routing protocol. Run the simulations and verify in NAM that the above network scenarios indeed generated. You can assume that the link parameters are: Bandwidht 1Mb, Delay 10ms and Queue type DropTail

![mesh](mesh.png)

## Tasks
* Implement Star topology in star.tcl file

* Implement Mesh topology in mesh.tcl file

* For Star topology, print the snapshot of your NAM file in star.md. The NAM file should be your-name.NAM

* For Mesh topology, print the snapshot of your NAM file in mesh.md. The NAM file should be your-name.NAM

* Your NAM output should be similar as given in the original file star.md and mesh.md

## Evaluation
Your assignment will be graded according to the following criteria:

* 40+40 points for the correct implementation of Star + Mesh.
* 10+10 points for the correct NAM output of Star and Mesh.

