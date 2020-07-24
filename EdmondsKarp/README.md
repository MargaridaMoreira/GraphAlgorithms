# Edmonds Karp (May 2020)

## About
This program predicts every students maximum grades according to each individuals network(sub-network). Every input network was represented as a graph in order to simplify the problem and the connections each student had (sub-networks) were represented as strongly connected components. This prediction consists in giving each student the maximum grade in his/hers connections. 

## Requirements
C++ compiler 
Python 2.7+


## Run by typing:
```
g++ project.cpp -o project
./project < {input file}
```

Input file can be generated from testGenerator.py
Example:
```
python testGenerator.py -n 10 -m 10 -s 5 -c 5 -N 20 -M 20 -S 10 -C 10 -Z 6 > {input file}
```

- -n: minimum number of streets (default:1)
- -m: minimum number of avenues (default:1)
- -s: minimum number of supermarkets (default:1)
- -c: minimum number of houses (default:1)
- -N: maximum number of streets (default:1)
- -M: maximum number of avenues (default:1)
- -S: maximum number of supermarkets (default:1)
- -C: maximum number of houses (default:1)
- -Z: seed for the random generator(default:None)

This project was made with my friend [@Mokita-J](https://github.com/Mokita-J). Go check her page for more interesting projects! :wink:
