# Cache Simulator (CS3339 Homework 3)

## Description
This program simulates a set-associative cache using an LRU replacement policy.  
It reads memory addresses from a file and outputs whether each access is a HIT or MISS.

## How to Compile
g++ cache_sim.cpp -o cache_sim

## How to Run
./cache_sim <num_entries> <associativity> <input_file>

Example:
./cache_sim 4 2 input.txt

## Input Format
A sequence of integer memory addresses separated by spaces.

Example:
1 3 5 1 3 1

## Output
Results are written to: cache_sim_output

Format:
ADDR : HIT  
ADDR : MISS


