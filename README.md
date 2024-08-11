# Supply Chain Optimization using MLP Optimizers

Inspired by the hackathon organized by Shell and recent discussion in LinkedIn, I am sharing my experiment of "hacking" MLP (multi-layer perceptron) optimizers such as from Tensorflow Keras framework to solve a discrete optimization problem for supply chain fleet management. It is widely believed that MLP optimizers only works for continous problem, but I managed to get it work for discrete problem and give quite satisfactory result. 

The implementation is written in Keras. Data and notebook can be found in this repo. 

### Result using MLP optimizers with a cost function without constraint
![image](https://github.com/user-attachments/assets/4c1cf2d3-f79b-4780-bbc8-27d585a56a36)

### Result using MLP optimizers with a cost function with constraint
![image](https://github.com/user-attachments/assets/4c1cf2d3-f79b-4780-bbc8-27d585a56a36)
