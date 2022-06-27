# README模板

## 1. 简介

- 简单的介绍模型，以及模型的主要架构或主要功能，可以在简介的下方直接贴上图片，展示模型结构。

- 论文标题: Data-driven prediction of battery cycle life before capacity degradation 

- 复现所用到的评价指标以及所达到的精度。



## 2. 数据集和复现精度

- 给出本repo中用到的数据集的基本信息，例如数据集大小与数据集格式。格式如下：
  - 数据集大小：关于数据集大小的描述，如类别，数量等等
  - 数据格式：关于数据集格式的说明

- 基于上述数据集，给出论文中精度、参考代码的精度、本repo复现的精度、数据集名称、、模型大小，以表格的形式给出。如果超参数有差别，可以在表格中新增一列备注一下。



## 3. 准备数据与环境

### 3.1 准备环境

- 建议将代码中用到的非python原生的库，都写在requirements.txt中，直接使用`pip install -r requirements.txt`安装依赖即可。

### 3.2 准备数据

- 简单介绍下对数据进行了哪些操作，例如数据预处理、train&test数据集选择等。



## 4. 开始使用

### 4.1 模型训练

- 简单说明一下训练的命令，建议附一些简短的训练日志。

- 可以简要介绍下可配置的超参数以及配置方法。

### 4.2 模型验证

- 在这里简单说明一下验证的命令，需要提供原始数据等内容，并在文档中体现输出结果。



## 5.代码结构与简要说明

### 5.1代码结构

- 列出代码目录结构

```undefined
./repo_template            # 项目文件夹名称，可以修改为自己的文件夹名称
|-- preprocess             # 预处理类文件夹
|   ├── dataset.py         # 数据集代码文件
|-- config                 # 配置类文件夹
|   ├── competition.json   # 项目配置信息文件
|-- tools                  # 工具类文件夹
|   ├── train.py           # 训练代码文件
|   ├── eval.py            # 验证代码文件
|-- scripts                # 脚本类文件夹
|   ├── train.sh           # 训练脚本，提供单机单卡的训练方式即可
|   ├── eval.sh            # 验证脚本，提供单机单卡的验证方式即可
|-- README.md              # 中文用户手册
|-- LICENSE                # LICENSE文件
```

### 5.2代码简要说明

- 说明代码文件中的类以及主要函数功能

```undefined
# 示例
./dataset.py               # 数据集代码文件
|-- class Alg              # 算法类
|   ├── run                # 类主函数，用于外部接收返回结果
|   ├── train_val_split    # 划分train&val数据集
```



## 6. LICENSE

- 本项目的发布受[Apache 2.0 license](https://github.com/thinkenergy/vloong-nature-energy/blob/master/LICENSE)许可认证。



## 7. 参考链接与文献

- github.com

- **[Data-driven prediction of battery cycle life before capacity degradation](https://doi.org/10.1038/s41560-019-0356-8)**

  