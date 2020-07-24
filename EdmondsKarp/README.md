# Edmonds Karp (May 2020)

## About
This program calculates the maximum number of citizens that can reach a supermarket without coming into contact with another citizen. All of the citizens and supermarkets are randomly located in different cells of a grid. To simplify this problem, the grid was represented as a weighted graph, with each edge having a capacity of 1, the citizens were all connected to the source vertex and the supermarkets to the sink vertex. Thus, making this a max flow problem, which was solved using Edmonds Karp algorithm. 

## Requirements
C++ compiler  <br />
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
