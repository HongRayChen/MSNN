
# Multi-scale topology optimization with Neural Networks 

[Paper link](https://arxiv.org/abs/2404.08708)

## Abstract
A long-standing challenge in multi-scale structural design is ensuring proper connectivity between the constituent cells as each cell is being optimized toward its theoretical performance limit. We propose a new method for multi-scale topology optimization that seamlessly ensures compatibility across neighboring microstructure cells without the need for a catalog of unit cells and associated connectivity rules. Our approach consists of a topology neural network that encodes each cell's microstructure as well as the distribution of the optimized cells within the design domain as a continuous and differentiable density field. Each cell is optimized based on a prescribed elasticity tensor that also accommodates in-plane rotations. The neural network takes as input the local coordinates within a cell to represent the density distribution within a cell, as well as the global coordinates of each cell to generate spatially varying microstructure cells. As such, our approach models an n-dimensional multi-scale optimization problem as a 2n-dimensional inverse homogenization problem using neural networks. During the inverse homogenization of each unit cell, we extend the boundary of each cell by scaling the input coordinates such that the boundaries of neighboring cells are blended and thus jointly optimized. This enables inverse homogenization of the cells to be consistently connected without introducing discontinuities at the cell boundaries. We demonstrate our method through the design and optimization of several graded multi-scale structures. 

![image](https://github.com/user-attachments/assets/d8023ce9-6da6-470c-a957-178584d763a3)

![image](https://github.com/user-attachments/assets/a1a3e42b-6b43-4db9-b86b-062b5f679c2c)
