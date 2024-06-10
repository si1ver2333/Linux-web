# 数据结构复习资料
## 第1章 引言

#### 1.1 数据结构的基本概念
- **定义**：数据结构是指相互之间存在一种或多种特定关系的数据元素的集合。
- **分类**：逻辑结构与物理结构。

#### 1.2 数据结构与算法
- **算法**：算法是对特定问题求解步骤的描述。
- **算法分析**：时间复杂度与空间复杂度。

## 第2章 线性表

#### 2.1 线性表的概念
- **定义**：线性表是由n个元素组成的有限序列。
- **操作**：插入、删除、查找、更新等。

#### 2.2 顺序表
- **定义**：用一段连续的存储单元来存储线性表的元素。
- **操作实现**：插入、删除、查找等。

#### 2.3 链表
- **单链表**：每个节点包含数据域和指针域。
- **双向链表**：每个节点包含前驱指针和后继指针。
- **循环链表**：尾节点的指针指向头节点。

## 第3章 栈和队列

#### 3.1 栈
- **定义**：栈是一种线性数据结构，遵循后进先出（LIFO）。
- **基本操作**：入栈（push）、出栈（pop）、取栈顶元素（top）等。

#### 3.2 队列
- **定义**：队列是一种线性数据结构，遵循先进先出（FIFO）。
- **基本操作**：入队（enqueue）、出队（dequeue）、取队首元素（front）等。
- **循环队列**：解决队列的假溢出问题。

## 第4章 串

#### 4.1 串的概念
- **定义**：串是由零个或多个字符组成的有限序列。
- **基本操作**：求串长、串连接、子串操作等。

#### 4.2 串的模式匹配
- **朴素匹配算法**：逐字符比较。
- **KMP算法**：利用部分匹配表加速匹配过程。

## 第5章 树

#### 5.1 树的概念
- **定义**：树是n（n≥0）个节点的集合。
- **基本术语**：节点、度、层次、深度、子树、父节点、叶子节点等。

#### 5.2 二叉树
- **定义**：每个节点最多有两个子树的树。
- **性质**：二叉树的性质。
- **遍历**：前序遍历、中序遍历、后序遍历、层次遍历。

#### 5.3 特殊二叉树
- **完全二叉树**：除最后一层外，所有层都是满的。
- **满二叉树**：每一层上的节点数都是最大值。
- **平衡二叉树**（AVL树）：任意节点的左右子树高度差不超过1。

#### 5.4 树与森林
- **树的表示**：双亲表示法、孩子表示法、孩子兄弟表示法。
- **树与二叉树的转换**：树转二叉树。

## 第6章 图

#### 6.1 图的概念
- **定义**：图由顶点的有穷非空集合和顶点之间边的集合组成。
- **基本术语**：顶点、边、路径、回路、连通图等。

#### 6.2 图的表示
- **邻接矩阵**：二维数组表示顶点间的边。
- **邻接表**：数组加链表结构表示邻接关系。

#### 6.3 图的遍历
- **深度优先搜索（DFS）**：递归或栈实现。
- **广度优先搜索（BFS）**：队列实现。

#### 6.4 最小生成树
- **Kruskal算法**：贪心算法，通过边的权值排序构建最小生成树。
- **Prim算法**：贪心算法，通过边的逐步扩展构建最小生成树。

#### 6.5 最短路径
- **Dijkstra算法**：解决单源最短路径问题。
- **Floyd算法**：解决多源最短路径问题。

## 第7章 查找

#### 7.1 线性查找
- **顺序查找**：按顺序查找元素。
- **哨兵法**：优化顺序查找。

#### 7.2 二分查找
- **基本思想**：每次比较中间元素，缩小查找范围。
- **前提条件**：适用于有序表。

#### 7.3 哈希查找
- **哈希函数**：将关键字映射到哈希表的位置。
- **冲突处理**：开放地址法、链地址法。

#### 7.4 平衡查找树
- **二叉查找树（BST）**：左子树小于根节点，右子树大于根节点。
- **平衡二叉树（AVL树）**：自平衡二叉搜索树。
- **红黑树**：每个节点带有颜色属性的二叉搜索树。

## 第8章 排序

#### 8.1 内部排序
- **交换排序**：冒泡排序、快速排序。
- **选择排序**：简单选择排序、堆排序。
- **插入排序**：直接插入排序、希尔排序。
- **归并排序**：两路归并排序、多路归并排序。
- **基数排序**：按位分配进行排序。

#### 8.2 外部排序
- **多路归并排序**：处理大量数据的排序算法。

## 第9章 文件与外存储器

#### 9.1 文件的概念
- **定义与分类**：按存取方式、信息类型等分类。
- **文件操作**：创建、打开、关闭、读写等。

#### 9.2 索引文件
- **基本概念**：通过索引提高文件的存取效率。
- **实现方法**：稀疏索引、密集索引、多级索引等。

#### 9.3 B树与B+树
- **B树**：平衡多路查找树。
- **B+树**：B树的变种，所有关键字都在叶子节点。