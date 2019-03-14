# BankersAlgorithm

The Banker algorithm, sometimes referred to as the detection algorithm, is a resource allocation and deadlock avoidance algorithm developed by Edsger Dijkstra that tests for safety by simulating the allocation of predetermined maximum possible amounts of all resources, and then makes an "s-state" check to test for possible deadlock conditions for all other pending activities, before deciding whether allocation should be allowed to continue.
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

For the Banker's algorithm to work, it needs to know three things:

How much of each resource each process could possibly request[MAX]
How much of each resource each process is currently holding[ALLOCATED]
How much of each resource the system currently has available[AVAILABLE]

```
Read about deadlocks,resourse-allocation, Dijkstra Algorithm
```

### Example

Click on the link to view the website.
The basic instructions will be provided there itself for convenience.


```
Total system resources are:
A B C D
6 5 7 6

```

```
Available system resources are:
A B C D
3 1 1 2
```
```
Processes (currently allocated resources):
   A B C D
P1 1 2 2 1
P2 1 0 3 3
P3 1 2 1 0
```
```
Processes (maximum resources):
   A B C D
P1 3 3 2 2
P2 1 2 3 4
P3 1 3 5 0
```
```
Need = maximum resources - currently allocated resources
Processes (possibly needed resources):
   A B C D
P1 2 1 0 1
P2 0 2 0 1
P3 0 1 4 0
```

## References
 Dijkstra, Edsger W. Een algorithme ter voorkoming van de dodelijke omarming (EWD-108) (PDF). E.W. Dijkstra Archive. Center for American History, University of Texas at Austin. (transcription) (in Dutch; An algorithm for the prevention of the deadly embrace)

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


