# 条件随机场（CRF）

## 基础

![img](https://pic3.zhimg.com/v2-05542e63ec1938d33e94dd7d7ed4e986_b.jpg)

![preview](https://pic2.zhimg.com/v2-47fee0ce37529374b22101f9d47fd4c1_r.jpg)

![preview](https://pic4.zhimg.com/v2-76ef30f5f3ebeb4fd83d9c5415d5580b_r.jpg)

![preview](https://pic1.zhimg.com/v2-f46d241210baf971e8968bd0ccf058d8_r.jpg)

![preview](https://pic1.zhimg.com/v2-d5cf7a3ebac7a4cd6126c11ae6c73044_r.jpg)

无向图的因子分解例子：

![img](https://pic3.zhimg.com/v2-efbb3f5419ff91c88db9844fe04cb636_b.jpg)

## 条件随机场的定义

![img](https://pic2.zhimg.com/v2-096bfaa482854b7fd4bb753357048921_b.jpg)

## 线性条件随机场

![img](https://pic2.zhimg.com/v2-3e284501e3cae972ec8d3549e3820fa1_b.jpg)

![preview](https://pic3.zhimg.com/v2-e4018eb4ee1ccb10a942525e36aa407a_r.jpg)

### 线性链条件随机场CRF的图结构

![img](https://pic1.zhimg.com/v2-cebd08fab5f567dff1ca16e2d204984c_b.jpg)

### 线性链条件随机场CRF公式

![img](https://pic1.zhimg.com/v2-ee91ebeecd409eb4a33af209fb8b0f18_b.jpg)

#### 特征函数的定义

![preview](https://pic1.zhimg.com/v2-799f58be49406ee7478ed52d94a3f188_r.jpg)

条件随机场简化公式：

![preview](https://pic4.zhimg.com/v2-e0f24d7d3c60c3fb0cfba7f10e3f33b3_r.jpg)

其中
$$
f_k(y,x)代表转移特征和状态特征，w_k代表的是权值
$$

### 条件随机场的例子

![img](https://pic3.zhimg.com/v2-98c85098271f347be65745d6d5b4e8de_b.jpg)

![img](https://pic2.zhimg.com/v2-980fd0c5d7c701e69aa3435f51901cb9_b.jpg)

![img](https://pic2.zhimg.com/v2-980fd0c5d7c701e69aa3435f51901cb9_b.jpg)

## 应用

### 1.中文的分词

![preview](https://pic2.zhimg.com/v2-31b9b12996bef5bfc857eabcc276e899_r.jpg)

#### CRF中文分词的图结构

![preview](https://pic2.zhimg.com/v2-8c7825e6a2a700faf96c7ed2aa1c7ed9_r.jpg)

### 2.命名实体识别

![img](https://pic1.zhimg.com/v2-e6b99a5894e1d65a0b8802ed718b861c_b.jpg)

#### CRF命名实体识别的图结构

![img](https://pic2.zhimg.com/v2-cdacd9ff36747052097e5516360a0155_b.jpg)

### 3.CRF词性的标注

![img](https://pic3.zhimg.com/v2-d6156399374fb6f9f813301559cb3f32_b.jpg)

#### CRF词性标注的图结构

![img](https://pic2.zhimg.com/v2-9d7163ea8fbb8484d1521936fe2ef139_b.jpg)



### 总结

![img](https://pic2.zhimg.com/v2-9d7163ea8fbb8484d1521936fe2ef139_b.jpg)

