# Chapter-2
第二章算例中，规模为2, 10, 50, 100个产消者社区的相关参数

# 概述
### 本项目是博士论文 _**《智能配电网产消者能量共享优化方法研究》-“第二章 计及信息隐私与交互效率的少迭代优化方法”**_ 中案例研究参数的说明文档。  
> _**two_prosumer.npy**_：包含2个产消者的社区案例研究参数。  
> _**ten_prosumer.npy**_：包含10个产消者的社区案例研究参数。  
> _**fifty_prosumer.npy**_：包含50个产消者的社区案例研究参数。  
> _**hundred_prosumer.npy**_：包含100个产消者的社区案例研究参数。

# 环境要求
>Python 3  
>Numpy  

# 打开方式
### 以 _**two_prosumer.npy**_ 为例，在 Python 中运行以下代码即可打开该文件。  
```Python
import numpy as np
dict_ = np.load('two_prosumer.npy',allow_pickle = True).item()
```

# 参数说明
### 我们的数据以字典（dictionary）的形式构建，不同键（key）的具体含义解释如下：  

>_**'E'**_ : 指代公式中的 _**E**_；  
>_**'Di'**_ : 指代公式中的 _**D<sub>i</sub>**_；  
>_**'Ai'**_ : 指代公式中的 _**A<sub>i</sub>**_；  
>_**'Bi'**_ : 指代公式中的 _**B<sub>i</sub>**_；  
>_**'Qi'**_ : 指代公式中的 _**Q<sub>i</sub>**_；  
>_**'di'**_ : 指代公式中的 _**d<sub>i</sub>**_；   
>_**'ci'**_ : 指代公式中的 _**c<sub>i</sub>**_；
