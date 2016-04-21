### 1.整体介绍
该文件夹下包含的是硕士毕业论文中所用到的用来求解四边形剖分下的多尺度有限元方法(FEM-MsFEM)的主要程序.
整体分成了两个部分:
* **OverSampling**文件夹下包含的是求解超样本基函数的程序.
* **cip_mulbase_J1**文件夹下包含的是FEM-MsFEM方法的主要程序.

### 2. **OverSampling**
该文件夹下包含的程序是用来求解在组合多尺度有限元方法所要用到的超样本基函数信息的.
* main文件夹

  该文件下包含了该程序的主要代码, 主要分成了以下的几个部分:
  * base*.f
  
  这一类的源文件是用来在超样本区域上计算基本的超样本信息.
  * assmble.f
  该文件将超样本区域上的超样本信息限制到标准剖分单元上,然后将线性方程组的刚度矩阵和右端项进行组合.
  * msfem.f
  该文件
* comm文件夹
* dat文件夹
* produceexactsolution文件夹

### 3. **cip_mulbase_J1**
