# cov19
## 对于数据拟合
找到了中国到6.15的数据，根据传染病模型SIR进行建模。根据武汉的数据确定传播系数和康复率的范围。再利用ode45函数得到数值解，与真实数据一起构造残差平方和。然后使用fmincon函数进行拟合。得到更好的结果。

![image](https://github.com/Latiest/Latiest.github.io/blob/master/images/first.PNG)

## 对于仿真
一开始想用SEIR模型加上元胞自动机，找到一个netlogo的仿真软件非常好用，但是有点简陋。后来听同学说B站up有做过视频并上传源码到了github，就找到代码并进行了一些改动。
