# 项目

基于tflean实现的kaggle猫狗图片分类

## 说明

### 环境配置

```html
电脑环境：windows10

python3.6.5

第三方库：requirements.txt
```

### 数据集

[沣云猫狗识别比赛](https://club.fenghub.com/views/activity-detail.html?activityId=_73b3947c81554b11b0c04ee86eda8c07) 

对于此次比赛，官方参考Kaggle比赛项目：https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition

- 数据集为：25000张猫狗数据
- 测试集为：12500张猫狗数据

沣云官方与Kaggle提供的数据集是一样的，但是测试集是隐藏的，最终以Excel形式提交即可。

### 仓库

本仓库包括以下：

- `requirements.txt`：第三方库；
- `code`：原始代码，需要进行预训练；
- `final_code`：我训练好的模型，直接进行数据集的测试；

> 大家根据自己需求自取不同代码即可！

## 使用

配置相应环境：
```python
pip install -r requirements.txt
```

运行项目：
```python
python main.py
```

## 结果

<center><img src="https://s1.ax1x.com/2020/08/08/aIdNpq.png" alt="aIdNpq.png" border="0" /></center>

