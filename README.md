# Smart Traffic Management System
This Project presents a solution to deal with traffic congestion in metropolitan cities and presents a central traffic control system which runs on a pretty simple algorithm.
Our product would include the entire mechanism of detection of congestion and increasing the red light duration of traffic signals in the crossings.
### Directions to use this repo:
   1.Install all the python dependencies by running **pip install -r requirements.txt**\
   2.Run the command **python main.py**\
   3.When the login page opens, enter name=admin
   4.The ui is up and running....
## How it Works
Each traffic crossing in a city would fall on a node, if for example we are constantly keeping a  graph (road network) under surveillance then 9 images would come from these crossings at regular intervals of time (for nodes=9).These 9 images are fed into a system which uses **state of the art computer vision to determine the level of congestion** in these crossings by various parameters like count of heavy vehicles. Now if for example we get crossing denoted by (1,1) as congested then the corresponding red light duration in the neighboring junctions increases and this inturn reduces the intake of vehicles in the congested junction and allows the vehicles in the congested junction some time to disperse.


   ![](read.PNG)



## Technologies Used

1.YOLO Version3 for Object Detection

2.Here Maps API

3.Tkinter(Python) for UI

