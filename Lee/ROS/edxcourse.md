### There are two fundamental concepts in ROS, which are: Nodes and Topics

- Nodes:  
These are software processes that do 'stuff' (e.g. process data, command hardware, execute algorithms). Nodes provide modularity to robotic projects that use ROS. They are often written in C++ or Python. In this course, we will use Python to write them. ROS Noetic compatible with Python 3.x.

- Topics:  
Transport information between nodes, in the form of messages.

For example, a sensor, processes information and then provides data, is a node as it does not transport it between nodes.



### There are three main ways to inspect a ROS node:

Simply list all currently running nodes in the terminal:  
```
rosnode list
```
Make a visual graph of all running nodes and their connections:  
```
rqt_graph
```
List information about a specific node in the terminal:  
```
rosnode info <node_name>
```
