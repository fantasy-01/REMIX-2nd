# 1.1 （疑似是）高中知识的接续

> 目前为止好像还没什么知识壁垒（指微积分擦及格线飘过仍然头铁直接看线代了），想了想践行费曼学习法效果比较好还是写下来好了

- 介绍了向量组合$v+w$ 以及线性组合$cv+dw$ .

###### 并非$new ones$：
实际上$V=\begin{bmatrix} 1 \\ 1 \\ -1 \end{bmatrix}$ 只是$v=\left( 1,1,-1\right)$ 的 另一种写法罢了，就像可以用$\overrightarrow{v}_{1}\left( a_{1},b_{1}\right)$表示二维空间的向量，$\overrightarrow{v}_{2}\left( a_{1},b_{1},c_{1}\right)$表示欧几里得坐标系的向量，那么其实至此我们还没有超出高中的范畴（指向量的相加；标量同向量的相乘等诸如此类）是这样吗？

###### 线性组合：
通过对$c\overrightarrow{u}$ 中$c$ 赋予不同的值来得到一条直线，即点的集合；通过对 $c\overrightarrow{u}+d\overrightarrow{v}$中 $c$和$d$ 赋予不同的值得到平面；以此类推得到 三维空间等等.

###### 对两道例题的讲解（？）
1.向量$v=\left( 1,1,0\right)$ 和$w=\left( 0,0,1\right)$ 的线性组合可得到一个平面，要求任意找出一个不在该平面上的向量.
将其表示为$c\overrightarrow{v}+d\overrightarrow{w}=C\begin{bmatrix} 1 \\ 1 \\ 0 \end{bmatrix}+d\begin{bmatrix} 0 \\ 1 \\ 1 \end{bmatrix}$，得到该平面实际是$\begin{bmatrix} c \\ c+d \\ d \end{bmatrix}$ .那么只需要找到一个向量并使其不满足这一条件就行了，如$\left( 1,2,3\right)$.

2.要求找到两个常数$c ，d$ ，使线性组合$c\overrightarrow{v}+d\overrightarrow{w}$ 等于向量b .其中$v=\begin{bmatrix} 2 \\ -1 \end{bmatrix} ，\omega =\begin{bmatrix} 1 \\ 2 \end{bmatrix}，b=\begin{bmatrix} 1 \\ 0 \end{bmatrix} .$
列出二元一次方程组求解即可.画到平面坐标系上似乎还是对俩箭头进行长度倍增缩短操作使其加和等效于第三个箭头这样.
实际上 矩阵是$\begin{bmatrix} 2 & -1 \\ -1 & 2 \end{bmatrix}$对向量$b$ 进行了一次线性变换（具体详见3b1b视频，直观地呈现了该过程），那么与此同时这道题其实是在问能否找到一个向量$\begin{bmatrix} c \\ d \end{bmatrix} ，在对其进行线性变换后得到的向量是已知的\begin{bmatrix} 1 \\ 0 \end{bmatrix} .$需要注意该变换后得到的向量仍然针对原坐标框架描述.

# 1.2 单位向量，以及点积$（Dot Product）$，模长

$需要注意的是点积结果与其计算先后顺序是无关系的，即满足交换律\overrightarrow{a}\cdot \overrightarrow{b}=\overrightarrow{b}\cdot \overrightarrow{a}$

$零向量同任意向量垂直.$

$模长的计算：\left\| v\right\| =\sqrt{v\cdot v}=\left( v_{1}^{2}+v_{2}^{2}+\ldots +v_{n}^{2}\right) ^{1/2}$

$两向量夹角满足关系：\cos 0=\dfrac{v\cdot w}{\left\| \upsilon \right\| \left\| w\right\| }$

$以及两个重要的不等式：\left| v\cdot w\right| \leq \left\| v\right\| \left\| w\right\|$
$\left\| v+w\right\| \leq \left\| \upsilon \right\| +\left\| w\right\|$

给这一节看完做了做题好像也没出现什么新的值得注意的概念，其实计算方法这些应该是没必要写的才对，需要时随时查就行了.其实$Deep  Learning$原书中靠前一部分是有数学基础关于线代的介绍的，奈何讲得太速通太抽象了

暂时搁置本页内容，效能太低了。




