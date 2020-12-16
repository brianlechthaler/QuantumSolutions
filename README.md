# QuantumSolutions
Solving real-world problems with NISQ-era quantum computing hardware.

## Contents
* Traveling Salesperson:
  * Designed for D-Wave Quantum Annealers. Uses the new (at time of writing) D-Wave plugin for Qiskit. 7 cities, 10000 shots, and one perfect solution out of 562949953421312 possibilities -- all in milliseconds.
  * https://github.com/brianlechthaler/QuantumSolutions/blob/origin/TravelingSalesperson.ipynb
* Graph Partitioning:
  * Designed for D-Wave Quantum Annealers running on AWS Braket. You'll need to set up Braket on AWS. 
  * Splitting a graph based on relationships of graphed entities.
  * https://github.com/brianlechthaler/QuantumSolutions/blob/origin/GraphPartitioning.ipynb
* The Knapsack Problem:
  * Designed for D-Wave quantum annealers, run and tested on D-Wave Advantage System version 1.1 on AWS Braket. 
  * scalable: choose from a list of datasets and input any value for weight, that's all you need to do
  * partly based on https://github.com/dwave-examples/knapsack
  * https://github.com/brianlechthaler/QuantumSolutions/blob/origin/GraphPartitioning.ipynb
