# 开发者：
HUST MSE ddc ZR_heihei; 
HUST MSE ddc CH_panpan
# mag_cuboid
 a gui or app based matlab to calculate B  force stiffness  计算立方磁体的计算
 
### 仅仅在matlab appdesigner中设计了更易于使用的gui界面，磁体计算的源代码全部来自于
Title: ‘MAGCODE: framework of models for calculating magnetic fields and interactions’

Author: William S. P. Robertson 

https://github.com/AUMAG/magcode 

DOI for the repository: 10.5281/zenodo.1491206 
### 磁体可视化部分代码同样来自于 William S. P. Robertson 
https://github.com/wspr/matlab-euler-angles
感谢 Robertson ！！
### 使用前请先将上述代码库中的相关函数添加入matlab路径 

可直接安装.exe文件，可将依赖的函数一同获得。
### 允许通过代码产生大规模磁体阵列
1. 打开gui，先使用保存一个.mat数据文件；
2. 编辑.mat数据文件，使用magnetdefine.m函数创建磁体数据结构体，并添加到cuboid_cell中，第一列为定子，第二列为动子。
