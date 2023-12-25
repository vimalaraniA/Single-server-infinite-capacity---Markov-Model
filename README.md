# Single server with infinite capacity (M/M/1):(oo/FIFO)
```
DEVELOPED BY:VIMALA RANI A
REG NO:212223040240
```
## Aim :
To find (a) average number of materials in the system (b) average number of materials in the conveyor (c) waiting time of each material in the system (d) waiting time of each material in the conveyor, if the arrival  of materials follow poisson process with the mean interval time 12 seconds, serivice time of lathe machine follows exponential distribution with mean serice time 1 second and average service time of robot is 7seconds.

## Software required :
Visual components and Python

## Theory:
Queuing are the most frequently encountered problems in everyday life. For example, queue at a cafeteria, library, bank, etc. Common to all of these cases are the arrivals of objects requiring service and the attendant delays when the service mechanism is busy. Waiting lines cannot be eliminated completely, but suitable techniques can be used to reduce the waiting time of an object in the system. A long waiting line may result in loss of customers to an organization. Waiting time can be reduced by providing additional service facilities, but it may result in an increase in the idle time of the service mechanism.

![image](1.png)

This is a queuing model in which the arrival is Marcovian and departure distribution is also Marcovian,number of server is one and size of the queue is also Marcovian,no.of server is one and size of the queue is infinite and service discipline is 1st come 1st serve(FCFS) and the calling source is also finite.

## Procedure :

![imAGE](2.png)



## Experiment:
 ![PRO 4 EXPT](https://github.com/vimalaraniA/Single-server-infinite-capacity---Markov-Model/assets/150007791/4eaeb886-ab00-494c-8d4b-46d9025cbc83)

## Program
![image](https://github.com/ramjan1729/Single-server-infinite-capacity---Markov-Model/assets/103921593/5f1fd58d-5929-4c51-89ea-4cef009e5bad)

## Output :
```
---------------------------------------------------------------------------------------
Enter the mean inter arrival time of objects from feeder(in secs):12
Enter the mean inter service time of Lathe Machines(in secs):1
Enter the Additional time taken for the Robot(in secs):7
------------------------------------------------------------------------
Single server with Infinite capacity - (M/M/1):(oo/FIFO)
------------------------------------------------------------------------
The mean arrival rate per second : 0.08
The mean service rate per second : 0.12
Average number of objects in the system : 2.00
Average number of objects in the conveyor : 1.33
Average waiting time of an object in the system : 24.00 secs
Average waiting time of an object in the conveyor : 16.00 secs
Probability that the system is busy : 0.67
Probability that the system is empty : 0.33
----------------------------------------------------------------------
```

## Result :
The average number of material in the sysytem and in the conveyor and waiting time are successfully found.


