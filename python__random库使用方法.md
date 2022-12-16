# 第一步

引入random函数库

import random

## 常用用法

**1.random.seed(a=None)**
**Python中产生随机数使用随机数种子来产生 （只要种子相同，产生的随机序列，无论是每一个数，还是数与数之间的关系都是确定的，所以随机数种子确定了随机序列的产生.**

**2.random.random()**
**生成一个[0.0,1.0)之间的随机小数.**

**3.random.randint(a,b)#此处包含b**
**生成一个[a,b]之间的随机整数.**

**4.random.randrange(m,n,k)<u>k为步长</u>**

**生成一个[m,n)之间以k(默认为1)为步长的随机整数.**

**5.random.uniform(a,b)**
**生成一个[a,b]之间的随机小数.**

**6.random.choice(seq)**
**从序列中随机选择一个元素**

**7.random.shuffle(seq)**
**将序列seq中元素随机排列,返回打乱后的序列**

**8.random.sample(pop, k)**

**从pop中选取k个元素，以列表类型返回（不改变原列表）；pop取序列类型，k取整数：代表选取个数**

```python
print(random.sample(list, 3))
```