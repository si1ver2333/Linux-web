## 第1章 极限与连续

#### 1.1 数列的极限
- **定义**：数列 \(\{a_n\}\) 的极限 \(A\) 满足对任意的 \(\epsilon > 0\)，存在一个正整数 \(N\)，使得当 \(n > N\) 时，\(|a_n - A| < \epsilon\)。
- **性质**：唯一性、有界性、四则运算。

#### 1.2 函数的极限
- **ε-δ定义**：函数 \(f(x)\) 在点 \(x=a\) 处的极限 \(L\) 满足对任意的 \(\epsilon > 0\)，存在 \(\delta > 0\)，使得当 \(0 < |x - a| < \delta\) 时，\(|f(x) - L| < \epsilon\)。

#### 1.3 连续性
- **定义**：函数 \(f(x)\) 在点 \(x=a\) 处连续当且仅当 \(\lim_{x \to a} f(x) = f(a)\)。
- **性质**：连续函数的运算、闭区间上连续函数的性质（最大值最小值定理、介值定理）。

## 第2章 导数与微分

#### 2.1 导数的定义与计算
- **定义**：函数 \(f(x)\) 在点 \(x=a\) 处的导数定义为 \(f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}\)。
- **基本导数公式**：幂函数、指数函数、对数函数、三角函数等的导数。

#### 2.2 导数的应用
- **函数的单调性与极值**：通过导数判断函数的单调性和极值点。
- **凹凸性与拐点**：通过二阶导数判断函数的凹凸性和拐点。
- **曲线的切线和法线**。

## 第3章 不定积分

#### 3.1 不定积分的概念与性质
- **定义**：函数 \(F(x)\) 是 \(f(x)\) 的一个原函数，则不定积分表示为 \(\int f(x) \, dx = F(x) + C\)。
- **基本积分公式**：常见函数的积分。

#### 3.2 积分方法
- **换元法**：利用变量替换简化积分。
- **分部积分法**：\(\int u \, dv = uv - \int v \, du\)。

## 第4章 定积分

#### 4.1 定积分的定义与性质
- **定义**：分割区间求和极限定义定积分 \(\int_a^b f(x) \, dx\)。
- **基本性质**：线性、区间分割。

#### 4.2 定积分的计算
- **牛顿-莱布尼茨公式**：\(\int_a^b f(x) \, dx = F(b) - F(a)\)。
- **分部积分法、换元积分法**。

## 第5章 微分方程

#### 5.1 一阶微分方程
- **分离变量法**：将方程写成 \(f(y) \, dy = g(x) \, dx\) 形式并积分。
- **线性微分方程**：一阶线性微分方程 \(\frac{dy}{dx} + P(x)y = Q(x)\) 的通解。

#### 5.2 高阶微分方程
- **齐次与非齐次线性微分方程**。
- **特征方程法**：求解形如 \(a_n y^{(n)} + a_{n-1} y^{(n-1)} + \cdots + a_0 y = 0\) 的齐次线性微分方程。

## 第6章 向量代数与空间解析几何

#### 6.1 向量代数
- **向量的运算**：加法、减法、数乘。
- **数量积与向量积**：点积和叉积的定义及几何意义。

#### 6.2 空间解析几何
- **直线与平面方程**：直线的参数方程、平面的法向量方程。
- **二次曲面**：椭圆、抛物面、双曲面等。

## 第7章 多元函数微积分

#### 7.1 多元函数的极限与连续
- **定义**：多元函数极限的 \(\epsilon-\delta\) 定义。
- **性质**：连续、多元函数的四则运算。

#### 7.2 偏导数与全微分
- **偏导数**：一阶偏导数、混合偏导数。
- **全微分**：全微分的定义及应用。

#### 7.3 多重积分
- **二重积分**：直角坐标系和极坐标下的二重积分。
- **三重积分**：直角坐标系和柱坐标、球坐标下的三重积分。

## 第8章 向量分析

#### 8.1 向量场与标量场
- **基本概念**：标量场和向量场的定义。
  
#### 8.2 线积分与曲面积分
- **线积分**：对弧长和对坐标的线积分。
- **曲面积分**：对面积和对坐标的曲面积分。

#### 8.3 格林公式、高斯定理与斯托克斯定理
- **格林公式**：平面上的曲线积分与区域积分的关系。
- **高斯定理**：三重积分与曲面积分的关系。
- **斯托克斯定理**：曲面积分与线积分的关系。