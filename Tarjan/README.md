# Tarjan (March 2020)

## About
This program predicts every students maximum grades according to each individuals network(sub-network). Every input network was represented as a graph in order to simplify the problem and the connections each student had (sub-networks) were represented as strongly connected components. This prediction consists in giving each student the maximum grade in his/hers connections. 

## Requirements
C++ compiler 

## Run by typing:
```
g++ project.cpp -o project
./project < {input file}
```

Input file can be generated from testGenerator.cc
```
g++ testGenerator.cc -o generator
./generator #S #C #SubN #m #M seed > {input file}
```

#S: number of students
#C: number of connections between students
#SubN: number of sub-networks
#m: minimum number of students in each sub-network(optional, default: 1)
#M: maximum number of students in each sub-network (optional, default: 10)
seed: seed for the random generator (optional, default: 0)

This project was made with my friend [@Mokita-J](https://github.com/Mokita-J). Go check her page for more insteresting projects! :wink:
