# Solution and tutorial
#### Assignment One for class cs231n in Standford
### 斯坦福cs231n计算机视觉课程作业#1 
## Table (目录)
- [1.Instruction of this assignment (课业导引)](#Instruction)
- [2.Video record of this class (课程视频)](#Video)
- [3.Tutorial to start (如何安装和开始)](#Tutorial)
- [4.Solution in Detail (方案详解)](#DetailedSolution)
<a name = "Instruction"></a>
## 1.Instruction of this assignment (课业导引) 
### Goals
In this assignment you will practice putting together a simple image classification pipeline based on the k-Nearest Neighbor or the SVM/Softmax classifier. The goals of this assignment are as follows:
- Understand the basic Image Classification pipeline and the data-driven approach (train/predict stages) (了解 __图像分类__ 和 __数据驱动算法__ 的大致过程)
- Understand the train/val/test splits and the use of validation data for hyperparameter tuning. (理解 __数据集分割__ 和利用验证集进行 __超参数调优__ )
- Develop proficiency in writing efficient vectorized code with numpy (利用numpy矩阵化运算 __提升性能__ )
- Implement and apply a k-Nearest Neighbor (kNN) classifier (实现 __kNN分类器__ )
- Implement and apply a Multiclass Support Vector Machine (SVM) classifier (实现 __SVM分类器__ )
- Implement and apply a Softmax classifier (实现 __SoftMax分类器__ ) 
- Implement and apply a Two layer neural network classifier (实现 __两层神经网络分类器__ )
- Understand the differences and tradeoffs between these classifiers (理解 __各个分类器__ 的 __不同和优劣之处__ )
- Get a basic understanding of performance improvements from using higher-level representations as opposed to raw pixels, e.g. color histograms, Histogram of Gradient (HOG) features, etc. (对于诸如 __HOG__ 等不同于单位像素的 __高级表达形式__ 对于表现的提升做一个初步的了解)
<a name = "Video"></a>
## 2.Video record of this class (课程视频)
- [Lecture2: Data-driven approach, kNN, Linear Classification 1](https://www.youtube.com/watch?v=8inugqHkfvE&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=2)
- [Lecture3: Linear Classification2, Optimization](https://www.youtube.com/watch?v=qlLChbHhbg4&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=3)
- [Lecture4: Backpropagation, Neural Networks 1](https://www.youtube.com/watch?v=i94OvYb6noo&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=4)
<a name = "Tutorial"></a>
## 3.Tutorial to start (如何安装和开始) 
### How to set up Local Development
___Download___. Starter code containing jupyter notebooks can be downloaded [here](https://cs231n.github.io/assignments/2020/assignment1_jupyter.zip).       
___Install Packages___. Once you have the starter code, activate your environment (the one you installed in the Software Setup page) and run (运行脚本安装运行环境,强烈推荐[此教程方法](https://denrydu.github.io/content.html?id=3))
```
pip install -r requirements.txt.
```
如果需要在conda虚拟环境中安装，则运行以下命令(具体见上一段链接):    
```
python -m pip install -r requirements.txt.
```     
___Download CIFAR-10___. Next, you will need to download the CIFAR-10 dataset. Run the following from the assignment1 directory: (运行脚本下载cifar-10数据集)
```
cd cs231n/datasets
./get_datasets.sh
```
___Start Jupyter Server___. After you have the CIFAR-10 data, you should start the Jupyter server from the assignment1 directory by executing jupyter notebook in your terminal.
```
```
<a name = "DetailedSolution"></a>
## 4.Solution in Detail (方案详解) 
[Unfinished, please wait...](#)
***
Details about this assignment can be found [on the course webpage](http://cs231n.github.io/), under Assignment #1 of Spring 2019.
