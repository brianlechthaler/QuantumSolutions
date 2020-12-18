# QuantumSolutions
Solving real-world problems with NISQ-era quantum computing hardware. 

## Getting Started
On a Linux machine, make sure you have git and Python 3 Virtualenv installed, then in a terminal window type:
1) `git clone https://github.com/brianlechthaler/QuantumSolutions && cd QuantumSolutions` (hit enter)
2) `virtualenv venv && . venv/bin/activate` (hit enter)
3) `pip install -Ur requirements.txt` (hit enter)
4) `jupyter lab` (hit enter)
At this point, if all goes right a browser window should open up and connect to Jupyter Lab hosted locally on your machine. On the left-hand side you should see a list of files, containing the examples listed in the Contents section of this README.md. Double-click any one you'd like, follow any instructions included with the notebook, and click the Kernel dropdown at the top of the page. In the dropdown, there's an item called Restart Kernel and Run All -- click this and confirm any dialog asking you if you are sure you want to do this. If you are authenticated to the target platform of the notebook you're looking at, and followed all of the steps mentioned in the notebook to run cells, everything should work without error.

## Important Note for AWS Braket
Remember to run these notebooks from an environment that has access to your AWS account's Braket resources. If you have not already, sign into your AWS console with the proper permissions and complete the Braket onboarding.

## Contents
* Traveling Salesperson:
  * Designed for D-Wave Quantum Annealers. Uses the new (at time of writing) D-Wave plugin for Qiskit. 7 cities, 10000 shots, and one perfect solution out of 562949953421312 possibilities -- all in milliseconds.
  * https://github.com/brianlechthaler/QuantumSolutions/blob/origin/TravelingSalesperson.ipynb
* Graph Partitioning:
  * Designed for D-Wave Quantum Annealers running on AWS Braket. You'll need to set up Braket on AWS. 
  * Splitting a graph based on relationships of graphed entities.
  * https://github.com/brianlechthaler/QuantumSolutions/blob/origin/GraphPartitioning.ipynb
* The Knapsack Problem v3.0.1:
  * Designed for D-Wave quantum annealers, run and tested on D-Wave Advantage System version 1.1 on AWS Braket. 
  * scalable: choose from a list of datasets and input any value for weight, that's all you need to do
  * partly based on https://github.com/dwave-examples/knapsack
  * https://github.com/brianlechthaler/QuantumSolutions/blob/origin/KnapsackProblem.ipynb
