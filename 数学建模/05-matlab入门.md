## 生成矩阵

### 直接法

```matlab
a = [1, 2, 3; 4, 5, 6; 7, 8, 9];   % 三行三列的矩阵
```

### 冒泡一维矩阵

a = [开始] : [步长] : [结束]，若步长为1则步长可以省略。

```matlab
b = 1:1:10;  % [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
b = 1:10;    % 与上一个式子相同
```

### 特殊矩阵

```matlab
% 第一个参数是行，第二个参数是列
z = zeros(1, 4);  % 生成一行4列的全为0的矩阵
o = ones(4, 1);   % 生成4行一列全为1的矩阵
% nxn
e = eye(4);  % 生成主对角线都是1，其他地方都是0的4x4矩阵
r = rand(4);    % 生成4x4在0~1上随机分布的随机数矩阵
rn = randn(4);   % 生成4x4的以0为均值的高斯分布
```

