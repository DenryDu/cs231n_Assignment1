# Assignment for class cs231n in Standford
## 斯坦福cs231n计算机视觉课程作业1 
## Table (目录)
- [1.Instruction of this assignment (课业导引)](#Instruction)
- [2.Tutorial to start (如何安装和开始)](#Tutorial)
- [3.Solution in Detail (方案详解)](#DetailedSolution)
## 1.Instruction of this assignment (课业导引) <a name = "Instruction"></a>
### Goals
In this assignment you will practice putting together a simple image classification pipeline based on the k-Nearest Neighbor or the SVM/Softmax classifier. The goals of this assignment are as follows:
- Understand the basic Image Classification pipeline and the data-driven approach (train/predict stages)
- Understand the train/val/test splits and the use of validation data for hyperparameter tuning.
- Develop proficiency in writing efficient vectorized code with numpy
- Implement and apply a k-Nearest Neighbor (kNN) classifier
- Implement and apply a Multiclass Support Vector Machine (SVM) classifier
- Implement and apply a Softmax classifier
- Implement and apply a Two layer neural network classifier
- Understand the differences and tradeoffs between these classifiers
- Get a basic understanding of performance improvements from using higher-level representations as opposed to raw pixels, e.g. color histograms, Histogram of Gradient (HOG) features, etc.
## 2.Tutorial to start (如何安装和开始) <a name = "Tutorial"></a>
### How to set up Local Development
___Download___. Starter code containing jupyter notebooks can be downloaded [here](https://cs231n.github.io/assignments/2020/assignment1_jupyter.zip).

___Install Packages___. Once you have the starter code, activate your environment (the one you installed in the Software Setup page) and run 
```
pip install -r requirements.txt.
```

___Download CIFAR-10___. Next, you will need to download the CIFAR-10 dataset. Run the following from the assignment1 directory:
```
cd cs231n/datasets
./get_datasets.sh
```
___Start Jupyter Server___. After you have the CIFAR-10 data, you should start the Jupyter server from the assignment1 directory by executing jupyter notebook in your terminal.
```
```
## 3.Solution in Detail (方案详解) <a name = "DetailedSolution"></a>

***
Details about this assignment can be found [on the course webpage](http://cs231n.github.io/), under Assignment #1 of Spring 2019.
