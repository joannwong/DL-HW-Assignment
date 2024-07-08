# dl_hwassignment
AI6103 Deep Learning Homework Assignment

In this homework assignment, I investigated the effects of hyperparameters such as initial learning rate, learning rate schedule, weight decay, and data augmentation on deep neural networks.
I used the MobileNet network and the CIFAR-100 dataset for this assignment. 

Data pre-processing steps:
- Train/ Val split (80/20)
- Data augmentation: standard random horizontal flip and random cropping
  
After data pre-processing, I performed the following experiments: 
1) Investigated different learning rates: LR = 0.5, 0.05, and 0.01
2) LR = 0.05, epochs = 300
3) Learning rate schedule: LR = 0.05, epochs = 300, with cosine annealing
4) Weight decay: LR = 0.05, epochs = 300, with cosine annealing, weight decay coefficient = λ = 5 × 10−4
5) Weight decay: LR = 0.05, epochs = 300, with cosine annealing, weight decay coefficient = λ = 1 × 10−4
6) Data Augmentation: LR = 0.05, epochs = 300, with cosine annealing, weight decay coefficient = λ = 5 × 10−4, mixup data augmentation
7) Test set 

